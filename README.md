# 💻 Projeto: Imersão Back-End Alura com Google Gemini

Este projeto foi desenvolvido durante a **Imersão Back-End** da Alura, utilizando **Node.js**, **Express** e **MongoDB**, com integração ao Google Gemini. O foco principal é aplicar conceitos de desenvolvimento de APIs RESTful, manipulação de dados, integração com banco de dados NoSQL e upload de arquivos.

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-v18.16.0-green" alt="Node.js Badge" />
  <img src="https://img.shields.io/badge/Express-v4.18.2-blue" alt="Express Badge" />
  <img src="https://img.shields.io/badge/MongoDB-v6.x-brightgreen" alt="MongoDB Badge" />
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow" alt="Status Badge" />
</p>

---

## 🧰 Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript fora do navegador, projetado para criar aplicações escaláveis e de alta performance.
- **Express**: Framework web minimalista e flexível para Node.js, utilizado para criar servidores HTTP e APIs REST de forma eficiente.
- **MongoDB**: Banco de dados NoSQL orientado a documentos, ideal para trabalhar com grandes volumes de dados não estruturados.
- **Mongoose**: Biblioteca ODM (Object Data Modeling) para conectar e manipular dados no MongoDB de forma simples.
- **Multer**: Middleware para manipulação de uploads de arquivos.

---

## 🗂 Como Configurar o Projeto Localmente?

Siga os passos abaixo para clonar, instalar as dependências e executar o projeto:

```bash
# 1. Clonar o repositório
git clone https://github.com/RaferaX/Imersao-Alura-BackEnd.git

# 2. Entrar no diretório do projeto
cd Imersao-Alura-BackEnd

# 3. Instalar as dependências do projeto
npm install

# 4. Configurar variáveis de ambiente
# Crie um arquivo .env e configure suas variáveis, como o exemplo:
# MONGO_URI=sua_url_de_conexao_com_mongodb
# PORT=3000

# 5. Iniciar o servidor localmente
node server.js
