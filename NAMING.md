# Convenção de nomes de repositórios — NuvLink

| Tipo | Padrão | Visibilidade | Exemplo |
|---|---|---|---|
| Projeto de cliente | `client-<cliente>-<sistema>` | Privado | `client-acme-erp-integration` |
| Automação interna reutilizável | `automation-<processo>` | Privado ou público | `automation-invoice-reconciliation` |
| Sistema/produto próprio | `system-<nome>` | Privado ou público | `system-billing-portal` |
| Template de projeto | `template-<stack>` | Público | `template-automation-python` |
| Ferramenta interna (CLI, libs) | `tool-<nome>` | Privado | `tool-client-onboarding-cli` |
| Documentação/config da org | `.github`, `docs-<tema>` | Público | `.github` |

## Regras rápidas

- Nomes em minúsculas, palavras separadas por hífen.
- Nome do cliente sempre em slug curto (sem espaços, sem dados sensíveis do contrato).
- Projeto de cliente é privado por padrão — só torna público com autorização explícita do cliente.
- Branch principal: `main`.
- Branches de trabalho: `feature/<descrição>`, `fix/<descrição>`, `chore/<descrição>`.
