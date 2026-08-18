# Contribuindo

## Fluxo de trabalho

1. Crie uma branch a partir de `main`: `feature/<descrição>`, `fix/<descrição>` ou `chore/<descrição>`.
2. Abra um Pull Request usando o template padrão.
3. Pelo menos 1 aprovação antes do merge em `main`.
4. CI (lint + testes) precisa passar antes do merge.
5. Use squash merge para manter o histórico limpo.

## Commits

Prefira mensagens no formato `tipo: descrição curta` (ex: `fix: corrige timeout na integração com ERP`).
Tipos comuns: `feat`, `fix`, `chore`, `docs`, `refactor`, `test`.

## Credenciais e dados de cliente

- Nunca commitar credenciais, tokens, chaves de API ou dados de cliente no código.
- Use variáveis de ambiente / secrets do GitHub Actions para qualquer credencial.
- Veja [SECURITY.md](SECURITY.md) para reportar problemas de segurança.

## Nomenclatura de repositórios

Veja [NAMING.md](NAMING.md).
