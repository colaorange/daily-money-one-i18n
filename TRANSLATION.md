# Translation Workflow

This document records the translation workflow used for Daily Money One localization tasks.

## Process

1. Before starting, ask whether to overwrite all target locale files and ignore old content, or only update specific parts.
2. Use the directory containing the working `TRANSLATION.md` file as the working directory.
3. Translate the target locale terminology first, following `./TERMINOLOGY.md`; wait for confirmation before continuing.
4. After the target locale terminology is confirmed, write back or update the target locale terminology and Style Rules in `./TERMINOLOGY.md` before translating files.
5. Translate the target locale JSON file; wait for confirmation before continuing.
6. Translate the remaining target locale documents.

When the task explicitly says to overwrite all target locale files, do not inspect, compare, or reuse the old target locale content. Use only the source references, terminology, and style rules to regenerate the target outputs.

## Encoding

- Read all source localization files as UTF-8.
- Write all translated output files as UTF-8.

## Source References

- Use `TERMINOLOGY.md` as the terminology and style authority.
- Use the maintained reference language files listed in `TERMINOLOGY.md`:
- For Chinese-related languages workflow, the translated content was based on:
  - `./zh/zh.json`
  - `./zh/dailyMoney.md`
  - `./zh/howToUse.md`
  - `./zh/store.md`
- For non-Chinese languages workflow, the translated content was based on:
  - `./en/en.json`
  - `./en/dailyMoney.md`
  - `./en/howToUse.md`
  - `./en/store.md`

## Target Outputs

- Write translated JSON to the target locale JSON file, for example `i18n/<locale>/<locale>.json`.
- Write translated Markdown files to the target locale directory, for example:
  - `./<locale>/dailyMoney.md`
  - `./<locale>/howToUse.md`
  - `./<locale>/store.md`
- Existing files in the target locale directory may be overwritten when the task explicitly allows it.
- When overwriting all target locale files, old target locale files are replacement targets only. Do not read them for translation decisions, consistency checks, or gap analysis.

## Translation Rules

- Follow `TERMINOLOGY.md` for product terms, UI labels, and feature names.
- Do not rely on simple script or character conversion when translating between related languages.
- Use the natural local wording, phrasing, and orthography of the target locale so local readers can understand the text easily.
- Preserve Markdown structure, image links, icon links, URLs, headings, and list structure unless the source text requires a natural local rewrite.
- Preserve JSON structure, keys, interpolation placeholders such as `{{name}}`, and i18n references such as `$t(...)`.
- Keep UI labels short and consistent with the app terminology.
- After translating or updating a locale, scan for ambiguous product terms listed in `TERMINOLOGY.md` and fix any target-language wording that uses a general UI meaning instead of the Daily Money One product meaning.
- After translating or updating a locale, scan for terminology drift from other locales or older translations, including product terms, regional wording, orthography, and non-local phrasing.
- For closely related locale variants, also check variant-specific writing systems and regional terms, such as Simplified/Traditional Chinese, European/Brazilian Portuguese, or regional Spanish wording.
- After translating JSON, validate that the file can be parsed and compare interpolation placeholders against the source file.
- In `store.md`, keep `Short description` at 80 characters or fewer.
- In `store.md`, keep `Long description` at 4000 characters or fewer.
- After translating `store.md`, check both description lengths. If either exceeds the limit, shorten less important sentences while preserving key product meaning and terminology.
