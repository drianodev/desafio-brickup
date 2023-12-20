# Desafio Brickup

Este é um repositório principal que contém os submódulos para os projetos `task-manager` e `task-api`.

## Clonando o Repositório

Certifique-se de incluir a opção `--recursive` ao clonar para garantir que os submódulos também sejam clonados:

```bash
git clone --recursive https://github.com/drianodev/desafio-brickup.git
```

Se você já clonou o repositório e precisa dos submódulos:

```bash
git submodule update --init --recursive
```

## Projetos Inclusos

### Task Manager

- [Repositório Task Manager](https://github.com/drianodev/task-manager)

**Descrição:** Frontend do projeto Task Manager, desenvolvido como parte do desafio da Brickup. Este aplicativo é um gerenciador de tarefas que se comunica com o backend para realizar operações como listar tarefas, criar, atualizar e excluir tarefas.

### Task API

- [Repositório Task API](https://github.com/drianodev/task-api)

**Descrição:** Backend do projeto Task Manager desenvolvido como parte do desafio da Brickup. O aplicativo consiste em um gerenciador de tarefas, com funcionalidades para listar todas as tarefas, obter detalhes de uma tarefa específica, criar, atualizar e excluir tarefas.
