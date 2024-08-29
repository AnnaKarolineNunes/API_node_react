# Projeto de Cadastro de Usuários

Este projeto é uma aplicação de cadastro de usuários utilizando Node.js no back-end com o framework Express e o banco de dados MongoDB, gerenciado pela biblioteca Prisma. No front-end, foi utilizado React. O sistema permite criar, listar, atualizar e deletar usuários.

## Tecnologias Utilizadas

### Back-end:
- **Node.js**: Ambiente de execução para o JavaScript no servidor.
- **Express**: Framework web para Node.js.
- **Prisma**: ORM (Object-Relational Mapping) utilizado para gerenciar o banco de dados.
- **MongoDB**: Banco de dados NoSQL, versão gratuita utilizada.

### Front-end:
- **React**: Biblioteca JavaScript para construção de interfaces de usuário.
- **CSS**: Para estilização da interface.

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
   cd nome-do-repositorio

2. **Instale as dependências:**

    npm install
    cd frontend
    npm install

3. **Configure o Prisma e MongoDB:**

- Verifique se o arquivo schema.prisma está configurado corretamente para usar o MongoDB como banco de dados. O arquivo deve conter algo semelhante a:

    ```bash
        datasource db {
            provider = "mongodb"
            url      = env("DATABASE_URL")
            }

- Crie uma conta no MongoDB Atlas e configure um cluster gratuito. Após configurar o cluster, obtenha a string de conexão no formato mongodb+srv://<username>:<password>@cluster.mongodb.net/<database>?retryWrites=true&w=majority.

- Crie um arquivo .env na raiz do diretório do back-end e adicione a seguinte linha, substituindo <string-de-conexao> pela string de conexão que você obteve no MongoDB Atlas:

    ```bash
    DATABASE_URL="<string-de-conexao>"


