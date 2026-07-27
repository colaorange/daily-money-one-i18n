# Translation Terminology

This file contains locale-specific terminology and style rules for Traditional Chinese (`zh`).

## Time and Range Terms

### Until

Use `截至` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Do not use a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `截至今天` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | zh |
| --- | --- |
| Mode label | 截至 |
| Quick View label | 截至今天 |
| Range display | 截至 {{date}} |
| Current-date label | 截至今天 |

## Feature Terms

### Quick View

Use `快速檢視` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. For Financial Distribution Chart, continue to use `財務分布圖快速檢視`.

### Financial Distribution Chart

Use `財務分布圖` in both Markdown documentation and locale JSON. Keep the current Chinese UI labels instead of applying the shorter English UI pattern.

| Context | zh |
| --- | --- |
| Documentation | 財務分布圖 |
| No-period UI | 財務分布圖 |
| Weekly UI | 週財務分布圖 |
| Monthly UI | 月財務分布圖 |
| Month-end UI | 至月底財務分布圖 |
| Annual UI | 年財務分布圖 |
| Quick View UI | 財務分布圖快速檢視設定 |
| Home tab | 財務分布圖 |

### Financial Trend Chart

Use `財務趨勢圖` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | zh |
| --- | --- |
| Documentation | 財務趨勢圖 |
| No-mode UI | 財務趨勢圖 |
| LINE mode | 趨勢 |
| CUMULATIVE mode | 累計趨勢 |
| Quick View UI | 趨勢圖快速檢視設定 |
| Home tab | 財務趨勢圖 |

## Style Rules

- Use `帳本` for `Book`.
- Use `帳戶` for `Account`.
- Use `帳目` for `Transaction`.
- Use `帳目範本` for `Transaction Template`.
- Use `轉出` for `Source` or withdrawal-side concepts.
- Use `轉入` for `Destination` or deposit-side concepts.
- Use `資產負債表` when referring to the report/table screen.
- Use `資產負債` when referring to the balance concept in a shorter UI label.
- Keep UI labels short and consistent. Prefer `新增帳目`, `編輯帳目`, `帳目列表` over longer explanatory wording.
