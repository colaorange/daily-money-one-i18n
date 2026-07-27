# Translation Terminology

This file contains locale-specific terminology and style rules for Spanish (`es`).

## Core Terms

| Term | es |
| --- | --- |
| Book | Libro |
| Account | Cuenta |
| Transaction | Transacción |
| Transaction Template | Plantilla de transacción |
| Template | Plantilla |
| Budget | Presupuesto |
| Balance Sheet | Hoja de balance |
| Balance | Saldo |

Use `Plantilla` when the UI context is already under transactions. Use `Plantilla de transacción` when the context is ambiguous.

## Direction Terms

| Term | es |
| --- | --- |
| Source | Origen |
| Destination | Destino |
| Withdrawal | Origen |
| Deposit | Destino |
| Amount Out | Importe saliente |
| Amount In | Importe entrante |

Use `salida` and `entrada` only as explanatory wording when the source needs to clarify the direction, for example `Origen (salida)` and `Destino (entrada)`.

## Account Types

| Term | es |
| --- | --- |
| Asset | Activo |
| Expense | Gasto |
| Income | Ingreso |
| Liability | Deuda |
| Other | Otro |

## Time and Range Terms

### Until

Use `Hasta` for the cumulative time-range mode that includes initial entries and all transactions up to and including the end of the selected date. Do not use a term meaning custom period selection.

The `Until` Quick View always ends on the current date. Use `Hasta hoy` for `balance.quickView.until` even though the key name does not include `Today`.

| Context | es |
| --- | --- |
| Mode label | Hasta |
| Quick View label | Hasta hoy |
| Range display | Hasta {{date}} |
| Current-date label | Hasta hoy |

## Feature Terms

| Term | es |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | Vista rápida |
| Chart | Gráfico |
| Distribution Chart | Gráfico de distribución financiera |
| Trend Chart | Gráfico de tendencia financiera |
| Trash | Papelera |
| Schedule | Programación |
| Preferences | Preferencias |
| License | Licencia |
| Backup | Copia de seguridad |
| Restore | Restaurar |
| Import | Importar |
| Export | Exportar |

### Quick View

Use `Vista rápida` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing Spanish locale JSON.

### Financial Distribution Chart

Use `Gráfico de distribución financiera` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | es |
| --- | --- |
| Documentation | Gráfico de distribución financiera |
| No-period UI | Distribución financiera |
| Weekly UI | Distribución semanal |
| Monthly UI | Distribución mensual |
| Month-end UI | Distribución fin de mes |
| Annual UI | Distribución anual |
| Quick View UI | Vista rápida: distribución |
| Home tab | Distribución |

### Financial Trend Chart

Use `Gráfico de tendencia financiera` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | es |
| --- | --- |
| Documentation | Gráfico de tendencia financiera |
| No-mode UI | Tendencia financiera |
| LINE mode | Tendencia |
| CUMULATIVE mode | Tendencia acumulada |
| Quick View UI | Vista rápida: tendencias |
| Home tab | Tendencias |

## Reconciliation Terms

| Term | es |
| --- | --- |
| Reconciled | Conciliado |
| Unreconciled | Sin conciliar |
| Reconciliation | Estado de conciliación |
| Reconciliation Status | Estado de conciliación |
| Reconciliation Mode | Modo de conciliación |

Use `Conciliado` and `Sin conciliar` for transaction reconciliation status labels.
Use `Estado de conciliación` for search filters or settings that refer to the reconciliation status as a field.
Use `Modo de conciliación` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Term | es |
| --- | --- |
| Home Screen | Pantalla de inicio |
| Home | Inicio |
| About | Acerca de |
| Help | Ayuda |
| UI | Interfaz |
| What's New | Novedades |
| Release Notes | Notas de versión |
| Credits | Créditos |
| Third-Party Licenses | Licencias de terceros |
| Device Info | Información del dispositivo |
| Platform | Plataforma |
| EULA | EULA |
| Ads Consent | Consentimiento de anuncios |
| Accounts | Cuentas |
| Books | Libros |
| Budgets | Presupuestos |
| Transactions | Transacciones |
| Daily Transactions | Transacciones diarias |
| Recent Updates | Actualizaciones recientes |
| Search | Buscar |
| Results | Resultados |
| Templates | Plantillas |
| Shortcuts | Accesos de inicio |
| Preferences | Preferencias |
| Display | Visualización |
| Functions | Funciones |
| Security | Seguridad |
| Language | Idioma |
| Password | Contraseña |
| Clear Password | Borrar contraseña |
| Date & Time | Fecha y hora |
| Server Mode | Modo servidor |
| Data Maintenance | Mantenimiento de datos |
| Auto Backup | Copia automática |
| Import CSV | Importar CSV |
| Import JSON | Importar JSON |
| Google Drive Backups | Copias en Google Drive |

## Style Rules

- Use `en` as the primary source.
- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `Libro` for `Book`.
- Use `Cuenta` for accounting `Account`.
- Use `cuenta de usuario`, `cuenta de Google`, or `inicio de sesión` only when the source clearly refers to a login account, Google account, user account, authorization account, or credential account.
- Use `Transacción` for `Transaction`.
- Use `Plantilla de transacción` for `Transaction Template`.
- Use `Plantilla` when the UI context is already under transactions.
- Use `Origen` for `Source` or withdrawal-side concepts.
- Use `Destino` for `Destination` or deposit-side concepts.
- Use `Hoja de balance` for `Balance Sheet`.
- Use `Saldo` for the balance concept in shorter UI labels.
- Keep UI labels short and consistent. Prefer `Nueva transacción`, `Editar transacción`, `Transacciones` over longer explanatory wording.
