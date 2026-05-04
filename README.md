<div align="center">

# 🛍️ FakeStoreAPI - Postman Test Suite

### Testes Automatizados de API para Portfólio de QA

[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![Testes API](https://github.com/paulo-qa-test/fakestoreapi-postman-tests/actions/workflows/test.yml/badge.svg)](https://github.com/paulo-qa-test/fakestoreapi-postman-tests/actions/workflows/test.yml)
[![FakeStoreAPI](https://img.shields.io/badge/API-FakeStoreAPI-00A86B?style=for-the-badge)](https://fakestoreapi.com/)

**Suíte completa de testes automatizados para a FakeStoreAPI**

</div>

---

## 📖 Sobre o Projeto

Projeto de testes automatizados para a [FakeStoreAPI](https://fakestoreapi.com/), uma API REST gratuita para testes de e-commerce.

Desenvolvido por **Paulo Henrique** como parte do portfólio de **Quality Assurance (QA)** e **Automação de Testes**.

### 🎯 Cobertura de Testes

| Módulo | Endpoints | Descrição |
|--------|-----------|-----------|
| 🛒 Products | 7 | CRUD completo + Autenticação |
| 🛍️ Carts | 5 | CRUD completo |
| 👤 Users | 5 | CRUD completo |
| 🔐 Auth | 2 | Login (válido/inválido) |
| **TOTAL** | **19** | **80+ testes automatizados** |

---

## 🚀 Como Usar

### Pré-requisitos

- [Postman](https://www.postman.com/downloads/) - Para visualizar os testes
- [Node.js](https://nodejs.org/) - Para executar via CLI

### Executar Localmente

```bash
# Clone o repositório
git clone https://github.com/paulo-qa-test/fakestoreapi-postman-tests.git
cd fakestoreapi-postman-tests

# Instalar dependências
npm install

# Executar todos os testes
npm test

# Executar módulo específico
npm run test:products
npm run test:carts
npm run test:users
npm run test:auth