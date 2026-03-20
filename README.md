# 🥋 WebDojo

![WebDojo Cover](.github/cover.png)

## 🚀 Sobre o Projeto

O **WebDojo** é um aplicativo exclusivo para os alunos do **Curso Ninja do Cypress**, ministrado pelo mestre **Fernando Papito**! 🥷💻 Ele foi criado para ser um **campo de treinamento prático**, onde os alunos podem aprimorar suas habilidades em automação de testes com desafios e exercícios focados no **Cypress**.

🛠️ Tecnologias Utilizadas

- [x] Git & GitHub 🌍 (Controle de versão e repositório remoto)
- [x] Bash (Linha de Comando) 💻 (Execução de scripts e comandos)
- [x] Visual Studio Code 🖥️ (Editor de código recomendado)
- [x] Node.js (22+) 🟢 (Runtime JavaScript)
- [x] Gerenciador de pacotes (npm ou yarn) 📦 (Dependências do projeto)
- [x] Cypress 🧪 (Framework de testes end-to-end)
- [x] Docker & Docker Compose 🐳 (Ambiente isolado para execução)
- [x] PostgreSQL 🗄 (Banco de dados relacional)
- [x] Use Bruno 🔌 (Cliente de API para testes de requisições)

## 📖 Como Usar

As instruções detalhadas de instalação e uso do **WebDojo** estão disponíveis dentro do **Curso Ninja do Cypress**.

🔗 **Acesse o curso e seja Ninja da Automação em Cypress!** 👉 [ninjadocypress.com.br](https://ninjadocypress.com.br)

## ⚠️ Contribuição

O **WebDojo** é um ambiente **exclusivo** para os alunos do **Curso Ninja do Cypress**, e por isso, **não aceita contribuições externas**.

📢 Para suporte e dúvidas, utilize os canais oficiais do curso!

## 🔒 Licença

Este projeto é **exclusivo para alunos** do **Curso Ninja do Cypress**. 🚫 O compartilhamento ou distribuição sem autorização é proibido.

------

💙 Feito com dedicação e muito café por **Fernando Papito** e a equipe do **Curso Ninja do Cypress**. 🚀🔥


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

