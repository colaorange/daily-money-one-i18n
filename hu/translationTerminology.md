# Translation Terminology

This file contains locale-specific terminology and style rules for Hungarian (`hu`).

## Core Terms

| Term | hu |
| --- | --- |
| Book | Könyv |
| Account | Számla |
| Transaction | Tranzakció |
| Transaction Template | Tranzakciósablon |
| Template | Sablon |
| Budget | Költségkeret |
| Balance Sheet | Egyenlegkimutatás |
| Balance | Egyenleg |

Use `Sablon` when the UI context is already under transactions. Use `Tranzakciósablon` when the context is ambiguous.

## Direction Terms

| Term | hu |
| --- | --- |
| Source | Forrás |
| Destination | Cél |
| Withdrawal | Forrás |
| Deposit | Cél |
| Amount Out | Kimenő összeg |
| Amount In | Bejövő összeg |

Use `kiutalás` and `beutalás` only as explanatory wording when the source needs to clarify the direction, for example `Forrás (kiutalás)` and `Cél (beutalás)`.

## Account Types

| Term | hu |
| --- | --- |
| Asset | Eszköz |
| Expense | Kiadás |
| Income | Bevétel |
| Liability | Kötelezettség |
| Other | Egyéb |

## Time and Range Terms

### Until

Use `Eddig` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Use the terminative suffix `-ig` with the displayed date. Do not use a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `Máig` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | hu |
| --- | --- |
| Mode label | Eddig |
| Quick View label | Máig |
| Range display | {{date}}-ig |
| Current-date label | Máig |

## Feature Terms

| Term | hu |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | Gyorsnézet |
| Chart | Diagram |
| Distribution Chart | Pénzügyi eloszlási diagram |
| Trend Chart | Pénzügyi trenddiagram |
| Trash | Kuka |
| Schedule | Ütemezés |
| Preferences | Beállítások |
| License | Licenc |
| Backup | Mentés |
| Restore | Visszaállítás |
| Import | Importálás |
| Export | Exportálás |

### Quick View

Use `Gyorsnézet` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Hungarian locale JSON.

### Financial Distribution Chart

Use `Pénzügyi eloszlási diagram` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | hu |
| --- | --- |
| Documentation | Pénzügyi eloszlási diagram |
| No-period UI | Pénzügyi eloszlás |
| Weekly UI | Heti eloszlás |
| Monthly UI | Havi eloszlás |
| Month-end UI | Hó végi eloszlás |
| Annual UI | Éves eloszlás |
| Quick View UI | Pénzügyi eloszlás gyorsnézete |
| Home tab | Eloszlás |

### Financial Trend Chart

Use `Pénzügyi trenddiagram` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | hu |
| --- | --- |
| Documentation | Pénzügyi trenddiagram |
| No-mode UI | Pénzügyi trend |
| LINE mode | Trend |
| CUMULATIVE mode | Összesített trend |
| Quick View UI | Trend gyorsnézete |
| Home tab | Trendek |

## Reconciliation Terms

| Term | hu |
| --- | --- |
| Reconciled | Egyeztetett |
| Unreconciled | Nem egyeztetett |
| Reconciliation | Egyeztetési állapot |
| Reconciliation Status | Egyeztetési állapot |
| Reconciliation Mode | Egyeztetési mód |

Use `Egyeztetett` and `Nem egyeztetett` for transaction reconciliation status labels.
Use `Egyeztetési állapot` for search filters or settings that refer to the reconciliation status as a field.
Use `Egyeztetési mód` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Term | hu |
| --- | --- |
| Home Screen | Kezdőképernyő |
| Home | Kezdőlap |
| About | Névjegy |
| Help | Súgó |
| UI | Felület |
| What's New | Újdonságok |
| Release Notes | Kiadási megjegyzések |
| Credits | Köszönetnyilvánítás |
| Third-Party Licenses | Harmadik felek licencei |
| Device Info | Eszközinformáció |
| Platform | Platform |
| EULA | EULA |
| Ads Consent | Reklámhozzájárulás |
| Accounts | Számlák |
| Books | Könyvek |
| Budgets | Költségkeretek |
| Transactions | Tranzakciók |
| Daily Transactions | Napi tranzakciók |
| Recent Updates | Legutóbbi frissítések |
| Search | Keresés |
| Results | Eredmények |
| Templates | Sablonok |
| Shortcuts | Kezdőlapi parancsikonok |
| Preferences | Beállítások |
| Display | Megjelenítés |
| Functions | Funkciók |
| Security | Biztonság |
| Language | Nyelv |
| Password | Jelszó |
| Clear Password | Jelszó törlése |
| Date & Time | Dátum és idő |
| Server Mode | Szerver mód |
| Data Maintenance | Adatkarbantartás |
| Auto Backup | Automatikus mentés |
| Import CSV | CSV importálása |
| Import JSON | JSON importálása |
| Google Drive Backups | Google Drive-mentések |

## Style Rules

- Use `en` as the primary source.
- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `Könyv` for `Book`.
- Use `Számla` for accounting `Account`.
- Use `felhasználói fiók`, `Google-fiók`, or `bejelentkezés` only when the source clearly refers to a login account, Google account, user account, authorization account, or credential account.
- Use `Tranzakció` for `Transaction`.
- Use `Tranzakciósablon` for `Transaction Template`.
- Use `Sablon` when the UI context is already under transactions.
- Use `Forrás` for `Source` or withdrawal-side concepts.
- Use `Cél` for `Destination` or deposit-side concepts.
- Use `Egyenlegkimutatás` for `Balance Sheet`.
- Use `Egyenleg` for the balance concept in shorter UI labels.
- Use `Költségkeret` for `Budget`.
- Keep UI labels short and consistent. Prefer `Új tranzakció`, `Tranzakció szerkesztése`, `Tranzakciók` over longer explanatory wording.
