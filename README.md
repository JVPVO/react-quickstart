# Vite + React Compiler + React Scan + shadcn/ui

Este é um projeto inicial (quick start) utilizando:

- [Vite](https://vitejs.dev/) - Build tool e dev server
- [React Compiler](https://github.com/facebook/react/tree/main/packages/react-compiler) - Compilador React para melhor performance
- [React Scan](https://github.com/aidenybai/react-scan) - Análise estática de componentes React
- [shadcn/ui](https://ui.shadcn.com/) - Componentes React reutilizáveis e estilizados

## Começando

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [pnpm](https://pnpm.io/) (recomendado para gerenciamento de pacotes)

### Instalação

1. Clone o repositório:

```bash
git clone https://github.com/JVPVO/react-quickstart.git
cd react-quickstart
```

2. Instale as dependências com pnpm:

```bash
pnpm install
```

### Desenvolvimento

Inicie o servidor de desenvolvimento:

```bash
pnpm dev
```

Acesse o aplicativo em [http://localhost:5173](http://localhost:5173)

### Build para produção

Crie uma versão otimizada para produção:

```bash
pnpm build
```

Visualize a versão de produção localmente:

```bash
pnpm preview
```

## Estrutura do Projeto

```
/
├── public/          # Arquivos estáticos
├── src/
│   ├── assets/  # Assets
│   ├── components/         # Componentes shadcn/ui
│   ├── lib/      # Utilitários e funções auxiliares
│   ├── App.tsx      # Componente principal
│   └── main.tsx     # Ponto de entrada
└── ...
```

## Tecnologias

Este projeto utiliza as seguintes tecnologias:

- **React 19** - Biblioteca para construção de interfaces
- **TypeScript** - Superset tipado de JavaScript
- **Vite** - Build tool e dev server extremamente rápido
- **React Compiler** - Otimização automática de componentes React
- **React Scan** - Análise estática para identificar problemas em componentes
- **shadcn/ui** - Componentes React reutilizáveis e estilizados
- **Tailwind CSS** - Framework CSS utilitário
- **ESLint** - Linter para identificar e corrigir problemas no código

## Comandos Disponíveis

- `pnpm dev` - Inicia o servidor de desenvolvimento
- `pnpm build` - Cria uma versão otimizada para produção
- `pnpm preview` - Visualiza a versão de produção localmente
- `pnpm lint` - Executa o linter para verificar problemas no código
- `pnpm test` - Executa os testes

## Configuração Adicional

### Adicionando Componentes do shadcn/ui

Para adicionar componentes do shadcn/ui, utilize o CLI:

```bash
pnpm dlx shadcn@latest add [nome-do-componente]
```

Exemplo:

```bash
pnpm dlx shadcn@latest add button
```

### Configuração do ESLint

Este projeto já vem com uma configuração básica do ESLint. Para expandir a configuração, edite o arquivo `eslint.config.js`.


## Autor

- **JVPVO** - [GitHub](https://github.com/JVPVO)
