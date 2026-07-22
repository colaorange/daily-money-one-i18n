# Translation Terminology

This file contains locale-specific terminology and style rules for English (`en`).

## Time and Range Terms

### Until

`Until` is a cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. It is not a custom date range.

The `Until` Quick View always ends on the current date. Use `Until Today` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | en |
| --- | --- |
| Mode label | Until |
| Quick View label | Until Today |
| Range display | Until {{date}} |
| Current-date label | Until Today |

## Feature Terms

### Quick View

Use `Quick View` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. For the compact Distribution Chart UI label, use `Financial Distribution Quick View`.

### Financial Distribution Chart

Use the full name `Financial Distribution Chart` in Markdown documentation. Use shorter names in locale JSON UI labels and messages.

| Context | en |
| --- | --- |
| Documentation | Financial Distribution Chart |
| No-period UI | Financial Distribution |
| Weekly UI | Weekly Distribution |
| Monthly UI | Monthly Distribution |
| Month-end UI | Month-end Distribution |
| Annual UI | Annual Distribution |
| Quick View UI | Financial Distribution Quick View |
| Home tab | Distribution |

### Financial Trend Chart

Use `Financial Trend Chart` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | en |
| --- | --- |
| Documentation | Financial Trend Chart |
| No-mode UI | Financial Trend |
| LINE mode | Trend |
| CUMULATIVE mode | Cumulative Trend |
| Quick View UI | Trend Quick View |
| Home tab | Trends |

## Style Rules

- Keep the product wording simple and app-specific.
- Use `Book`, not `Accounting Book`, `Ledger`, or `Account Book`.
- Use `Account`, not `Category`, even when the account represents an income or expense category.
- Use `Transaction`, not `Entry`, unless referring specifically to initial entries in import summaries.
- Use `Source` and `Destination` for transaction directions.
- Use title case for screen titles and action labels.
