# Teste ponta a ponta com Cypress

Projeto de exemplo do Curso de Cypress por Walmyr Filho para demonstrar testes ponta a ponta (e2e) escritos com [Cypress](https://cypress.io) em execução no GitHub Actions.

## Pré requisitos

Para clonar e executar este projeto, você precisará de:

- [git](https://git-scm.com/downloads) (versão `2.34.1` implementada no projeto)
- [Node.js](https://nodejs.org/en/) (versão `v18.15.0` implementada no projeto)
- npm (usei a versão `9.5.0` implementada no projeto)

**Observação:** Ao instalar o Node.js, o npm é instalado automaticamente. 🚀

## Instalação

Para instalar as dependências de desenvolvimento, execute `npm install` (ou `npm i` para abreviar).

## Configurando as variáveis ​​de ambiente

Antes de executar os testes, algumas variáveis ​​de ambiente precisam ser configuradas.

Faça uma cópia do arquivo [`cypress.env.example.json`](./cypress.env.example.json) como `cypress.env.json` e defina os valores apropriados para todas as variáveis.

**Nota:** O arquivo `cypress.env.json` não é rastreado pelo git, pois está listado no arquivo `.gitignore`.

## Executando os testes

Neste projeto, os testes pode ser executados nos modos headless e interativo, tanto em viewports de desktop quanto de tablets.

### Modo Hedless

Execute `npm test` (ou `npm t` para abreviar) para executar todos os testes no modo headless usando uma janela de visualização de desktop.

Execute `npm run test:tablet` para executar os testes apropriados no modo headless usando uma janela de visualização de tablet.

### Modo interativo

Execute `npm run cy:open` para abrir o __Cypress App__ para executar testes em modo interativo usando uma janela de visualização de desktop.

Execute `npm run cy:open:tablet` para abrir o __Cypress App__ para executar testes em modo interativo usando uma janela de visualização de tablet.

___

Feito com ❤️ por [Catarina Calori](https://github.com/cabcalori).