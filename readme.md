# Teste ponta a ponta com Cypress

Projeto de exemplo para demonstrar testes ponta a ponta (e2e) escritos com [Cypress](https://cypress.io) em execução no GitHub Actions.

## Pré requisitos

Para clonar e executar este projeto, você precisará de:

- [git](https://git-scm.com/downloads) (usei a versão `2.34.1` enquanto escrevia este documento)
- [Node.js](https://nodejs.org/en/) (usei a versão `v18.15.0` ao escrever este documento)
- npm (usei a versão `9.5.0` ao escrever este documento)

**Observação:** Ao instalar o Node.js, o npm é instalado automaticamente. 🚀

## Instalação

Para instalar as dependências de desenvolvimento, execute `npm install` (ou `npm i` para abreviar).

## Configurando as variáveis ​​de ambiente

Antes de executar os testes, algumas variáveis ​​de ambiente precisam ser configuradas.

Faça uma cópia do arquivo [`cypress.env.example.json`](./cypress.env.example.json) como `cypress.env.json` e defina os valores apropriados para todas as variáveis.

**Nota:** O arquivo `cypress.env.json` não é rastreado pelo git, pois está listado no arquivo `.gitignore`.

## Executando os testes

Neste projeto, você pode executar testes nos modos interativo e headless, tanto em viewports de desktop quanto de tablets.

### Modo Hedless

Execute `npm test` (ou `npm t` para abreviar) para executar todos os testes no modo headless usando uma janela de visualização de desktop.

Execute `npm run test:tablet` para executar os testes apropriados no modo headless usando uma janela de visualização de tablet.

### Modo interativo

Execute `npm run cy:open` para abrir o __Cypress App__ para executar testes em modo interativo usando uma janela de visualização de desktop.

Execute `npm run cy:open:tablet` para abrir o __Cypress App__ para executar testes em modo interativo usando uma janela de visualização de tablet.

___

Feito com ❤️ por [seu-nome-aqui](https://seu-site-ou-perfil-github-aqui).