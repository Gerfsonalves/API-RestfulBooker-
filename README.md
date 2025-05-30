<h1>Projeto de Testes API - Restful Booker</h1>

<b>Este projeto realiza testes automatizados da API Restful Booker utilizando o Cypress.
O fluxo de testes implementado contempla todas as operações principais do CRUD:

🔒 Autenticação

📖 Consulta de livro

🆕 Criação de livro

✏️ Atualização total e parcial de livro

🗑️ Deleção de livro
<hr><h2>
📋 Estrutura dos testes</h2>
Os testes são divididos em etapas:
<br><br>
<ol>
<li>Gerar Token de autenticação (POST /auth)

<li>Consultar IDs de reservas (GET /booking)

<li>Criar um novo livro (POST /booking)

<li>Consultar um livro específico (GET /booking/:id)

<li>Atualizar totalmente um livro (PUT /booking/:id)

<li>Atualizar parcialmente um livro (PATCH /booking/:id)

<li>Deletar um livro (DELETE /booking/:id)
</ol>
<br>
O fluxo é dinâmico: o bookingId criado no teste é reutilizado nas próximas operações.
<hr>
<h2>📸 Exemplo de execução
Durante a execução, o Cypress realiza:</h2>

Verificação de status HTTP

Validação do corpo da resposta

Conferência dos dados manipulados
<hr>
<h2>⚙️ Integração Contínua (CI) com GitHub Actions</h2>

Este projeto possui integração contínua configurada utilizando GitHub Actions.

Sempre que houver um push ou pull request para a branch main, o GitHub Actions irá:

Fazer o checkout do repositório

Instalar o Node.js

Instalar as dependências do projeto

Executar todos os testes do Cypress automaticamente

- Assim garantimos que todo novo código enviado continue passando nos testes automaticamente! ✅

<hr>
<h2>✨ Desenvolvido com foco em boas práticas de automação de testes.</h2>

![Cypress](https://img.shields.io/badge/tested%20with-Cypress-17202C?logo=cypress&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18.x-green?logo=node.js)
![API Tested](https://img.shields.io/badge/API-Tested-informational)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Automated%20Tests-2088FF.svg)](https://github.com/features/actions)
![Restful Booker API](https://img.shields.io/badge/Restful%20Booker-API-orange)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)