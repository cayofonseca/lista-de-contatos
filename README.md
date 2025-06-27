API - Lista de Contatos
📄 Descrição
Este projeto é uma simples API para gerenciar uma lista de contatos. Ele foi desenvolvido como parte dos meus primeiros passos nos estudos de Node.js e TypeScript no curso da B7 Web.

A aplicação permite criar, listar e deletar contatos, que são armazenados de forma persistente em um arquivo de texto (.txt). O objetivo principal foi praticar a criação de um servidor, o roteamento de requisições e a manipulação de arquivos de forma assíncrona.

✨ Funcionalidades
Listar contatos: Retorna todos os contatos salvos.

Criar um novo contato: Adiciona um novo nome à lista.

Deletar um contato: Remove um contato existente da lista pelo nome.

🚀 Tecnologias Utilizadas
Node.js: Ambiente de execução do JavaScript no servidor.

TypeScript: Superset do JavaScript que adiciona tipagem estática.

Express: Framework para criação do servidor e gerenciamento de rotas.

Helmet: Middleware para adicionar uma camada de segurança básica à API.

ts-node-dev (ou similar): Para rodar o ambiente de desenvolvimento em TypeScript com live reload.



🏁 Como Executar o Projeto
Siga os passos abaixo para rodar o projeto em sua máquina local.

Pré-requisitos:

Node.js instalado.

Um gerenciador de pacotes como NPM ou Yarn.



# 1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# 2. Navegue até a pasta do projeto
cd seu-repositorio

# 3. Instale as dependências
npm install

# 4. Crie o arquivo de dados na pasta 'src/data'
# Crie a pasta /data e dentro dela um arquivo vazio chamado list.txt

# 5. Rode o servidor em modo de desenvolvimento
npm run dev

# O servidor estará rodando em http://localhost:3000
Scripts Sugeridos para package.json:

JSON

"scripts": {
  "start": "node dist/server.js",
  "build": "tsc",
  "dev": "ts-node-dev --respawn --transpile-only src/server.ts"
}
🧠 O que foi Praticado
Este projeto serviu como uma excelente introdução aos seguintes conceitos:

Configuração de um projeto Node.js com TypeScript.

Criação de um servidor web utilizando o framework Express.

Definição e organização de rotas (GET, POST, DELETE).

Utilização de middlewares (como helmet e express.json).

Manipulação de requisições (req.body, req.query) e respostas (res.json, res.status).

Leitura e escrita de arquivos de forma assíncrona com o módulo fs/promises.

Estruturação básica de um projeto, separando responsabilidades (servidor, rotas, serviços).
