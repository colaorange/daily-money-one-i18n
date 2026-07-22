# Terminology

This document defines the preferred wording for key product terms when translating Daily Money One.

Traditional Chinese (`zh`) is the original product language and the primary reference for Chinese-related languages. English (`en`) is the primary reference for non-Chinese languages. Other languages should follow the meaning defined here, not literal accounting terms from other products.

## Reference Languages

Only `en` and `zh` are maintained in this document for now. The tables below are reference examples, not a requirement to add every future language as another column.

For Chinese-related languages, such as Simplified Chinese and Traditional Chinese variants, use `zh` as the main reference. For other languages, use `en` as the main reference.

## Term Selection Principles

When translating product terms, choose the wording that best represents the app-specific concept naturally in the target language. Do not keep a short English-inspired term or loanword only because the English source is short.

Prefer the clearest local term first. If that wording is too long for repeated UI labels, compact screens, tabs, buttons, or charts, then choose a shorter natural term that still preserves the app-specific meaning.

## Core Terms

| Term | en | zh |
| --- | --- | --- |
| Book | Book | 帳本 |
| Account | Account | 帳戶 |
| Transaction | Transaction | 帳目 |
| Transaction Template | Template / Transaction Template | 帳目範本 |
| Budget | Budget | 預算 |
| Balance Sheet | Balance Sheet | 資產負債表 |
| Balance | Balance | 資產負債 |

### Book

Use `Book` in English. Do not expand it to `Accounting Book`, `Ledger`, or `Account Book`.

In this app, a Book is the top-level container for accounting data. A Book contains Accounts and Transactions, and it also defines currency-related settings such as currency code, symbol, and decimal places.

For Traditional Chinese, use `帳本`.

Reference examples:

| en | zh |
| --- | --- |
| New Book | 新增帳本 |
| Edit Book | 編輯帳本 |
| Book Management | 帳本管理 |
| Book not found | 找不到帳本 |

### Account

Use `Account` in English.

In this app, an Account is an item inside a Book used for classification and balance calculation. It can represent cash, bank accounts, credit cards, income categories, expense categories, liability categories, or other custom categories.

For Traditional Chinese, use `帳戶`.

Reference examples:

| en | zh |
| --- | --- |
| New Account | 新增帳戶 |
| Edit Account | 編輯帳戶 |
| Account Type | 帳戶類型 |
| Account Management | 帳戶管理 |

### Transaction

Use `Transaction` in English.

In this app, a Transaction is a record that moves an amount from one side to another. Do not translate it as a generic trade, payment, or bank transaction unless the target language has no better app-specific term.

For Traditional Chinese, use `帳目`.

Reference examples:

| en | zh |
| --- | --- |
| New Transaction | 新增帳目 |
| Edit Transaction | 編輯帳目 |
| Transaction List | 帳目列表 |
| No transactions | 沒有任何帳目 |

### Transaction Template

Use `Template` when the UI context is already under transactions. Use `Transaction Template` when the context is ambiguous.

For Traditional Chinese, use `帳目範本`.

Reference examples:

| en | zh |
| --- | --- |
| New Template | 建立範本 |
| New Transaction Template | 建立帳目範本 |
| Transaction Template Management | 帳目範本管理 |

## Direction Terms

| Term | en | zh |
| --- | --- | --- |
| Source | Source | 轉出 |
| Destination | Destination | 轉入 |
| Withdrawal | Source | 轉出 |
| Deposit | Destination | 轉入 |
| Amount Out | Amount Out | 轉出金額 |
| Amount In | Amount In | 轉入金額 |

### Source and Destination

Use `Source` and `Destination` in English UI labels.

These terms describe the two sides of a Transaction. `Source` is the side where the amount leaves. `Destination` is the side where the amount enters.

For Traditional Chinese, use `轉出` and `轉入`.

Reference examples:

| en | zh |
| --- | --- |
| Source account | 轉出帳戶 |
| Destination account | 轉入帳戶 |
| Source Book | 轉出帳本 |
| Destination Book | 轉入帳本 |

## Account Types

| Term | en | zh |
| --- | --- | --- |
| Asset | Asset | 資產 |
| Expense | Expense | 支出 |
| Income | Income | 收入 |
| Liability | Liability | 債務 |
| Other | Other | 其他 |

These are Account type labels. Keep them short because they appear in tabs, filters, charts, and compact lists.

## Time and Range Terms

| Term | en | zh |
| --- | --- | --- |
| Daily | Daily | 每日 |
| Weekly | Weekly | 每週 |
| Monthly | Monthly | 每月 |
| Yearly | Yearly | 每年 |
| Until | Until | 直到 |
| Initial | Initial | 初始化 |
| Custom | Custom | 自定區間 |

Use these consistently for report modes, budget modes, schedule modes, and transaction list modes.

## Feature Terms

| Term | en | zh |
| --- | --- | --- |
| Daily Money One | Daily Money One | 每日記帳本One |
| Daily Money | Daily Money | 每日記帳本 |
| Quick View | Quick View | 快速檢視 |
| Chart | Chart | 圖表 |
| Distribution Chart | Financial Distribution Chart | 財務分布圖 |
| Trend Chart | Financial Trend Chart | 財務趨勢圖 |
| Trash | Trash | 垃圾桶 |
| Schedule | Schedule | 排程 |
| Preferences | Preferences | 喜好設定 |
| License | License | 授權 |
| Backup | Backup | 備份 |
| Restore | Restore | 還原 |
| Import | Import | 匯入 |
| Export | Export | 匯出 |

When translating from English into other languages, keep `Daily Money One` and `Daily Money` untranslated and use the English names exactly.

### Quick View

A Quick View is a saved, continuously updated view of a result that would otherwise require multiple UI operations to reach. It is placed on the Home Screen so the user can see that result directly without repeating those operations.

Quick View is not a summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Translate the product concept naturally; a locale does not need to reproduce the English words `Quick` and `View` literally.

Use `Quick View` in English and `快速檢視` in Traditional Chinese. Each locale's final term and any locale-specific usage rules must be recorded in that locale's `translationTerminology.md` under `### Quick View` before changing locale JSON.

When a combined Quick View label is too long for the UI, shorten only the redundant surrounding feature words or use a compact local structure. Retain the meanings of both Quick View and the viewed feature. Do not shorten a natural label merely for cross-locale uniformity, and do not remove words when the existing localized label already fits.

### Financial Distribution Chart

Use `Financial Distribution Chart` as the full English name in Markdown documentation and long-form prose. Do not pluralize this official name. For Traditional Chinese, continue to use `財務分布圖` in both UI and documentation.

English UI labels stored in locale JSON use shorter forms:

- When a period appears first, use `{Period} Distribution`, such as `Weekly Distribution`, `Monthly Distribution`, `Month-end Distribution`, and `Annual Distribution`.
- When no period appears, use `Financial Distribution`.
- For Quick View, use `Financial Distribution Quick View`.
- For the Home tab, use `Distribution`.

These compact forms are for UI labels and UI messages only. Markdown documentation must retain the full name `Financial Distribution Chart`. For the Traditional Chinese Home tab, use `財務分布圖`.

This feature displays the distribution of values across account types or accounts. It can include assets, liabilities, income, and expenses. Do not use `Balance Chart`, `Distribution Chart`, `資產負債圖表`, or `分布圖` for this feature.

### Financial Trend Chart

Use `Financial Trend Chart` as the full English name in Markdown documentation and long-form prose. For Traditional Chinese, use `財務趨勢圖`.

Use the approved context-specific labels in locale JSON:

| Context | en | zh |
| --- | --- | --- |
| Documentation | Financial Trend Chart | 財務趨勢圖 |
| No-mode UI | Financial Trend | 財務趨勢圖 |
| LINE mode | Trend | 趨勢 |
| CUMULATIVE mode | Cumulative Trend | 累計趨勢 |
| Quick View UI | Trend Quick View | 趨勢圖快速檢視設定 |
| Home tab | Trends | 財務趨勢圖 |

This feature displays account values over time. LINE mode shows each period's net change. CUMULATIVE mode starts from the opening balance, when available, and accumulates each period's net change.

Do not translate this feature as `Financial Distribution Chart`, `Balance Chart`, or a financial-market price chart. Do not use the full documentation name in compact UI contexts when the locale has an approved shorter label.

## Reconciliation Terms

| Term | en | zh |
| --- | --- | --- |
| Reconciled | Reconciled | 已核對 |
| Unreconciled | Unreconciled | 未核對 |
| Reconciliation | Reconciliation Status | 核對狀態 |
| Reconciliation Status | Reconciliation Status | 核對狀態 |
| Reconciliation Mode | Reconciliation Mode | 核對模式 |

Use `Reconciled` / `已核對` and `Unreconciled` / `未核對` for transaction reconciliation status labels.
Use `Reconciliation Status` / `核對狀態` for search filters or settings that refer to the reconciliation status as a field.
Use `Reconciliation Mode` / `核對模式` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

Use these terms for screen names, navigation labels, settings pages, and other UI-facing labels.

| Term | en | zh |
| --- | --- | --- |
| Home Screen | Home Screen | 主頁 |
| Home | Home | 主頁 |
| About | About | 關於 |
| Help | Help | 如何使用 |
| UI | UI | 使用者介面 |
| What's New | What's New | 有什麼新功能 |
| Release Notes | Release Notes | 版本歷史 |
| Credits | Credits | 特別感謝 |
| Third-Party Licenses | Third-Party Licenses | 第三方軟體授權 |
| Device Info | Device Info | 手機設備 |
| Platform | Platform | 程式平台 |
| EULA | EULA | 使用者許可協議 |
| Ads Consent | Ads Consent | Google 廣告收集許可協議 |
| Accounts | Accounts | 帳戶管理 |
| Books | Books | 帳本管理 |
| Budgets | Budgets | 預算管理 |
| Transactions | Transactions | 帳目列表 |
| Daily Transactions | Daily Transactions | 日帳目列表 |
| Recent Updates | Recent Updates | 最近異動帳目 |
| Search | Search | 搜尋帳目 |
| Results | Results | 搜尋結果 |
| Templates | Templates | 帳目範本管理 |
| Shortcuts | Shortcuts | 主頁捷徑設定 |
| Preferences | Preferences | 喜好設定 |
| Display | Display | 顯示設定 |
| Functions | Functions | 功能設定 |
| Security | Security | 安全設定 |
| Language | Language | 語言設定 |
| Password | Password | 密碼設定 |
| Clear Password | Clear Password | 清除密碼 |
| Date & Time | Date & Time | 日期時間設定 |
| Server Mode | Server Mode | 伺服器模式 |
| Data Maintenance | Data Maintenance | 資料維護 |
| Auto Backup | Auto Backup | 自動備份資料庫 |
| Import CSV | Import CSV | 匯入 每日記帳本+ CSV |
| Import JSON | Import JSON | 匯入 每日記帳本One JSON |
| Google Drive Backups | Google Drive Backups | Google Drive備份管理 |

### Home Screen and Home

Use `Home Screen` when referring to the app's main UI area or main tab. For Traditional Chinese, use `主頁`.

Use `Home` when referring to the home screen label already used by the app. For Traditional Chinese, use `主頁`.

## Ambiguous Terms

Some English terms have product-specific meanings in Daily Money One. Translate these terms by their app-specific meaning unless the source context clearly refers to a general software, identity, file, network, or platform concept.

When a term is ambiguous, first decide whether the source refers to the Daily Money One domain model. If it does, use the product terminology. Only use the general UI translation when the surrounding source text clearly points to the general meaning.

| Term | Product-specific meaning | General meaning examples |
| --- | --- | --- |
| Account | Accounting item inside a Book, used for classification and balance calculation | Login account, Google account, user account, credential account |
| Book | Top-level accounting data container | Physical book, generic ledger, document |
| Transaction | Accounting record that moves an amount from Source to Destination | Commercial trade, payment processor transaction, bank transaction |
| Source | Side where the amount leaves in a Transaction | Data source, file source, origin |
| Destination | Side where the amount enters in a Transaction | File destination, network destination, navigation destination |
| Balance | Accounting balance in the app | General balance, equilibrium |

### Account Context

In Daily Money One, `Account` usually means an accounting item inside a Book. It can represent cash, bank accounts, credit cards, income categories, expense categories, liability categories, or other custom categories. Do not translate this accounting `Account` as a login or user account.

When the source clearly refers to sign-in, Google identity, authorization, credentials, or app users, translate it as a login/user account term appropriate for the target language.

Examples:

| Source | Meaning |
| --- | --- |
| New Account | Accounting Account |
| Account Type | Accounting Account |
| Source account | Accounting Account |
| Google account | Login/user account |
| Sign in with Google | Login action |
| User account | User identity |

## Adding New Languages

When adding a Chinese-related language, use `zh` as the primary source and use `en` only as a secondary reference. When adding any other language, use `en` as the primary source and use `zh` only as a secondary reference to clarify the app-specific meaning.

Do not add the new language to every table in this document. Add a language section here only when that language becomes a maintained reference language for future translations.

## Style Rules

Locale-specific style rules are maintained in each locale directory as `translationTerminology.md`. Keep this document focused on shared product terminology, reference-language policy, and cross-locale ambiguity rules.

When translating a target locale, read only the shared terminology in this file plus the terminology files needed for that locale:

- For English-based locales, use `./en/translationTerminology.md` as the primary base reference and `./zh/translationTerminology.md` only as a secondary reference when the product meaning is unclear.
- For Chinese-based locales, use `./zh/translationTerminology.md` as the primary base reference and `./en/translationTerminology.md` only as a secondary reference when the product meaning is unclear.
- If the target locale already has `./<locale>/translationTerminology.md`, read it together with the appropriate base reference files.
- If the target locale does not yet have `translationTerminology.md`, create it during the terminology phase after the proposed locale-specific terminology and style rules are confirmed. This file must contain the localized terminology tables corresponding to all term tables in this document, followed by the target locale's specific style rules.

