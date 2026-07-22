# Translation Terminology

This file contains locale-specific terminology and style rules for Hong Kong Traditional Chinese (`zh-HK`).

## Core Terms

| Term | zh-HK |
| --- | --- |
| Book | 賬簿 |
| Account | 戶口 |
| Transaction | 賬目 |
| Transaction Template | 賬目範本 |
| Budget | 預算 |
| Balance Sheet | 資產負債表 |
| Balance | 資產負債 |

## Direction Terms

| Term | zh-HK |
| --- | --- |
| Source | 轉出 |
| Destination | 轉入 |
| Withdrawal | 轉出 |
| Deposit | 轉入 |
| Amount Out | 轉出金額 |
| Amount In | 轉入金額 |

## Account Types

| Term | zh-HK |
| --- | --- |
| Asset | 資產 |
| Expense | 支出 |
| Income | 收入 |
| Liability | 債務 |
| Other | 其他 |

## Time and Range Terms

### Until

Use `截至` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Do not use a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `截至今日` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | zh-HK |
| --- | --- |
| Mode label | 截至 |
| Quick View label | 截至今日 |
| Range display | 截至 {{date}} |
| Current-date label | 截至今日 |

## Feature Terms

| Term | zh-HK |
| --- | --- |
| Daily Money One | 每日記賬簿One |
| Daily Money | 每日記賬簿 |
| Quick View | 快速檢視 |
| Chart | 圖表 |
| Distribution Chart | 財務分佈圖 |
| Trend Chart | 財務趨勢圖 |
| Trash | 垃圾桶 |
| Schedule | 排程 |
| Preferences | 偏好設定 |
| License | 授權 |
| Backup | 備份 |
| Restore | 還原 |
| Import | 匯入 |
| Export | 匯出 |

### Quick View

Use `快速檢視` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. For Financial Distribution Chart, continue to use `財務分佈圖快速檢視`.

### Financial Distribution Chart

Use `財務分佈圖` in both Markdown documentation and locale JSON. Keep the current Chinese UI labels instead of applying the shorter English UI pattern.

| Context | zh-HK |
| --- | --- |
| Documentation | 財務分佈圖 |
| No-period UI | 財務分佈圖 |
| Weekly UI | 週財務分佈圖 |
| Monthly UI | 月財務分佈圖 |
| Month-end UI | 至月底財務分佈圖 |
| Annual UI | 年財務分佈圖 |
| Quick View UI | 財務分佈圖快速檢視設定 |
| Home tab | 財務分佈圖 |

### Financial Trend Chart

Use `財務趨勢圖` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | zh-HK |
| --- | --- |
| Documentation | 財務趨勢圖 |
| No-mode UI | 財務趨勢圖 |
| LINE mode | 趨勢 |
| CUMULATIVE mode | 累計趨勢 |
| Quick View UI | 趨勢圖快速檢視設定 |
| Home tab | 財務趨勢圖 |

## Reconciliation Terms

| Term | zh-HK |
| --- | --- |
| Reconciled | 已核對 |
| Unreconciled | 未核對 |
| Reconciliation | 核對狀態 |
| Reconciliation Status | 核對狀態 |
| Reconciliation Mode | 核對模式 |

Use `已核對` and `未核對` for transaction reconciliation status labels.
Use `核對狀態` for search filters or settings that refer to the reconciliation status as a field.
Use `核對模式` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Term | zh-HK |
| --- | --- |
| Home Screen | 主頁 |
| Home | 主頁 |
| About | 關於 |
| Help | 如何使用 |
| UI | 用戶介面 |
| What's New | 有什麼新功能 |
| Release Notes | 版本歷史 |
| Credits | 特別感謝 |
| Third-Party Licenses | 第三方軟件授權 |
| Device Info | 手機裝置 |
| Platform | 程式平台 |
| EULA | 用戶授權協議 |
| Ads Consent | Google 廣告資料收集授權協議 |
| Accounts | 戶口管理 |
| Books | 賬簿管理 |
| Budgets | 預算管理 |
| Transactions | 賬目列表 |
| Daily Transactions | 日賬目列表 |
| Recent Updates | 最近異動賬目 |
| Search | 搜尋賬目 |
| Results | 搜尋結果 |
| Templates | 賬目範本管理 |
| Shortcuts | 主頁捷徑設定 |
| Preferences | 偏好設定 |
| Display | 顯示設定 |
| Functions | 功能設定 |
| Security | 安全設定 |
| Language | 語言設定 |
| Password | 密碼設定 |
| Clear Password | 清除密碼 |
| Date & Time | 日期時間設定 |
| Server Mode | 伺服器模式 |
| Data Maintenance | 資料維護 |
| Auto Backup | 自動備份資料庫 |
| Import CSV | 匯入 每日記賬簿+ CSV |
| Import JSON | 匯入 每日記賬簿One JSON |
| Google Drive Backups | Google Drive備份管理 |

## Style Rules

- Use `zh` as the primary source.
- Use Hong Kong wording and orthography where it differs from `zh`.
- Use `賬簿` for `Book`.
- Use `戶口` for accounting `Account`.
- Use `帳戶` only when the source clearly refers to a login account, user account, platform account, authorization account, or credential account.
- Use `用戶帳戶` for user accounts and `登入帳戶` for login-account contexts when an explicit account noun is needed.
- Avoid `賬戶` for general login/user account contexts; prefer `帳戶`.
- Do not use `戶口` for Google accounts, login accounts, authorization accounts, credential accounts, or other non-accounting identity concepts.
- Use `賬目` for `Transaction`.
- Use `賬目範本` for `Transaction Template`.
- Use `記賬` instead of `記帳`.
- Use `軟件` instead of `軟體`.
- Use `用戶` instead of `使用者` when referring to app users.
- Use `偏好設定` for `Preferences`.
- Keep UI labels short and consistent. Prefer `新增賬目`, `編輯賬目`, `賬目列表` over longer explanatory wording.
