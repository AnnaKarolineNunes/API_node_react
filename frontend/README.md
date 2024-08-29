# Projeto de Cadastro de Usuários - Backend

Este é o backend de uma aplicação de cadastro de usuários, desenvolvido com Node.js, Express, Prisma, e MongoDB. Ele fornece uma API para operações de criação, leitura, atualização e exclusão de usuários.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para o JavaScript no servidor.
- **Express**: Framework web para Node.js.
- **Prisma**: ORM (Object-Relational Mapping) utilizado para gerenciar o banco de dados.
- **MongoDB**: Banco de dados NoSQL, versão gratuita utilizada.

## Instalação e Configuração

### Pré-requisitos:
- Node.js instalado
- Gerenciador de pacotes npm ou yarn
- Conta gratuita no MongoDB e instância configurada
- Banco de dados configurado com Prisma

### Passos:

    1. **Clone o repositório:**

    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    cd nome-do-repositorio/backend
    ```

    2. **Instale as dependências:**

    ```bash
        npm install 
    ```

    3. **Executar a Aplicação**

    ```bash
        npm run dev
    ```


## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte forma:

-public/: Contém o arquivo index.html que serve de base para a aplicação.
src/:
-assets/: Arquivos estáticos, como imagens e ícones.
-components/: Componentes React reutilizáveis.
-pages/: Páginas principais da aplicação.
-services/: Arquivos responsáveis por interações com APIs externas.
-styles/: Arquivos de estilos CSS.
-index.jsx: Ponto de entrada da aplicação.
-main.jsx: Ponto de entrada principal do React.
-App.jsx: Componente raiz que contém as rotas e estrutura principal da aplicação.

##Dependências

-**react**: Biblioteca principal para construção da interface de usuário.
-**react-dom**: Integração do React com a árvore DOM.
-**react-router-dom**: Gerenciamento de rotas na aplicação.
-**axios**: Biblioteca para realizar requisições HTTP.
-**vite**: Ferramenta para desenvolvimento rápido de aplicações web.