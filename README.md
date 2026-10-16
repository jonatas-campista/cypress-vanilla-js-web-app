# Testes E2E com Cypress — app de cadastro de imagens

![Cypress](https://img.shields.io/badge/Cypress-17202C?logo=cypress&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Automação dos cenários BDD de uma aplicação em JavaScript puro que cadastra imagens (título + URL) e as
guarda no `localStorage`.

## O que foi feito

- Implementação dos cenários escritos em Gherkin no arquivo [`app.feature`](app.feature).
- **Page Object** (`RegisterForm`) com os seletores e ações do formulário.
- Validação de mensagens de erro, ícones de validação e cor da borda dos campos inválidos.
- Limpeza do `localStorage` após os testes, para manter o isolamento.

## Como rodar

```bash
npm ci
npm start          # sobe a aplicação localmente
npx cypress open   # em outro terminal
```

## Créditos

Fork do [vanilla-js-web-app-example](https://github.com/ErickWendel/vanilla-js-web-app-example),
de Erick Wendel. A aplicação é do autor original; os testes em `cypress/e2e/` foram escritos por mim.
