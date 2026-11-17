# Portfólio Profissional — Phillipe Henry

![Status da CI](https://github.com/SEU-USUARIO/SEU-REPOSITORIO/actions/workflows/ci.yml/badge.svg)

Portfólio desenvolvido com HTML e CSS. O projeto utiliza GitHub Actions para validar o código em Pull Requests e publicar automaticamente no GitHub Pages após a integração na branch `main`.

## Tecnologias

- HTML5 e CSS3
- Git e GitHub
- GitHub Actions (CI/CD)
- HTMLHint, Stylelint e Linkinator

## Executar localmente

1. Instale o Node.js (versão 18 ou 20).
2. No terminal, execute `npm install`.
3. Abra `index.html` no navegador ou utilize a extensão Live Server do VS Code.

## Antes de entregar

- [ ] Trocar `SEU-USUARIO` e `SEU-REPOSITORIO` no badge.
- [ ] Atualizar os links do GitHub e LinkedIn para seus perfis.
- [ ] Substituir o endereço de e-mail de exemplo.
- [ ] Conferir nome, textos e projetos para refletirem sua experiência real.
- [ ] Configurar GitHub Pages para usar GitHub Actions.
- [ ] Criar a regra de proteção da branch `main`.
- [ ] Adicionar `09116428-collab` como colaborador.

## Workflows

- `ci.yml`: executa as verificações em Pull Requests para `main`, usando Node.js 18 e 20.
- `deploy.yml`: publica no GitHub Pages quando há push na branch `main`.

## Notificação de falha

O workflow de deploy possui uma etapa opcional de notificação por Discord. Para ativá-la, crie um webhook no Discord e cadastre a URL no repositório em **Settings → Secrets and variables → Actions**, com o nome `DISCORD_WEBHOOK_URL`.
