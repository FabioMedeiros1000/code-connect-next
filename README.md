# Code-Connect

**Code-Connect** é uma aplicação desenvolvida com [Next.js](https://nextjs.org/), que exibe posts relacionados à programação. O projeto foi criado como parte de um curso da Alura e tem como objetivo demonstrar a navegação entre páginas sem o recarregamento completo do navegador, além de exibir conteúdo de cada post ao clicar nele.

## Funcionalidades

- Exibição de posts sobre programação.
- Navegação entre posts sem recarregar a página.
- Estilização com CSS Modules.
- API local para fornecer o conteúdo dos posts, levantada com `json-server`.

## Tecnologias Utilizadas

- **Next.js**: Framework React com renderização híbrida (estática e dinâmica).
- **React**: Biblioteca JavaScript para construção de interfaces.
- **CSS Modules**: Para escopo local de estilos e melhor manutenção.
- **Json-server**: Para simular uma API que fornece os dados dos posts.
- **Imagem otimizada com o componente `Image` do Next.js**.
- **Links dinâmicos com o componente `Link` do Next.js**.

## Aprendizados

Neste projeto, explorei várias funcionalidades do Next.js, como:

- Uso do componente `Image` para otimização de imagens.
- Criação de rotas dinâmicas para páginas com variáveis na URL.
- Acessar parâmetros de rota (query strings) diretamente na URL.
- Navegação com `Link` para evitar carregamento completo da página.
- Levantamento de uma API com `json-server` para fornecer os dados de forma local.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone git@github.com:FabioMedeiros1000/code-connect-next.git
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Execute o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Inicie o `json-server` para levantar a API:
   ```bash
   json-server posts.json -p 4032
   ```

5. Acesse a aplicação no navegador:
   ```
   http://localhost:3000
   ```
