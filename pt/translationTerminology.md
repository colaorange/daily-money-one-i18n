# Translation Terminology

This file contains locale-specific terminology and style rules for Portuguese (`pt`, European Portuguese / `pt-PT`).

## Core Terms

| Source | Portuguese |
| --- | --- |
| Book | Livro |
| Account | Conta |
| Transaction | Movimento |
| Transaction Template | Modelo de movimento |
| Template | Modelo |
| Budget | Orçamento |
| Balance Sheet | Balanço |
| Balance | Saldo |

## Direction Terms

| Source | Portuguese |
| --- | --- |
| Source | Origem |
| Destination | Destino |
| Amount Out | Montante de saída |
| Amount In | Montante de entrada |

## Account Types

| Source | Portuguese |
| --- | --- |
| Asset | Ativo |
| Expense | Despesa |
| Income | Rendimento |
| Liability | Passivo |
| Other | Outro |

## Feature Terms

| Source | Portuguese |
| --- | --- |
| Daily Money One | Daily Money One |
| Daily Money | Daily Money |
| Quick View | Vista rápida |
| Distribution Chart | Gráfico de distribuição financeira |
| Trend Chart | Gráfico de tendência financeira |
| Trash | Lixo |
| Schedule | Agenda |
| Preferences | Preferências |
| License | Licença |
| Backup | Cópia de segurança |
| Restore | Restaurar |
| Import | Importar |
| Export | Exportar |

### Quick View

Use `Vista rápida` for the saved, continuously updated result placed on the Home Screen for direct viewing without repeating the UI operations that originally produced it.

Do not use a term meaning summary, preview, static snapshot, navigation shortcut, favorite, or operating-system widget. Record any future replacement here before changing European Portuguese locale JSON.

### Financial Distribution Chart

Use `Gráfico de distribuição financeira` in Markdown documentation. In compact locale JSON UI labels, omit the words corresponding to `Financial` and `Chart` when a period appears first.

| Context | pt |
| --- | --- |
| Documentation | Gráfico de distribuição financeira |
| No-period UI | Distribuição financeira |
| Weekly UI | Distribuição semanal |
| Monthly UI | Distribuição mensal |
| Month-end UI | Distribuição fim do mês |
| Annual UI | Distribuição anual |
| Quick View UI | Vista rápida: distribuição |
| Home tab | Distribuição |

### Financial Trend Chart

Use `Gráfico de tendência financeira` in Markdown documentation and long-form prose. Use the approved shorter labels for compact UI contexts.

| Context | pt |
| --- | --- |
| Documentation | Gráfico de tendência financeira |
| No-mode UI | Tendência financeira |
| LINE mode | Tendência |
| CUMULATIVE mode | Tendência acumulada |
| Quick View UI | Vista rápida: tendências |
| Home tab | Tendências |

## Reconciliation Terms

| Term | pt |
| --- | --- |
| Reconciled | Reconciliado |
| Unreconciled | Não reconciliado |
| Reconciliation | Estado de reconciliação |
| Reconciliation Status | Estado de reconciliação |
| Reconciliation Mode | Modo de reconciliação |

Use `Reconciliado` and `Não reconciliado` for transaction reconciliation status labels.
Use `Estado de reconciliação` for search filters or settings that refer to the reconciliation status as a field.
Use `Modo de reconciliação` for the transaction list mode used to mark transactions as reconciled or unreconciled.

## UI Terms

| Source | Portuguese |
| --- | --- |
| Home Screen | Ecrã inicial |
| Home | Início |
| Help | Ajuda |
| What's New | Novidades |
| Release Notes | Notas de versão |
| Credits | Agradecimentos |
| Device Info | Info. do dispositivo |
| Data Maintenance | Manutenção de dados |

## Style Rules

- Use `en` as the primary source.
- Translate `pt` as European Portuguese (pt-PT), while keeping the locale code and file names as `pt`.
- Keep `Daily Money One` and `Daily Money` untranslated.
- Use `Livro` for `Book`.
- Use `Conta` for accounting `Account`.
- Use `conta de utilizador`, `conta Google`, or `iniciar sessão` only when the source clearly refers to a login account, Google account, user account, authorization account, or credential account.
- Use `Movimento` for `Transaction`.
- Use `Modelo de movimento` for `Transaction Template`.
- Use `Modelo` when the UI context is already under transactions.
- Use `Origem` for `Source` or withdrawal-side concepts.
- Use `Destino` for `Destination` or deposit-side concepts.
- Use `Balanço` for `Balance Sheet`.
- Use `Saldo` for the balance concept in shorter UI labels.
- Use `Orçamento` for `Budget`.
- Use European Portuguese wording and orthography: prefer `utilizador`, `ecrã`, `ficheiro`, `telemóvel`, `cópia de segurança`, `aplicação`, and `iniciar sessão`.
- Keep UI labels short and consistent. Prefer `Novo movimento`, `Editar movimento`, `Movimentos` over longer explanatory wording.
