# API - Lista de Contatos

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

## 📄 Descrição

Este projeto é uma simples API para gerenciar uma lista de contatos. Ele foi desenvolvido como parte dos meus primeiros passos nos estudos de **Node.js** e **TypeScript** no curso da **B7 Web**.

A aplicação permite criar, listar e deletar contatos, que são armazenados de forma persistente em um arquivo de texto (`.txt`). O objetivo principal foi praticar a criação de um servidor, o roteamento de requisições e a manipulação de arquivos de forma assíncrona.

## ✨ Funcionalidades

-   **Listar contatos**: Retorna todos os contatos salvos.
-   **Criar um novo contato**: Adiciona um novo nome à lista.
-   **Deletar um contato**: Remove um contato existente da lista pelo nome.

## 🚀 Tecnologias Utilizadas

-   **Node.js**: Ambiente de execução do JavaScript no servidor.
-   **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
-   **Express**: Framework para criação do servidor e gerenciamento de rotas.
-   **Helmet**: Middleware para adicionar uma camada de segurança básica à API.
-   **ts-node-dev** (ou similar): Para rodar o ambiente de desenvolvimento em TypeScript com live reload.

## 📋 Endpoints da API

Abaixo estão os endpoints disponíveis na aplicação:

| Método HTTP | Rota        | Descrição                    | Corpo (Body) / Query   |
| :---------- | :---------- | :--------------------------- | :--------------------- |
| `GET`       | `/contatos` | Lista todos os contatos.     | N/A                    |
| `POST`      | `/contato`  | Cria um novo contato.        | `{ "name": "string" }` |
| `DELETE`    | `/contato`  | Deleta um contato pelo nome. | `?name=string`         |

## 🏁 Como Executar o Projeto

Siga os passos abaixo para rodar o projeto em sua máquina local.

**Pré-requisitos:**

-   [Node.js](https://nodejs.org/en/) instalado.
-   Um gerenciador de pacotes como [NPM](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/).

```bash
# 1. Clone o repositório
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

# 2. Navegue até a pasta do projeto
cd seu-repositorio

# 3. Instale as dependências
npm install

# 4. Crie o arquivo de dados na pasta 'src/data'
# Crie a pasta /data e dentro dela um arquivo vazio chamado list.txt

# 5. Rode o servidor em modo de desenvolvimento
npm run dev

# O servidor estará rodando em http://localhost:3000
```
