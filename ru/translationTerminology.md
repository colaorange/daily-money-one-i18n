# Translation Terminology

This file contains locale-specific terminology and style rules for Russian (`ru`)

## Core Terms

| Source | Russian |
| --- | --- |
| Book | Книга |
| Account | Счёт |
| Transaction | Операция |
| Transaction Template | Шаблон операции |
| Template | Шаблон |
| Budget | Бюджет |
| Balance Sheet | Балансовый отчёт |
| Balance | Баланс |

## Direction Terms

| Source | Russian |
| --- | --- |
| Source | Источник |
| Destination | Назначение |
| Amount Out | Сумма списания |
| Amount In | Сумма зачисления |

## Account Types

| Source | Russian |
| --- | --- |
| Asset | Актив |
| Expense | Расход |
| Income | Доход |
| Liability | Обязательство |
| Other | Другое |

## Time and Range Terms

### Until

Use `До даты` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Do not use a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `По сегодняшний день` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | ru |
| --- | --- |
| Mode label | До даты |
| Quick View label | По сегодняшний день |
| Range display | До {{date}} |
| Current-date label | По сегодняшний день |

## Feature Terms

| Source | Russian |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | Быстрый просмотр |
| Distribution Chart | Диаграмма распределения финансов |
| Trend Chart | Диаграмма финансовой динамики |
| Trash | Корзина |
| Schedule | Расписание |
| Preferences | Настройки |
| License | Лицензия |
| Backup | Резервная копия |
| Restore | Восстановление |
| Import | Импорт |
| Export | Экспорт |

### Quick View

Use `Быстрый просмотр` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Russian locale JSON.

### Financial Distribution Chart

Use `Диаграмма распределения финансов` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | ru |
| --- | --- |
| Documentation | Диаграмма распределения финансов |
| No-period UI | Распределение финансов |
| Weekly UI | Недельное распределение |
| Monthly UI | Месячное распределение |
| Month-end UI | Распределение: конец месяца |
| Annual UI | Годовое распределение |
| Quick View UI | Быстрый просмотр: распределение |
| Home tab | Распределение |

### Financial Trend Chart

Use `Диаграмма финансовой динамики` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | ru |
| --- | --- |
| Documentation | Диаграмма финансовой динамики |
| No-mode UI | Финансовая динамика |
| LINE mode | Динамика |
| CUMULATIVE mode | Накопительная динамика |
| Quick View UI | Быстрый просмотр: динамика |
| Home tab | Динамика |

## Reconciliation Terms

| Term | ru |
| --- | --- |
| Reconciled | Сверено |
| Unreconciled | Не сверено |
| Reconciliation | Статус сверки |
| Reconciliation Status | Статус сверки |
| Reconciliation Mode | Режим сверки |

Use `Сверено` and `Не сверено` for transaction reconciliation status labels.
Use `Статус сверки` for search filters or settings that refer to the reconciliation status as a field.
Use `Режим сверки` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Source | Russian |
| --- | --- |
| Home Screen | Главный экран |
| Home | Главная |
| Help | Помощь |
| What's New | Что нового |
| Release Notes | История версий |
| Credits | Благодарности |
| Device Info | Устройство |
| Data Maintenance | Обслуживание данных |

## Style Rules

- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `Книга` for `Book`.
- Use `Счёт` for accounting `Account`.
- Use `Операция` for `Transaction`.
- Use `Шаблон операции` for `Transaction Template`.
- Use `Источник` for `Source` and withdrawal-side concepts.
- Use `Назначение` for `Destination` and deposit-side concepts.
- Use `Сумма списания` for `Amount Out`.
- Use `Сумма зачисления` for `Amount In`.
- Use `Балансовый отчёт` for `Balance Sheet`.
- Use `Баланс` for `Balance`.
- Use short, natural Russian UI labels. Prefer concise nouns for tabs, filters, buttons, and chart labels.
- Translate product-specific accounting terms by Daily Money One meaning, not by generic banking, trading, or login/account wording.
