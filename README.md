<<<<<<< HEAD
# 🏖️ Ultimate Praia

Sistema completo de gerenciamento para operações de praia, desenvolvido para otimizar o controle de guarda-vidas, postos, materiais e cautelas.

## 🚀 Demo

Acesse a aplicação: [ultimate-praia.vercel.app](https://ultimate-praia.vercel.app)

## ✨ Funcionalidades

- **🏃 Dashboard Interativo**: Visão geral de todas as operações em tempo real
- **👥 Gestão de GVCs**: Controle completo de guarda-vidas e suas escalas
- **📍 Gerenciamento de Postos**: Administração de postos de salvamento
- **📦 Controle de Materiais**: 
  - Inventário em tempo real
  - Rastreamento de faltas
  - Histórico de alterações
- **📋 Sistema de Cautelas**: Gestão de empréstimos e responsabilidades
- **⭐ Registro de Conduta**: Alterações, elogios e ocorrências
- **🔐 Autenticação Segura**: Sistema de login com Firebase Authentication
- **📱 Design Responsivo**: Interface adaptável para desktop, tablet e mobile

## 🛠️ Stack Tecnológica

### Frontend
- **React 19.2** - Framework principal
- **TypeScript** - Tipagem estática
- **Vite** - Build tool e dev server
- **React Router DOM** - Roteamento SPA
- **Tailwind CSS 4.1** - Estilização

### Backend & Infraestrutura
- **Firebase** - Backend as a Service
  - Firestore - Banco de dados NoSQL
  - Authentication - Sistema de autenticação
  - Hosting - Deploy da aplicação

### UI/UX
- **Lucide React** - Ícones
- **React Icons** - Ícones complementares
- **React Hot Toast** - Notificações
- **next-themes** - Tema claro/escuro

## 📦 Instalação

### Pré-requisitos
- Node.js 18+ 
- npm ou yarn

### Passo a passo

1. Clone o repositório
```
git clone https://github.com/BrenoBalsini/ultimate-praia.git
cd ultimate-praia
```

2. Instale as dependências
```
npm install
```

3. Configure as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto:

```
VITE_FIREBASE_API_KEY=sua_api_key
VITE_FIREBASE_AUTH_DOMAIN=seu_auth_domain
VITE_FIREBASE_PROJECT_ID=seu_project_id
VITE_FIREBASE_STORAGE_BUCKET=seu_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=seu_sender_id
VITE_FIREBASE_APP_ID=seu_app_id
```

4. Inicie o servidor de desenvolvimento
```
npm run dev
```

A aplicação estará rodando em `http://localhost:5173`

## 🏗️ Scripts Disponíveis

```
npm run dev      # Inicia servidor de desenvolvimento
npm run build    # Cria build de produção
npm run preview  # Preview do build de produção
npm run lint     # Executa o linter
```

## 📁 Estrutura do Projeto

```
src/
├── components/       # Componentes reutilizáveis
├── contexts/         # Context API (Auth, Theme, etc)
├── firebase/         # Configurações do Firebase
├── hooks/            # Custom hooks
├── pages/           # Páginas da aplicação
│   ├── Alteracoes/  # Gestão de alterações
│   ├── Cautelas/    # Sistema de cautelas
│   ├── GVC/         # Gestão de guarda-vidas
│   └── Postos/      # Gerenciamento de postos
├── services/        # Serviços e API calls
├── types/           # TypeScript types e interfaces
└── utils/           # Funções utilitárias
```

## 🔒 Segurança

- Autenticação via Firebase Authentication
- Rotas protegidas com `ProtectedRoute`
- Regras de segurança do Firestore configuradas
- Variáveis de ambiente para credenciais sensíveis

## 🚀 Deploy

O projeto está configurado para deploy automático na Vercel. Cada push na branch `main` dispara um novo deploy.

### Deploy manual
```
npm run build
# O build estará na pasta dist/
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT.

## 👤 Autor

**Breno Balsini**

- GitHub: [@BrenoBalsini](https://github.com/BrenoBalsini)

## 📧 Contato

Para dúvidas ou sugestões, abra uma issue no GitHub.

---

Desenvolvido com ❤️ para melhorar a gestão de operações de praia
=======
# ultimate-praia-portfolio
>>>>>>> 88d4660614413e7865077954fc1ac5ccd921b2af
