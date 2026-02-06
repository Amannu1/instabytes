# **Instabytes – Back-end API**

Back-end de uma aplicação de rede social de compartilhamento de fotos, desenvolvido com Node.js e MongoDB.
O projeto expõe uma API REST responsável pelo gerenciamento de posts, upload de imagens, sistema de likes e integração com IA generativa para criação automática de descrições.

## 🎯 Objetivo do projeto

Construir uma API escalável e organizada para simular o funcionamento básico de uma rede social, aplicando conceitos essenciais de back-end como:

Arquitetura REST

Persistência de dados

Upload de arquivos

Integração com APIs externas

Separação de responsabilidades

## ⚙️ Funcionalidades

Criação e listagem de posts

Upload e armazenamento de imagens

Sistema de likes

Geração automática de descrições utilizando Google Gemini API

Comunicação via API REST para consumo por aplicações front-end

## 🛠️ Tecnologias e ferramentas

Node.js

Express

MongoDB

Mongoose

Google Gemini API

## 📋 Pré-requisitos

Para executar o projeto localmente, é necessário ter instalado:

Node.js

MongoDB (local ou em nuvem, como MongoDB Atlas)

## ▶️ Execução do projeto
1. Clone o repositório
git clone https://github.com/Amannu1/instabytes

2. Acesse o diretório do projeto
cd instabytes

3. Instale as dependências
npm install

4. Configure as variáveis de ambiente

Crie um arquivo .env na raiz do projeto com o seguinte conteúdo:

STRING_CONEXAO="mongodb+srv://usuario:senha@cluster.mongodb.net/nome-do-banco"
GEMINI_API_KEY="sua_chave_da_api_gemini"


STRING_CONEXAO: string de conexão com o MongoDB

GEMINI_API_KEY: chave de acesso à API do Google Gemini

5. Inicie o servidor
npm run dev


A aplicação será executada em modo de desenvolvimento.

## 🧠 Principais aprendizados

Desenvolvimento de APIs REST com Express

Modelagem de dados e persistência com MongoDB

Upload e manipulação de arquivos

Organização de código em camadas

Integração com inteligência artificial generativa

Uso de variáveis de ambiente para configuração segura

## 📌 Observações

Este projeto possui finalidade educacional, mas foi desenvolvido seguindo práticas que podem ser aplicadas em projetos reais, servindo como base para evolução e novas funcionalidades.
