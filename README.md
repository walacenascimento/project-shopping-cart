# Projeto Shopping-Cart
  `Olá, seja bem vindo(a) ao projeto Shopping-Cart!`

### DESCRIÇÃO:
* O objetivo desse projeto, foi a implementação totalmente dinâmica de um carrinho de compras de verdade. Para isso
consumimos dados da `API` do `Mercado Livre`.

---

### SUMÁRIO:
  - [Descrição](#descrição)
  - [Instruções](#instruções)
  - [Habilidades](#habilidades)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [Status](#status)
  - [Desempenho](#desempenho)
  - [Observações](#observações)
  - [Colaborador](#colaborador)
  - [Requisitos do projeto](#requisitos-do-projeto)

  ---

### INSTRUÇÕES:
1. Clone do repositório
    * Link para clonar o repositório:
```bash
    https://github.com/walacenascimento/project-shopping-cart
```

* Entrar na pasta do repositório:
```bash
    cd walacenascimento/project-shopping-cart
```
2. Instalar as dependências
```bash
    npm install
```
3. Para rodar o ESLint e Stylelint:
```bash
  npm run lint
  npm run lint:styles
```
3. Para rodar o Cypress:
Para executar os testes apenas no terminal:

```bash
npm test
```

Para executar os testes e vê-los rodando em uma janela de navegador:

```bash
npm run cypress:open
```
***ou***
```bash
npx cypress open
```

### HABILIDADES:
* O objetivo do projeto, era desmonstrar de forma prática as habilidades adiquiridas no módulo de `Introdução a Front-End`. Nesse módulo, fomos habilitados a `iniciar um projeto do zero`, `configurar pastas`, `utilizar o controle de versionamento com o Git`, `instalar bibliotecas externas`, `utlizar o NPM, NPX e NPM Scripts`, assim como a utilização do `CSS`. Outra habilidades adiquirido e aplicada nesse projeto foi as operações `assícronas`, a utilização de `Promises` para as tratativas com códigos assícronos e a função `fetch` para efetuar as requisições externas.

### TECNOLOGIAS UTILIZADAS:
1. `JavaScript`
2. `HTML`
3. `CSS`
4. `ESLint e Stylelint`
    * O ESLint e Stylelint, são usados para garantir a qualidade do código e a sua configuração foi feita pela <a href="https://betrybe.com">**TRYBE**</a>

2. `Cypress`
    * O Cypress é uma ferramenta de teste de front-end desenvolvida para a web.
    *  A configuração do `Cypress` foi feita pela <a href="https://betrybe.com">**TRYBE**</a> para avaliar o desenvolvimento dos requisitos.

### STATUS:
* Finalizado `APROVADO`

### DESEMPENHO
* `100%`

### COLABORADOR:
* Colaborador(es,as)
    * Este projeto foi desenvolvido individualmente por mim, `Walace Nascimento`
    * Nesse projeto, eu implementei as funções que constam no arquivo `script.js`.
    * A chamada para a `API`, foi implementada pela `Trybe`. 

### OBSERVAÇÕES:
* Todos os arquivos desse projeto foram fornecidos pela <a href="https://betrybe.com">**TRYBE**</a>
* Todos os arquivos de teste desse projeto foram fornecidos e implementados pela <a href="https://betrybe.com">**TRYBE**</a> 


### REQUISITOS DO PROJETO:

- [X] 1. Crie uma listagem de produtos.
    * Você deve criar uma listagem de produtos que devem ser consultados através da API do Mercado Livre.

- [x] 2. Adicione o produto ao carrinho de compras
  * Cada produto na página HTML possui um botão com o nome Adicionar ao carrinho!.
  * Ao clicar nesse botão você deve realizar uma requisição para o endpoint:
```javascript
  "https://api.mercadolibre.com/items/$ItemID"
```

- [x] 3. Remova o item do carrinho de compras ao clicar nele.
  * Ao clicar no **produto no carrinho de compra**, ele deve ser removido da lista.

- [x] 4.Carregue o carrinho de compras através do **LocalStorage** ao iniciar a página.
  * Ao carregar a página, o estado atual do carrinho de compras deve ser carregado do **LocalStorage**.

- [x] 5.Some o valor total dos itens do carrinho de compras.
  * Cada vez que se adicionar um item ao carrinho de compras, será necessário somar seus valores e apresentá-los na página principal do projeto.

- [x] 6. Crie um botão para limpar carrinho de compras.
  * Crie um botão para remover todos os itens do carrinho de compras.

- [x] 7. Adicione um texto de "loading" durante uma requisição à API
  * Uma requisição à API gasta um tempo e durante ele, ficamos sem saber se está tudo certo ou se algo deu errado.
Normalmente é utilizada alguma forma para mostrar que a requisição está em andamento.
Mostre a palavra "loading..." em algum lugar da página **apenas durante** a requisição à API.

---
