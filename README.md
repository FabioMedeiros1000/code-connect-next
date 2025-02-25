# Code-Connect

**Code-Connect** é uma aplicação desenvolvida com [Next.js](https://nextjs.org/) para exibir posts sobre programação. O projeto foi parte de um curso da Alura.

<p align="center">
  <img src="./screenshot.png" alt="Code-Connect Screenshot"> 
</p>

## Funcionalidades

- Exibição de posts sobre programação com conteúdo interativo.
- Navegação entre posts.
- Estilização modular com CSS Modules.
- Busca e filtragem de posts.
- Curtir, comentar e comentar um comentário de um post.
- Persistência de dados com banco de dados PostgreSQL e Prisma.

## Tecnologias Utilizadas

- **Next.js**: Framework React para renderização híbrida.
- **React**: Biblioteca JavaScript para construção de interfaces.
- **CSS Modules**: Para estilização modular.
- **Prisma**: ORM para integração com banco de dados PostgreSQL.
- **PostgreSQL**: Banco de dados para armazenamento de posts.
- **Docker**: Containerização do banco de dados.

## Aprendizados

- Configuração e uso do PostgreSQL com Prisma.
- Criação de rotas dinâmicas e navegação eficiente com Next.js.
- Uso do Docker para configurar e gerenciar ambientes de banco de dados.
- Melhoria da UX com CSS Modules e busca dinâmica.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone git@github.com:FabioMedeiros1000/code-connect-next.git
   ```

2. Entre na pasta do projeto:
   ```bash
   cd code-connect-next
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Configure o banco de dados:

   - Certifique-se de ter o Docker instalado e em execução.
   - Execute o container do PostgreSQL com Docker:


   ```bash
   docker-compose up -d
   ```

5. Migre o banco de dados com Prisma:

   ```bash
   npx prisma migrate dev
   ```

6. Realize o seed dos dados para popular o banco com posts:

   ```bash
   npx prisma db seed
   ```

7. Execute o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

8. Acesse a aplicação no navegador:

   ```bash
   http://localhost:3000
   ```

