# Translation Terminology

This file contains locale-specific terminology and style rules for Dutch (`nl`).

## Core Terms

| Term | nl |
| --- | --- |
| Book | Boek |
| Account | Rekening |
| Transaction | Transactie |
| Transaction Template | Transactiesjabloon |
| Template | Sjabloon |
| Budget | Budget |
| Balance Sheet | Balansoverzicht |
| Balance | Saldo |

Use `Sjabloon` when the UI context is already under transactions. Use `Transactiesjabloon` when the context is ambiguous.

## Direction Terms

| Term | nl |
| --- | --- |
| Source | Bron |
| Destination | Bestemming |
| Withdrawal | Bron |
| Deposit | Bestemming |
| Amount Out | Bedrag uit |
| Amount In | Bedrag in |

Use `uitgaand` and `inkomend` only as explanatory wording when the source needs to clarify the direction, for example `Bron (uitgaand)` and `Bestemming (inkomend)`.

## Account Types

| Term | nl |
| --- | --- |
| Asset | Activa |
| Expense | Uitgave |
| Income | Inkomen |
| Liability | Schuld |
| Other | Overig |

## Feature Terms

| Term | nl |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | Snelle weergave |
| Chart | Diagram |
| Distribution Chart | Financieel verdelingsdiagram |
| Trend Chart | Financieel trenddiagram |
| Trash | Prullenbak |
| Schedule | Planning |
| Preferences | Voorkeuren |
| License | Licentie |
| Backup | Back-up |
| Restore | Herstellen |
| Import | Importeren |
| Export | Exporteren |

### Quick View

Use `Snelle weergave` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Dutch locale JSON.

### Financial Distribution Chart

Use `Financieel verdelingsdiagram` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | nl |
| --- | --- |
| Documentation | Financieel verdelingsdiagram |
| No-period UI | Financiële verdeling |
| Weekly UI | Wekelijkse verdeling |
| Monthly UI | Maandelijkse verdeling |
| Month-end UI | Maandeindverdeling |
| Annual UI | Jaarlijkse verdeling |
| Quick View UI | Snelle weergave: verdeling |
| Home tab | Verdeling |

### Financial Trend Chart

Use `Financieel trenddiagram` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | nl |
| --- | --- |
| Documentation | Financieel trenddiagram |
| No-mode UI | Financiële trend |
| LINE mode | Trend |
| CUMULATIVE mode | Cumulatieve trend |
| Quick View UI | Snelle weergave: trend |
| Home tab | Trends |

## Reconciliation Terms

| Term | nl |
| --- | --- |
| Reconciled | Afgestemd |
| Unreconciled | Niet afgestemd |
| Reconciliation | Afstemmingsstatus |
| Reconciliation Status | Afstemmingsstatus |
| Reconciliation Mode | Afstemmingsmodus |

Use `Afgestemd` and `Niet afgestemd` for transaction reconciliation status labels.
Use `Afstemmingsstatus` for search filters or settings that refer to the reconciliation status as a field.
Use `Afstemmingsmodus` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Term | nl |
| --- | --- |
| Home Screen | Startscherm |
| Home | Start |
| About | Over |
| Help | Help |
| UI | UI |
| What's New | Wat is nieuw |
| Release Notes | Releaseopmerkingen |
| Credits | Dankbetuigingen |
| Third-Party Licenses | Licenties van derden |
| Device Info | Apparaatinfo |
| Platform | Platform |
| EULA | EULA |
| Ads Consent | Advertentietoestemming |
| Accounts | Rekeningen |
| Books | Boeken |
| Budgets | Budgetten |
| Transactions | Transacties |
| Daily Transactions | Dagelijkse transacties |
| Recent Updates | Recente updates |
| Search | Zoeken |
| Results | Resultaten |
| Templates | Sjablonen |
| Shortcuts | Startschermsnelkoppelingen |
| Preferences | Voorkeuren |
| Display | Weergave |
| Functions | Functies |
| Security | Beveiliging |
| Language | Taal |
| Password | Wachtwoord |
| Clear Password | Wachtwoord wissen |
| Date & Time | Datum en tijd |
| Server Mode | Servermodus |
| Data Maintenance | Gegevensonderhoud |
| Auto Backup | Automatische back-up |
| Import CSV | CSV importeren |
| Import JSON | JSON importeren |
| Google Drive Backups | Google Drive-back-ups |

## Style Rules

- Use `en` as the primary source.
- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `Boek` for `Book`.
- Use `Rekening` for accounting `Account`.
- Use `gebruikersaccount`, `Google-account`, or `inloggen` only when the source clearly refers to a login account, Google account, user account, authorization account, or credential account.
- Use `Transactie` for `Transaction`.
- Use `Transactiesjabloon` for `Transaction Template`.
- Use `Sjabloon` when the UI context is already under transactions.
- Use `Bron` for `Source` or withdrawal-side concepts.
- Use `Bestemming` for `Destination` or deposit-side concepts.
- Use `Balansoverzicht` for `Balance Sheet`.
- Use `Saldo` for the balance concept in shorter UI labels.
- Use `Budget` for `Budget`.
- Keep UI labels short and consistent. Prefer `Nieuwe transactie`, `Transactie bewerken`, `Transacties` over longer explanatory wording.
