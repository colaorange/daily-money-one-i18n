# Translation Terminology

This file contains locale-specific terminology and style rules for Italian (`it`).

## Core Terms

| Term | it |
| --- | --- |
| Book | Libro |
| Account | Conto |
| Transaction | Movimento |
| Transaction Template | Modello di movimento |
| Template | Modello |
| Budget | Budget |
| Balance Sheet | Stato patrimoniale |
| Balance | Saldo |

Use `Modello` when the UI context is already under transactions. Use `Modello di movimento` when the context is ambiguous.

## Direction Terms

| Term | it |
| --- | --- |
| Source | Origine |
| Destination | Destinazione |
| Withdrawal | Origine |
| Deposit | Destinazione |
| Source account | Conto origine |
| Destination account | Conto destinazione |
| Source Book | Libro origine |
| Destination Book | Libro dest. |
| Amount Out | Importo in uscita |
| Amount In | Importo in entrata |

Use `uscita` and `entrata` only as explanatory wording when the source needs to clarify the direction, for example `Origine (uscita)` and `Destinazione (entrata)`.

## Account Types

| Term | it |
| --- | --- |
| Asset | Attivo |
| Expense | Spesa |
| Income | Entrata |
| Liability | Passività |
| Other | Altro |

## Time and Range Terms

### Until

Use `Fino a` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Do not use a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `Fino a oggi` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | it |
| --- | --- |
| Mode label | Fino a |
| Quick View label | Fino a oggi |
| Range display | Fino al {{date}} |
| Current-date label | Fino a oggi |

## Feature Terms

| Term | it |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | Vista rapida |
| Chart | Grafico |
| Distribution Chart | Grafico di distribuzione finanziaria |
| Trend Chart | Grafico dell'andamento finanziario |
| Trash | Cestino |
| Schedule | Pianificazione |
| Preferences | Preferenze |
| License | Licenza |
| Backup | Backup |
| Restore | Ripristina |
| Import | Importa |
| Export | Esporta |

### Quick View

Use `Vista rapida` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Italian locale JSON.

### Financial Distribution Chart

Use `Grafico di distribuzione finanziaria` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | it |
| --- | --- |
| Documentation | Grafico di distribuzione finanziaria |
| No-period UI | Distribuzione finanziaria |
| Weekly UI | Distribuzione settimanale |
| Monthly UI | Distribuzione mensile |
| Month-end UI | Distribuzione fine mese |
| Annual UI | Distribuzione annuale |
| Quick View UI | Vista rapida: distribuzione |
| Home tab | Distribuzione |

### Financial Trend Chart

Use `Grafico dell'andamento finanziario` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | it |
| --- | --- |
| Documentation | Grafico dell'andamento finanziario |
| No-mode UI | Andamento finanziario |
| LINE mode | Andamento |
| CUMULATIVE mode | Andamento cumulativo |
| Quick View UI | Vista rapida: andamento |
| Home tab | Andamento |

## Reconciliation Terms

| Term | it |
| --- | --- |
| Reconciled | Riconciliato |
| Unreconciled | Non riconciliato |
| Reconciliation | Stato riconciliazione |
| Reconciliation Status | Stato riconciliazione |
| Reconciliation Mode | Modalità riconciliazione |

Use `Riconciliato` and `Non riconciliato` for transaction reconciliation status labels.
Use `Stato riconciliazione` for search filters or settings that refer to the reconciliation status as a field.
Use `Modalità riconciliazione` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Term | it |
| --- | --- |
| Home Screen | Schermata Home |
| Home | Home |
| About | Informazioni |
| Help | Aiuto |
| UI | UI |
| What's New | Novità |
| Release Notes | Note di rilascio |
| Credits | Ringraziamenti |
| Third-Party Licenses | Licenze di terze parti |
| Device Info | Info dispositivo |
| Platform | Piattaforma |
| EULA | EULA |
| Ads Consent | Consenso annunci |
| Accounts | Conti |
| Books | Libri |
| Budgets | Budget |
| Transactions | Movimenti |
| Daily Transactions | Movimenti giornalieri |
| Recent Updates | Aggiornamenti recenti |
| Search | Cerca |
| Results | Risultati |
| Templates | Modelli |
| Shortcuts | Scorciatoie Home |
| Preferences | Preferenze |
| Display | Visualizzazione |
| Functions | Funzioni |
| Security | Sicurezza |
| Language | Lingua |
| Password | Password |
| Clear Password | Cancella password |
| Date & Time | Data e ora |
| Server Mode | Modalità server |
| Data Maintenance | Manutenzione dati |
| Auto Backup | Backup automatico |
| Import CSV | Importa CSV |
| Import JSON | Importa JSON |
| Google Drive Backups | Backup Google Drive |

## Style Rules

- Use `en` as the primary source.
- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `Libro` for `Book`.
- Use `Conto` for accounting `Account`.
- Use `account`, `account Google`, or `accesso` only when the source clearly refers to a login account, Google account, user account, authorization account, or credential account.
- Use `Movimento` for `Transaction`.
- Use `Modello di movimento` for `Transaction Template`.
- Use `Modello` when the UI context is already under transactions.
- Use `Origine` for `Source` or withdrawal-side concepts.
- Use `Destinazione` for `Destination` or deposit-side concepts.
- Use `Stato patrimoniale` for `Balance Sheet`.
- Use `Saldo` for the balance concept in shorter UI labels.
- Keep UI labels short and consistent. Prefer `Nuovo movimento`, `Modifica movimento`, `Movimenti` over longer explanatory wording.
