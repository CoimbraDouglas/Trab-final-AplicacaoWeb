# 📚 Sistema de Cadastro de Alunos - Web e Mobile

Este projeto consiste em uma aplicação web e mobile integrada para cadastro e gerenciamento de alunos, utilizando tecnologias modernas como React, Vite, Material UI, Axios e Expo.

**Aplicativo foi disponivel no link** ✔ alunosApp: https://expo.dev/accounts/coimbradouglas/projects/alunosApp on EAS

✔ Linked local project to EAS project 7d411cb8-6fae-4f19-bdc3-0b96cb0083b7

---

## ⚙️ 1. Configuração do Ambiente

### Requisitos

- [Node.js](https://nodejs.org/)
- [VS Code](https://code.visualstudio.com/) com extensões recomendadas para React (ex: ESLint, Prettier, React Snippets)

### Criação do Projeto Web
```bash
npm create vite@latest nome-do-projeto --template react
cd nome-do-projeto
npm install
```

### Instalação de Bibliotecas
```
npm install @mui/material @emotion/react @emotion/styled
npm install axios
npm install react-router-dom
```

---

## 🔗 2. Integração com a API

Consultar a documentação da API de alunos (insira o link real da API).

Utilizar o Axios para criar funções de requisição (GET, POST, PUT, DELETE).

Implementar um formulário com Material UI para cadastrar alunos.

Exibir a lista de alunos cadastrados com opções de edição e remoção.

---

## 🧩 3. Organização do Código

Utilizar componentes modulares para manter o código limpo e reutilizável.

Separar as chamadas da API em arquivos específicos (ex: services/api.js).

Utilizar Context API ou outros métodos de gerenciamento de estado para compartilhar dados entre componentes.

---

## 🌍 4. Configuração e Hospedagem

Criar variáveis de ambiente para desenvolvimento e produção (.env).

Testar a aplicação localmente com:
```
npm run dev
```

---

## 📱 5. Desenvolvimento do Aplicativo Mobile

Criação com Expo:
```
npx create-expo-app nome-do-app
cd nome-do-app
npm install axios react-navigation
```

Funcionalidades Mobile:
Tela de cadastro e listagem de alunos.

Integração com a mesma API utilizada na versão web.

Testes em emuladores ou dispositivos físicos via Expo Go.

---

## ✅ 6. Testes e Melhorias

Validar os dados dos formulários (campos obrigatórios, formatos, etc.).

Adicionar feedbacks visuais (ex: Snackbar do Material UI, alertas).

Realizar testes manuais para garantir o funcionamento completo da versão web e mobile.

---

## 🚀 Tecnologias Utilizadas

React + Vite
Material UI
Axios
React Router
Expo (React Native)
Context API
Vercel

---

## ✅Fazendo atualizações via Terminal no git

```
git status
git add .
git commit -m "Adicionando nova versão do projeto mobile"
git push origin main
```
