# Intro ao Vue-js: Construindo um app de todo-list do zero

## Setup

- Instalar o [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)

- Instalar o vue-cli

```
yarn global add @vue/cli
```

- Instalar o [vs-code](https://code.visualstudio.com/Download) e em seguida instalar o plugin [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

- Instalar o [vue.js dev-tools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd?hl=en) no chrome

# Vue.js Todo App

- Setup
- Criar um componente Todo-List
  - properties: conteudoNovaTartefa (string) e tarefas (array)
- Criar um input de texto que será usado para adicionar tarefas
  - v-model two way data bind na conteudoNovaTartefa
- Criar botão de adicionar
  - evento de click
  - adiciona uma nova tarefa no array de tarefas
- Exibir tarefas numa lista
  - v-for
- Marcar tarefas como "finalizadas"
  - manipulação da classe css do item de acordo com sua model
- Botão de remover tarefas
- Botão de remover todas
- Botão de finalizar todas
- Teste unitário "deve adicionar nova tarefa"

## Extra:

- Faca um fork do repositório
  - Crie novas funcionalidades (use sua criatividade :D)
  - Evolua a suite de testes unitários

## Documentações para estudo

- Guia oficial do Vue.js
  https://vuejs.org/v2/guide/
- Escrever componentes vue em estilo de classes
  https://class-component.vuejs.org/
- Documentação vue-test-utils
  https://vue-test-utils.vuejs.org/guides/#getting-started
- Jest
  https://jestjs.io/

## Comandos utéis

- Instalar os pacotes do npm

```
yarn install
```

- Compilar e rodar a aplicação em modo de desenvolvimento

```
yarn serve
```

- Rodar testes unitários

```
yarn test:unit
```
