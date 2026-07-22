# Translation Terminology

This file contains locale-specific terminology and style rules for Turkish (`tr`).

## Core Terms

| Source | Turkish |
| --- | --- |
| Book | Defter |
| Account | Hesap |
| Transaction | İşlem |
| Transaction Template | İşlem Şablonu |
| Template | Şablon |
| Budget | Bütçe |
| Balance Sheet | Bilanço |
| Balance | Bakiye |

## Direction Terms

| Source | Turkish |
| --- | --- |
| Source | Kaynak |
| Destination | Hedef |
| Amount Out | Çıkan Tutar |
| Amount In | Giren Tutar |

## Account Types

| Source | Turkish |
| --- | --- |
| Asset | Varlık |
| Expense | Gider |
| Income | Gelir |
| Liability | Borç |
| Other | Diğer |

## Time and Range Terms

### Until

Use `Tarihe kadar` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Do not use a deictic expression without a clear date reference or a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `Bugüne kadar` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | tr |
| --- | --- |
| Mode label | Tarihe kadar |
| Quick View label | Bugüne kadar |
| Range display | {{date}} tarihine kadar |
| Current-date label | Bugüne kadar |

## Feature Terms

| Source | Turkish |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | Hızlı Görünüm |
| Distribution Chart | Finansal dağılım grafiği |
| Trend Chart | Finansal eğilim grafiği |
| Trash | Çöp Kutusu |
| Schedule | Zamanlama |
| Preferences | Tercihler |
| License | Lisans |
| Backup | Yedekleme |
| Restore | Geri Yükleme |
| Import | İçe Aktar |
| Export | Dışa Aktar |

### Quick View

Use `Hızlı Görünüm` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Turkish locale JSON.

### Financial Distribution Chart

Use `Finansal dağılım grafiği` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | tr |
| --- | --- |
| Documentation | Finansal dağılım grafiği |
| No-period UI | Finansal dağılım |
| Weekly UI | Haftalık dağılım |
| Monthly UI | Aylık dağılım |
| Month-end UI | Ay sonu dağılım |
| Annual UI | Yıllık dağılım |
| Quick View UI | Finansal dağılım hızlı görünümü |
| Home tab | Dağılım |

### Financial Trend Chart

Use `Finansal eğilim grafiği` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | tr |
| --- | --- |
| Documentation | Finansal eğilim grafiği |
| No-mode UI | Finansal eğilim |
| LINE mode | Eğilim |
| CUMULATIVE mode | Kümülatif eğilim |
| Quick View UI | Eğilim hızlı görünümü |
| Home tab | Eğilim |

## Reconciliation Terms

| Term | tr |
| --- | --- |
| Reconciled | Mutabık |
| Unreconciled | Mutabık olmayan |
| Reconciliation | Mutabakat durumu |
| Reconciliation Status | Mutabakat durumu |
| Reconciliation Mode | Mutabakat Modu |

Use `Mutabık` and `Mutabık olmayan` for transaction reconciliation status labels.
Use `Mutabakat durumu` for search filters or settings that refer to the reconciliation status as a field.
Use `Mutabakat Modu` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Source | Turkish |
| --- | --- |
| Home Screen | Ana Ekran |
| Home | Ana Sayfa |
| Help | Yardım |
| What's New | Yenilikler |
| Release Notes | Sürüm Notları |
| Credits | Katkıda Bulunanlar |
| Device Info | Cihaz Bilgileri |
| Data Maintenance | Veri Bakımı |

## Style Rules

- Keep `Daily Money One` and `Daily Money` untranslated.
- Use natural Turkish UI wording with short labels where possible.
- Use sentence case for Turkish UI text unless the source is a proper noun or product name.
- Use `Hesap` for accounting accounts inside a book.
- Use `kullanıcı hesabı`, `Google hesabı`, or another identity-specific wording only when the source clearly refers to login or user identity.
- Use `İşlem` for app transaction records, not commercial trade wording.
- Use `Kaynak` and `Hedef` for the two sides of a transaction.
