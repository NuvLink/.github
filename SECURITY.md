# Política de Segurança

A NuvLink lida com integrações de sistemas e automações que frequentemente envolvem dados e credenciais de clientes. Levamos segurança a sério.

## Reportando uma vulnerabilidade

Se você encontrar uma vulnerabilidade de segurança em qualquer repositório da NuvLink, **não abra uma issue pública**. Envie um e-mail para `NuvLinkCORP@gmail.com` (ajustar para o e-mail real da empresa) com:

- Descrição do problema e impacto potencial
- Passos para reproduzir
- Repositório e versão/commit afetado

Você receberá uma confirmação em até 2 dias úteis.

## Boas práticas exigidas nos repositórios

- Segredos e credenciais apenas via GitHub Actions Secrets ou variável de ambiente — nunca hardcoded.
- Dependabot/alertas de segurança habilitados em todos os repositórios.
- Repositórios de projetos de cliente são privados por padrão.
