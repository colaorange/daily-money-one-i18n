# Translation Terminology

This file contains locale-specific terminology and style rules for Thai (`th`).

## Core Terms

| Source | Thai |
| --- | --- |
| Book | สมุดบัญชี |
| Account | บัญชี |
| Transaction | รายการ |
| Transaction Template | แม่แบบรายการ |
| Template | แม่แบบ |
| Budget | งบประมาณ |
| Balance Sheet | งบดุล |
| Balance | ยอดคงเหลือ |

## Direction Terms

| Source | Thai |
| --- | --- |
| Source | ต้นทาง |
| Destination | ปลายทาง |
| Amount Out | จำนวนเงินออก |
| Amount In | จำนวนเงินเข้า |

## Account Types

| Source | Thai |
| --- | --- |
| Asset | สินทรัพย์ |
| Expense | ค่าใช้จ่าย |
| Income | รายรับ |
| Liability | หนี้สิน |
| Other | อื่นๆ |

## Feature Terms

| Source | Thai |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | มุมมองด่วน |
| Distribution Chart | แผนภูมิการกระจายทางการเงิน |
| Trend Chart | แผนภูมิแนวโน้มทางการเงิน |
| Trash | ถังขยะ |
| Schedule | กำหนดการ |
| Preferences | การตั้งค่า |
| License | ใบอนุญาต |
| Backup | สำรอง |
| Restore | กู้คืน |
| Import | นำเข้า |
| Export | ส่งออก |

### Quick View

Use `มุมมองด่วน` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Thai locale JSON.

### Financial Distribution Chart

Use `แผนภูมิการกระจายทางการเงิน` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | th |
| --- | --- |
| Documentation | แผนภูมิการกระจายทางการเงิน |
| No-period UI | การกระจายทางการเงิน |
| Weekly UI | การกระจายรายสัปดาห์ |
| Monthly UI | การกระจายรายเดือน |
| Month-end UI | การกระจายสิ้นเดือน |
| Annual UI | การกระจายรายปี |
| Quick View UI | มุมมองด่วนของการกระจายทางการเงิน |
| Home tab | การกระจาย |

### Financial Trend Chart

Use `แผนภูมิแนวโน้มทางการเงิน` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | th |
| --- | --- |
| Documentation | แผนภูมิแนวโน้มทางการเงิน |
| No-mode UI | แนวโน้มทางการเงิน |
| LINE mode | แนวโน้ม |
| CUMULATIVE mode | แนวโน้มสะสม |
| Quick View UI | มุมมองด่วนแนวโน้ม |
| Home tab | แนวโน้ม |

## Reconciliation Terms

| Term | th |
| --- | --- |
| Reconciled | กระทบยอดแล้ว |
| Unreconciled | ยังไม่กระทบยอด |
| Reconciliation | สถานะการกระทบยอด |
| Reconciliation Status | สถานะการกระทบยอด |
| Reconciliation Mode | โหมดกระทบยอด |

Use `กระทบยอดแล้ว` and `ยังไม่กระทบยอด` for transaction reconciliation status labels.
Use `สถานะการกระทบยอด` for search filters or settings that refer to the reconciliation status as a field.
Use `โหมดกระทบยอด` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Source | Thai |
| --- | --- |
| Home Screen | หน้าหลัก |
| Home | หน้าหลัก |
| Help | ความช่วยเหลือ |
| What's New | มีอะไรใหม่ |
| Release Notes | บันทึกประจำรุ่น |
| Credits | เครดิต |
| Device Info | ข้อมูลอุปกรณ์ |
| Data Maintenance | ดูแลข้อมูล |

## Style Rules

- Keep `Daily Money One` and `Daily Money` untranslated.
- Use natural, concise Thai for UI labels and avoid overly literal wording.
- Use `สมุดบัญชี` for `Book`.
- Use `บัญชี` for accounting `Account`; use login/user account wording only when the source clearly refers to identity, Google sign-in, credentials, or app users.
- Use `รายการ` for `Transaction`.
- Use `แม่แบบรายการ` for `Transaction Template`.
- Use `ต้นทาง` for `Source` or withdrawal-side concepts.
- Use `ปลายทาง` for `Destination` or deposit-side concepts.
- Use `งบดุล` when referring to the Balance Sheet screen or report.
- Use `ยอดคงเหลือ` when referring to the shorter balance concept.
- Keep UI labels short and consistent, such as `รายการ`, `บัญชี`, `สมุดบัญชี`, and `งบประมาณ`.
