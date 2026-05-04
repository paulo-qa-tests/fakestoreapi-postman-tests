<div align="center">

# 🚀 FakeStoreAPI - Postman Test Suite

### Testes Automatizados de API | Portfólio de Quality Assurance

[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![Newman](https://img.shields.io/badge/Newman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://learning.postman.com/docs/running-collections/using-newman-cli/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)
[![Testes](https://github.com/paulo-qa-tests/fakestoreapi-postman-tests/actions/workflows/test.yml/badge.svg)](https://github.com/paulo-qa-tests/fakestoreapi-postman-tests/actions/workflows/test.yml)

**Uma suíte completa de testes automatizados para API REST de e-commerce**

[📊 Cobertura](#-cobertura-de-testes) • 
[🚀 Execução](#-como-executar) • 
[🤖 CI/CD](#-cicd-com-github-actions) • 
[📁 Estrutura](#-estrutura-do-projeto)

</div>

---

## 🎯 Sobre o Projeto

Este projeto demonstra minhas habilidades como **QA Engineer** através de uma suíte completa de testes automatizados para a [FakeStoreAPI](https://fakestoreapi.com/), uma API REST gratuita para testes de e-commerce.

### 💡 O que este projeto prova sobre mim:

| Habilidade | Evidência |
|-----------|-----------|
| **Automação de Testes** | 19 endpoints testados com scripts JavaScript no Postman |
| **Planejamento de Testes** | Cobertura completa de CRUD + cenários de erro |
| **Integração Contínua** | CI/CD configurado com GitHub Actions |
| **Documentação Técnica** | README profissional e estruturado |
| **Validação de API** | Testes de status code, schemas e tipos de dados |

---

## 📊 Cobertura de Testes

### Estatísticas Gerais

| Métrica | Valor |
|---------|-------|
| **Endpoints testados** | 19 |
| **Requests** | 19 |
| **Testes automatizados** | 38+ |
| **Status code verificados** | 200, 201, 401 |
| **Cobertura de métodos** | GET, POST, PUT, DELETE |

### Detalhamento por Módulo

| Módulo | Endpoints | Métodos | Cenários |
|--------|-----------|---------|----------|
| 🛒 **Products** | 7 | GET, POST, PUT, DELETE | Listagem, busca, criação, atualização, remoção, autenticação, 404 |
| 🛍️ **Carts** | 5 | GET, POST, PUT, DELETE | Listagem, busca, criação, atualização, remoção |
| 👤 **Users** | 5 | GET, POST, PUT, DELETE | Listagem, busca, criação, atualização, remoção |
| 🔐 **Auth** | 2 | POST | Login válido e inválido |

### ✅ Cenários Testados

- ✅ **Sucesso (200/201)** - Fluxos principais
- ✅ **Erro (401)** - Credenciais inválidas
- ✅ **Validação de schemas** - Campos obrigatórios
- ✅ **Tipos de dados** - ID numérico, strings, arrays
- ✅ **Autenticação** - Token JWT

---

## 🛠️ Tecnologias Utilizadas

| Ferramenta | Finalidade | Versão |
|-----------|-----------|--------|
| **Postman** | Criação e execução dos testes | v10+ |
| **Newman** | Execução via linha de comando | v6+ |
| **GitHub Actions** | Integração contínua (CI/CD) | - |
| **Node.js** | Runtime para Newman | v18+ |
| **JavaScript** | Scripts de validação | ES6+ |

---

## 📋 Pré-requisitos

```bash
# Node.js (para executar via CLI)
node --version  # v18 ou superior

# Postman (para visualizar/editar testes)
# Baixe em: https://www.postman.com/downloads/