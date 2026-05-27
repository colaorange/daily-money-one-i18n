# Translation Workflow

This document records the translation workflow used for Daily Money One localization tasks.

## Process

1. Before starting, ask whether to overwrite all target locale files and ignore old content, or only update specific parts.
2. Use the directory containing the working `TRANSLATION.md` file as the working directory.
3. Translate the target locale terminology first, following `./TERMINOLOGY.md` and the required `translationTerminology.md` files; wait for confirmation before continuing.
4. After the target locale terminology is confirmed, write back or update the target locale terminology and Style Rules in `./<locale>/translationTerminology.md` before translating files.
5. Re-read `./TERMINOLOGY.md` and the required `translationTerminology.md` files after the confirmed terminology update.
6. Translate the target locale JSON file; wait for confirmation before continuing.
7. Translate the remaining target locale documents.

### Mandatory Phase Separation

For target locales that do not already have confirmed terminology in `./<locale>/translationTerminology.md`, split the work into two separate phases:

1. Terminology phase:
   - Translate the target locale terminology and style rules first.
   - For the terminology tables, localize all the terminology tables found in `./TERMINOLOGY.md` (Core Terms, Direction Terms, Account Types, Feature Terms, UI Terms) to the target language.
   - Include locale-specific style rules that must be fixed for consistent translation.
   - Present the proposed terminology and style rules for review.
   - Do not translate or write target JSON or Markdown files in this phase.
   - After confirmation, write the localized terminology tables and style rules to `./<locale>/translationTerminology.md` only.

2. File translation phase:
   - Start only after the target locale terminology has been confirmed and written to `./<locale>/translationTerminology.md`.
   - Then translate and write the target JSON and Markdown files.

Do not combine terminology updates and target file translation in the same execution step unless the user explicitly says the terminology is already confirmed and asks to proceed with all files.

When the task explicitly says to overwrite all target locale files, do not inspect, compare, or reuse the old target locale content. Use only the source references, terminology, and style rules to regenerate the target outputs.

## Encoding

- Read all source localization files as UTF-8.
- Write all translated output files as UTF-8.

## Source References

- Use `TERMINOLOGY.md` as the terminology and style authority.
- Use only the terminology files needed for the target locale.
- If the target locale has `./<locale>/translationTerminology.md`, read it together with the required base terminology files.
- If the target locale does not have `./<locale>/translationTerminology.md`, create it only during the confirmed terminology phase.
- For Chinese-related languages workflow, the translated content was based on:
  - `./zh/zh.json`
  - `./zh/zh.dev.json`
  - `./zh/dailyMoney.md`
  - `./zh/howToUse.md`
  - `./zh/store.md`
  - `./zh/whatIsNew.md`
  - `./zh/eula.md`
  - `./zh/gaca.md`
- For non-Chinese languages workflow, the translated content was based on:
  - `./en/en.json`
  - `./en/en.dev.json`
  - `./en/dailyMoney.md`
  - `./en/howToUse.md`
  - `./en/store.md`
  - `./en/whatIsNew.md`
  - `./en/eula.md`
  - `./en/gaca.md`

## Target Outputs

- Write the localized terminology tables and style rules to the target locale terminology file:
  - `./<locale>/translationTerminology.md`
- Write translated JSON to the target locale JSON file, for example:
  - `./<locale>/<locale>.json` 
  - `./<locale>/<locale>.dev.json`
- Write translated Markdown files to the target locale directory, for example:
  - `./<locale>/dailyMoney.md`
  - `./<locale>/howToUse.md`
  - `./<locale>/store.md`
  - `./<locale>/whatIsNew.md`
  - `./<locale>/eula.md`
  - `./<locale>/gaca.md`
- Existing files in the target locale directory may be overwritten when the task explicitly allows it.
- When overwriting all target locale files, old target locale files are replacement targets only. Do not read them for translation decisions, consistency checks, or gap analysis.
- Treat the target output list as the scope of the task. Do not create or update extra target files just because matching source files exist, unless the user explicitly asks for them.

## Translation Rules

- Follow `TERMINOLOGY.md` for product terms, UI labels, and feature names.
- Follow the required `translationTerminology.md` files for locale-specific style rules, regional wording, and target-locale terminology.
- Do not rely on simple script or character conversion when translating between related languages.
- Use the natural local wording, phrasing, and orthography of the target locale so local readers can understand the text easily.
- Preserve Markdown structure, image links, icon links, URLs, headings, and list structure unless the source text requires a natural local rewrite.
- Preserve JSON structure, keys, interpolation placeholders such as `{{name}}`, and i18n references such as `$t(...)`.
- Keep UI labels short and consistent with the app terminology.
- After translating or updating a locale, scan for ambiguous product terms listed in `TERMINOLOGY.md` and fix any target-language wording that uses a general UI meaning instead of the Daily Money One product meaning.
- After translating or updating a locale, scan for terminology drift from other locales or older translations, including product terms, regional wording, orthography, and non-local phrasing.
- For closely related locale variants, also check variant-specific writing systems and regional terms, such as Simplified/Traditional Chinese, European/Brazilian Portuguese, or regional Spanish wording. Resolve any leftover source-language characters, mixed orthography, or clearly non-local wording in context instead of maintaining long per-language replacement lists.
- After translating JSON, validate that the file can be parsed and compare interpolation placeholders against the source file.
- In `store.md`, keep `Short description` at 80 characters or fewer.
- In `store.md`, keep `Long description` at 4000 characters or fewer.
- After translating `store.md`, check both description lengths. If either exceeds the limit, shorten less important sentences while preserving key product meaning and terminology.

## Translation Review

Translation is not complete after the first written output. Always perform a second-pass review before reporting completion.

- Review the translation against the surrounding context, not sentence by sentence in isolation.
- Compare each translated section with the source meaning and confirm that no meaning was omitted, added, reversed, or over-literalized.
- Check that product-specific terms follow `TERMINOLOGY.md`, and that general-language uses of ambiguous words are still translated by context.
- After translating, produce a terminology conformance report before reporting completion. For each target locale, read that locale's actual `./<locale>/translationTerminology.md`, identify the terminology entries relevant to the translated content, and report the source/product term, required target term, applied key or string, and PASS/FAIL result. Build this report from the terminology file used for that locale, not from a fixed global checklist. If a relevant term is defined in the terminology file but the translation does not use it, fix the translation before reporting completion.
- If a target locale introduces new ambiguous words or product-specific wording risks that are not already covered by `TERMINOLOGY.md`, pause and propose them for confirmation. After confirmation, add shared ambiguity rules to `TERMINOLOGY.md` under `## Ambiguous Terms` and add locale-specific rules to `./<locale>/translationTerminology.md` before continuing.
- For JSON files, review short UI labels separately from longer messages:
  - Short UI labels should be concise, natural, and consistent with app terminology.
  - Longer messages should read naturally in the target locale and should not sound like direct machine translation.
- For Markdown files, review headings, lists, links, image references, icon references, and paragraph flow after translation.
- For store listing text, review the result as user-facing marketing copy in the target locale, while still respecting the length limits.
- For every locale, check for wrong writing system, mixed orthography, leftover source-language words, and non-local phrasing. Fix these by context rather than by maintaining long per-locale replacement lists.
- When the target language is not familiar to the requester, still perform the same self-review and report the checks that were completed.

## Validation Checklist

Before reporting completion, validate and summarize the following:

- Target files are limited to the requested target outputs.
- JSON files parse successfully.
- JSON keys match the source reference files.
- Interpolation placeholders such as `{{name}}` and i18n references such as `$t(...)` match the source.
- Required terminology from `TERMINOLOGY.md` and the required `translationTerminology.md` files is used consistently.
- A target-locale terminology conformance report was included, generated from the actual `./<locale>/translationTerminology.md` entries relevant to the translated content.
- The target locale's writing system and regional wording were checked.
- Long-form Markdown and store text received a context and naturalness review.
- `store.md` short and long description lengths are within limits.
