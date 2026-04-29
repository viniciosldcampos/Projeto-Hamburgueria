# 📦 API - Estrutura e Tecnologias

Este projeto consiste na construção de uma API utilizando Node.js com o framework Express, seguindo boas práticas de organização, segurança e padronização de código.

## 🚀 Tecnologias Utilizadas
Node.js — Ambiente de execução JavaScript no servidor  
Express — Framework para criação de APIs REST  
Biome.js — Padronização e formatação de código  

## 🏗️ Arquitetura

O projeto seguirá o padrão MVC (Model-View-Controller), garantindo melhor organização, manutenção e escalabilidade do código.

## 🐳 Docker

Será utilizado o Docker para gerenciar e isolar os ambientes dos bancos de dados, permitindo fácil configuração e portabilidade.
Para a montagem da API será usado o Node.JS e o Framework Express.

## 🗄️ Banco de Dados

A aplicação utilizará dois tipos de banco de dados:

### 🔹 Relacional:
- PostgreSQL
- MySQL (compatível com ORM utilizada)

### ORM:
Sequelize — Manipulação de dados relacionais

### 🔹 Não Relacional (NoSQL)
- MongoDB

### ODM:
Mongoose — Modelagem e manipulação de dados NoSQL

## 🔐 Segurança
✔️ Validação de Dados
Yup — Validação de entradas com foco em segurança e tipagem

✔️ Criptografia
bcrypt.js — Criptografia de senhas antes do armazenamento

✔️ Autenticação
JWT (JSON Web Token) — Sistema de autenticação para proteger rotas e garantir acesso seguro