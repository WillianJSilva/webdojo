# 🧪 Testes Automatizados - Webdojo (Cypress)

## 📌 Sobre o projeto

Este projeto contém testes automatizados end-to-end (E2E) para a aplicação **Webdojo**, utilizando o framework **Cypress**.

A aplicação e os testes estão no mesmo repositório, sendo necessário iniciar a aplicação antes da execução dos testes.

---

## 📁 Estrutura do Projeto

```
WEBDOJO/
├── api/
├── web/
│   ├── cypress/
│   │   ├── e2e/
│   │   ├── fixtures/
│   │   │   ├── cep.json
│   │   │   ├── consultancy.json
│   │   │   └── document.pdf
│   │   ├── support/
│   │   │   ├── actions/
│   │   │   │   └── consultancy.actions.js
│   │   │   ├── commands.js
│   │   │   ├── e2e.js
│   │   │   └── utils.js
│   │   └── cypress.config.js
├── .github/
├── .vscode/
```

---

## ⚙️ Pré-requisitos

- Node.js instalado
- NPM ou Yarn
- Cypress instalado (via dependência do projeto)

---

## 🚀 Como executar o projeto

### 1. Instalar dependências

```bash
npm install
```

### 2. Subir a aplicação Webdojo

```bash
npm run dev
```

A aplicação será iniciada em:

```
http://localhost:3000
```

---

## 🧪 Execução dos testes

### ▶️ Rodar todos os testes (modo headless)

```bash
npm run test
```

---

### 🖥️ Rodar testes com interface do Cypress

```bash
npm run test:ui
```

---

### 🔐 Rodar testes de login (desktop)

```bash
npm run test:login
```

---

### 📱 Rodar testes de login (mobile)

```bash
npm run test:login:mobile
```

---

## 📐 Configurações de viewport

| Tipo     | Resolução          |
|----------|------------------|
| Desktop  | 1440 x 900       |
| Mobile   | 414 x 896        |

---

## 📦 Fixtures

Os arquivos de **fixtures** são utilizados para simular dados nos testes:

- `cep.json` → Dados de CEP
- `consultancy.json` → Dados de consultoria
- `document.pdf` → Arquivo para testes de upload/download

---

## 🛠️ Suporte e utilitários

- `commands.js` → Comandos customizados do Cypress
- `utils.js` → Funções auxiliares
- `consultancy.actions.js` → Ações reutilizáveis para testes de consultoria
- `e2e.js` → Configuração global dos testes

---

## ✅ Boas práticas adotadas

- Separação por responsabilidades (actions, utils, fixtures)
- Reutilização de código com commands e actions
- Uso de fixtures para dados mockados
- Testes organizados por feature dentro de `e2e`

---

## ⚠️ Observações importantes

- Sempre garantir que a aplicação esteja rodando antes de executar os testes
- Verificar se a porta `3000` está disponível
- Ajustar baseUrl no `cypress.config.js` se necessário

---

## 📬 Contribuição

Sinta-se à vontade para contribuir com melhorias nos testes, organização ou documentação.

---
