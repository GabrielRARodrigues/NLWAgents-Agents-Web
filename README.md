# NLW Agents (Web App)

Projeto desenvolvido durante o evento **NLW 20 (Agents)** da Rocketseat, focado em criar uma aplicação web para gerenciamento de salas e agentes.

## 🚀 Tecnologias

- **React 19** - Biblioteca para construção de interfaces
- **TypeScript** - Tipagem estática para JavaScript
- **Vite** - Build tool e dev server
- **Tailwind CSS** - Framework CSS utilitário
- **React Router DOM** - Roteamento para React
- **TanStack Query** - Gerenciamento de estado e cache
- **Shadcn/ui** - Sistema de componentes
- **Radix UI** - Componentes acessíveis
- **Lucide React** - Ícones
- **Biome** - Linter e formatter

## 📁 Estrutura do Projeto

```
src/
├── components/    # Componentes reutilizáveis
├── pages/         # Páginas da aplicação
├── lib/           # Utilitários e configurações
├── app.tsx        # Componente principal
└── main.tsx       # Ponto de entrada
```

## 🛠️ Setup e Instalação

### Pré-requisitos
- Node.js (versão 18 ou superior)
- npm ou yarn
- Git

### Instalação

1. Clone o repositório:
    ```bash
    git clone <url-do-repositorio>
    cd agents-web
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Execute o projeto em modo de desenvolvimento:
    ```bash
    npm run dev
    ```

4. Acesse a aplicação em `http://localhost:5173`

### Backend

o projeto consome uma API que deve estar rodando na porta 3333. Certifique-se de que o backend esteja configurado e executando antes de iniciar o projeto.

[Link do repositório do backend](https://github.com/gabrielrarodrigues/NLWAgents-Agents-Server)

## 📜 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` - Visualiza o build de produção

## 🎨 Padrões de Projeto

- **Componentes**: Utiliza shadcn/ui para componentes base
- **Roteamento**: React Router para navegação entre páginas
- **Estado**: TanStack Query para gerenciamento de estado e cache
- **Estilização**: Tailwind CSS com variáveis CSS customizadas
- **Linting**: Biome para formatação e linting de código

## 📱 Funcionalidades

- Criação de salas
- Navegação entre salas
- Interface responsiva e moderna
- Componentes acessíveis

---

Desenvolvido com ❤️ durante o NLW 20 da Rocketseat 