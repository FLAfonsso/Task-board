# 📋 Task Board

Aplicação web em desenvolvimento para gerenciamento e organização de tarefas, construída com React, TypeScript e Vite. O projeto utiliza uma base moderna de desenvolvimento front-end e está sendo estruturado para receber recursos de gerenciamento de tarefas, validação de dados e comunicação com APIs.

## ✨ Funcionalidades

- 🧩 Estrutura inicial de uma aplicação React com TypeScript
- ⚡ Ambiente de desenvolvimento e build configurado com Vite
- 🎨 Tailwind CSS preparado para estilização da interface
- 📝 React Hook Form e Zod configurados para formulários e validação
- 🔄 TanStack React Query e Axios preparados para consumo e gerenciamento de dados de APIs
- 🌍 i18next e react-i18next preparados para internacionalização
- ✅ ESLint configurado para padronização e qualidade do código

> 🚧 **Status:** projeto em desenvolvimento. A interface e as funcionalidades do Task Board estão sendo implementadas gradualmente.

## 🚀 Tecnologias utilizadas

- **React 19** - Construção da interface
- **TypeScript** - Tipagem estática e segurança no desenvolvimento
- **Vite** - Ferramenta de desenvolvimento e build
- **Tailwind CSS** - Estilização da aplicação
- **Axios** - Comunicação com APIs
- **TanStack React Query** - Gerenciamento de requisições e dados assíncronos
- **React Hook Form** - Gerenciamento de formulários
- **Zod** - Validação e definição de schemas
- **i18next / react-i18next** - Internacionalização
- **ESLint** - Padronização e análise do código

## 📁 Estrutura do Projeto

```text
task-board/
├── public/                # Arquivos públicos da aplicação
├── src/                   # Código-fonte principal
│   ├── assets/            # Imagens e recursos estáticos
│   ├── App.tsx            # Componente principal
│   ├── App.css            # Estilos do componente principal
│   ├── index.css          # Estilos globais
│   └── main.tsx           # Ponto de entrada da aplicação
├── .gitignore
├── eslint.config.js       # Configuração do ESLint
├── index.html             # Documento HTML principal
├── package.json           # Dependências e scripts
├── postcss.config.js      # Configuração do PostCSS
├── tailwind.config.js     # Configuração do Tailwind CSS
├── tsconfig.app.json      # Configuração TypeScript da aplicação
├── tsconfig.json          # Configuração principal do TypeScript
├── tsconfig.node.json     # Configuração TypeScript para o ambiente Node
└── vite.config.ts         # Configuração do Vite
