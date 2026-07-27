# Translation Terminology

This file contains locale-specific terminology and style rules for Korean (`ko`).

## Core Terms

| Term | ko |
| --- | --- |
| Book | 장부 |
| Account | 계정 |
| Transaction | 거래 |
| Transaction Template | 거래 템플릿 |
| Template | 템플릿 |
| Budget | 예산 |
| Balance Sheet | 잔액표 |
| Balance | 잔액 |

Use `템플릿` when the UI context is already under transactions. Use `거래 템플릿` when the context is ambiguous.

## Direction Terms

| Term | ko |
| --- | --- |
| Source | 출금 |
| Destination | 입금 |
| Withdrawal | 출금 |
| Deposit | 입금 |
| Amount Out | 출금액 |
| Amount In | 입금액 |

Use `출금` and `입금` for the two sides of a transaction. Use `출금액` and `입금액` for the corresponding amounts.

## Account Types

| Term | ko |
| --- | --- |
| Asset | 자산 |
| Expense | 지출 |
| Income | 수입 |
| Liability | 부채 |
| Other | 기타 |

## Time and Range Terms

### Until

Use `지정일까지` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Do not use the bound particle `까지` by itself or a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `오늘까지` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | ko |
| --- | --- |
| Mode label | 지정일까지 |
| Quick View label | 오늘까지 |
| Range display | {{date}}까지 |
| Current-date label | 오늘까지 |

## Feature Terms

| Term | ko |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | 빠른 보기 |
| Chart | 차트 |
| Distribution Chart | 재무 분포 차트 |
| Trend Chart | 재무 추이 차트 |
| Trash | 휴지통 |
| Schedule | 일정 |
| Preferences | 환경설정 |
| License | 라이선스 |
| Backup | 백업 |
| Restore | 복원 |
| Import | 가져오기 |
| Export | 내보내기 |

### Quick View

Use `빠른 보기` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Korean locale JSON.

### Financial Distribution Chart

Use `재무 분포 차트` in Markdown documentation. In compact locale JSON UI labels, omit `재무` and `차트` when a period appears first.

| Context | ko |
| --- | --- |
| Documentation | 재무 분포 차트 |
| No-period UI | 재무 분포 |
| Weekly UI | 주별 분포 |
| Monthly UI | 월별 분포 |
| Month-end UI | 월말 분포 |
| Annual UI | 연간 분포 |
| Quick View UI | 재무 분포 빠른 보기 |
| Home tab | 재무 분포 |

### Financial Trend Chart

Use `재무 추이 차트` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | ko |
| --- | --- |
| Documentation | 재무 추이 차트 |
| No-mode UI | 재무 추이 |
| LINE mode | 추이 |
| CUMULATIVE mode | 누적 추이 |
| Quick View UI | 재무 추이 빠른 보기 |
| Home tab | 재무 추이 |

## Reconciliation Terms

| Term | ko |
| --- | --- |
| Reconciled | 확인됨 |
| Unreconciled | 확인되지 않음 |
| Reconciliation | 확인 상태 |
| Reconciliation Status | 확인 상태 |
| Reconciliation Mode | 확인 모드 |

Use `확인됨` and `확인되지 않음` for transaction reconciliation status labels.
Use `확인 상태` for search filters or settings that refer to the reconciliation status as a field.
Use `확인 모드` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Term | ko |
| --- | --- |
| Home Screen | 홈 화면 |
| Home | 홈 |
| About | 정보 |
| Help | 도움말 |
| UI | UI |
| What's New | 새로운 기능 |
| Release Notes | 릴리스 노트 |
| Credits | 감사의 말 |
| Third-Party Licenses | 서드파티 라이선스 |
| Device Info | 기기 정보 |
| Platform | 플랫폼 |
| EULA | EULA |
| Ads Consent | 광고 동의 |
| Accounts | 계정 |
| Books | 장부 |
| Budgets | 예산 |
| Transactions | 거래 |
| Daily Transactions | 일별 거래 |
| Recent Updates | 최근 업데이트 |
| Search | 검색 |
| Results | 결과 |
| Templates | 템플릿 |
| Shortcuts | 홈 바로가기 |
| Preferences | 환경설정 |
| Display | 표시 |
| Functions | 기능 |
| Security | 보안 |
| Language | 언어 |
| Password | 비밀번호 |
| Clear Password | 비밀번호 해제 |
| Date & Time | 날짜 및 시간 |
| Server Mode | 서버 모드 |
| Data Maintenance | 데이터 유지 관리 |
| Auto Backup | 자동 백업 |
| Import CSV | CSV 가져오기 |
| Import JSON | JSON 가져오기 |
| Google Drive Backups | Google Drive 백업 |

## Style Rules

- Use `en` as the primary source.
- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `장부` for `Book`.
- Use `계정` for accounting `Account`.
- Use `사용자 계정`, `Google 계정`, or `로그인` only when the source clearly refers to a login account, Google account, user account, authorization account, or credential account.
- Use `거래` for `Transaction`.
- Use `거래 템플릿` for `Transaction Template`.
- Use `템플릿` when the UI context is already under transactions.
- Use `출금` for `Source` or withdrawal-side concepts.
- Use `입금` for `Destination` or deposit-side concepts.
- Use `잔액표` for `Balance Sheet`.
- Use `잔액` for the balance concept in shorter UI labels.
- Use `예산` for `Budget`.
- Keep UI labels short and consistent. Prefer `새 거래`, `거래 편집`, `거래` over longer explanatory wording.
