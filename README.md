# NLW Agents

## Tecnologias

- **React 19.1** - Biblioteca para interfaces de usuários
- **TypeScript 5.8** - Superset JavaScript com tipagem estática
- **Vite 7.0** - Build tool e servidor de desenvolvimento
- **Tailwind 4.1** - Framework CSS utility-fist
- **React Router Dom 7.6** - Biblioteca de roteamento
- **Radix UI** - Componentes primitivos acessíveis
- **Shadcn/ui** - Sistema de componentes
- **Lucide React** - Biblioteca de ícones

## Padrão do Projeto

- **Component-based Architecture** - Arquitetura baseada em componentes React
- **File-based Routing** - Roteamento baseado em arquivos com React Router
- **Server State Management** - Gerenciamento de estado servidor com React Query
- **Variant-based Components** - Componentes com variantes usando CVA
- **Composition Pattern** - Padrão de composição com Radix Slot
- **Path Aliasing** - Alias de caminhos (`@/` aponta para `src/`)

## Configurações do Projeto

### Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn

### Instalação

1. Clone o repositório
2. Instale as dependências

```sh
npm install
```

3. Execute o servidor de desenvolvimento

```sh
npm run dev
```

4. Acesse a aplicação em `http://localhost:5173`

### Scripts disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build de produção
- `npm run preview` = Preview do build de produção

### Backend

O projeto consome uma API que deve estar rodando na porta `3333`. Certifique-se de que o backend esteja configurado antes de iniciar o frontend.

## Estrutura de Pastas

```text
src/
├── components/ui/  # Componentes de interface
├── pages/          # Páginas da aplicação
├── lib/            # Utilitários e configuração
├── app.tsx         # Componente raiz
```
