# i18n TODO

This file records follow-up localization work for the next session.

## Context

- Follow `TRANSLATION.md` and `TERMINOLOGY.md`.
- Recent terminology work added ambiguous product-term rules.
- Product-specific terms must use the app domain meaning, not generic UI meanings.
- For overwrite-all translation tasks, do not inspect or reuse old target-locale content unless the task is explicitly a review or incremental cleanup.

## Already Done

- Added ambiguous-term guidance to `TERMINOLOGY.md`.
- Added `zh-CN` Style Rules:
  - `Book` -> `账本`
  - accounting `Account` -> `账户`
  - login/user/platform account -> `账号`
  - `Transaction` -> `记录`
  - `Transaction Template` -> `记录模板`
- Updated `zh-CN/whatIsNew.md` product `Transaction` wording from `账目/帐目` to `记录`.
- Fixed `zh/zh.json` and `zh-CN/zh-CN.json` mapping messages from `帳號/账号` wording to accounting `帳戶/账户` wording.
- Updated `zh-HK/whatIsNew.md` obvious terminology drift:
  - `每日記帳本` -> `每日記賬簿`
  - `帳本` -> `賬簿`
  - `賬戶` -> `戶口`
- Updated `TRANSLATION.md` to require scans for ambiguous product terms and terminology drift across locales.
- Updated Japanese files so accounting `Account` uses `科目` instead of `アカウント`.

## Pending Work

1. Strengthen `zh-HK` login/user account rules in `TERMINOLOGY.md`.
   - Keep accounting `Account` as `戶口`.
   - Add a rule for general account meanings, for example:
     - login/user account -> `用戶帳戶` or `登入帳戶`
     - platform account / authorization account / credential account -> use a clear non-`戶口` term.
   - Decide whether to use `帳戶` or `賬戶` for general login/user account in Hong Kong Traditional Chinese.

2. Review `zh-HK.json` for login/user account contexts.
   - Search for Google sign-in, user identity, authorization, credentials, and account wording.
   - Confirm accounting `Account` remains `戶口`.
   - Confirm general user/login account wording does not accidentally use `戶口`.
   - Current quick impression: most strings use `登入Google` and `用戶資料`, so this may only need confirmation.

3. Do not broad-rewrite Chinese docs yet.
   - `zh-HK`, `zh-CN`, and `zh` documents have only received terminology drift fixes.
   - Full naturalness polish, punctuation cleanup, and regional style cleanup are still optional future work.
   - If doing this, handle one locale at a time and avoid changing product meaning.

4. Review other locales for ambiguous product-term drift.
   - Prioritize languages where `Account`, `Book`, `Transaction`, `Source`, `Destination`, or `Balance` may have generic UI meanings.
   - Check whether translations use login-account wording for accounting `Account`.
   - Check whether `Transaction` is translated as trade/payment/bank transaction when the app-specific accounting record meaning is intended.
   - Update `TERMINOLOGY.md` with per-locale Style Rules only when a stable decision is made.

## Suggested Verification

- For JSON files, run parse checks after edits.
- Compare interpolation placeholders such as `{{name}}` and i18n references such as `$t(...)` when JSON strings change.
- Use `rg` to scan for old or non-local terminology after each locale cleanup.
- Keep changes scoped; do not retranslate unrelated text unless the task explicitly asks for a full rewrite.
