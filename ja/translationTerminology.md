# Translation Terminology

This file contains locale-specific terminology and style rules for Japanese (`ja`).

## Core Terms

| Term | ja |
| --- | --- |
| Book | 帳簿 |
| Account | 科目 |
| Transaction | 取引 |
| Transaction Template | 取引テンプレート |
| Template | テンプレート |
| Budget | 予算 |
| Balance Sheet | 残高表 |
| Balance | 残高 |

Use `テンプレート` when the UI context is already under transactions. Use `取引テンプレート` when the context is ambiguous.

## Direction Terms

| Term | ja |
| --- | --- |
| Source | 出金元 |
| Destination | 入金先 |
| Withdrawal | 出金元 |
| Deposit | 入金先 |
| Amount Out | 出金額 |
| Amount In | 入金額 |

Use `出金元` and `入金先` for the two sides of a transaction. Use `出金額` and `入金額` for the corresponding amounts.

## Account Types

| Term | ja |
| --- | --- |
| Asset | 資産 |
| Expense | 支出 |
| Income | 収入 |
| Liability | 負債 |
| Other | その他 |

## Feature Terms

| Term | ja |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | クイックビュー |
| Chart | グラフ |
| Distribution Chart | 財務分布グラフ |
| Trash | ゴミ箱 |
| Schedule | スケジュール |
| Preferences | 設定 |
| License | ライセンス |
| Backup | バックアップ |
| Restore | 復元 |
| Import | インポート |
| Export | エクスポート |

### Quick View

Use `クイックビュー` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Japanese locale JSON.

### Financial Distribution Chart

Use `財務分布グラフ` in Markdown documentation. In compact locale JSON UI labels, omit `財務` and `グラフ` when a period appears first.

| Context | ja |
| --- | --- |
| Documentation | 財務分布グラフ |
| No-period UI | 財務分布 |
| Weekly UI | 週次分布 |
| Monthly UI | 月次分布 |
| Month-end UI | 月末分布 |
| Annual UI | 年次分布 |
| Quick View UI | 財務分布のクイックビュー |

## Reconciliation Terms

| Term | ja |
| --- | --- |
| Reconciled | 照合済み |
| Unreconciled | 未照合 |
| Reconciliation | 照合状態 |
| Reconciliation Status | 照合状態 |
| Reconciliation Mode | 照合モード |

Use `照合済み` and `未照合` for transaction reconciliation status labels.
Use `照合状態` for search filters or settings that refer to the reconciliation status as a field.
Use `照合モード` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Term | ja |
| --- | --- |
| Home Screen | ホーム画面 |
| Home | ホーム |
| About | 情報 |
| Help | ヘルプ |
| UI | UI |
| What's New | 新着情報 |
| Release Notes | リリースノート |
| Credits | スペシャルサンクス |
| Third-Party Licenses | サードパーティライセンス |
| Device Info | デバイス情報 |
| Platform | プラットフォーム |
| EULA | EULA |
| Ads Consent | 広告の同意 |
| Accounts | 科目 |
| Books | 帳簿 |
| Budgets | 予算 |
| Transactions | 取引 |
| Daily Transactions | 日次取引 |
| Recent Updates | 最近の更新 |
| Search | 検索 |
| Results | 結果 |
| Templates | テンプレート |
| Shortcuts | ショートカット |
| Preferences | 設定 |
| Display | 表示 |
| Functions | 機能 |
| Security | セキュリティ |
| Language | 言語 |
| Password | パスワード |
| Clear Password | パスワードをクリア |
| Date & Time | 日時 |
| Server Mode | サーバーモード |
| Data Maintenance | データメンテナンス |
| Auto Backup | 自動バックアップ |
| Import CSV | CSVインポート |
| Import JSON | JSONインポート |
| Google Drive Backups | Google Driveバックアップ |

## Style Rules

- Use `en` as the primary source.
- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `帳簿` for `Book`.
- Use `科目` for accounting `Account`.
- Use `アカウント` only when the source clearly refers to a login account, Google account, user account, authorization account, or credential account.
- Use `取引` for `Transaction`.
- Use `取引テンプレート` for `Transaction Template`.
- Use `テンプレート` when the UI context is already under transactions.
- Use `出金元` for `Source` or withdrawal-side concepts.
- Use `入金先` for `Destination` or deposit-side concepts.
- Use `残高表` for `Balance Sheet`.
- Use `残高` for the balance concept in shorter UI labels.
- Keep UI labels short and consistent. Prefer `新規取引`, `取引を編集`, `取引一覧` over longer explanatory wording.
