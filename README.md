<h1 align="center"> Spacetime - Back End </h1>

## 1 - Sobre

Aplicação de recordação de memórias, onde o usuário poderá adicionar à uma timeline textos, fotos e vídeos de acontecimentos marcantes da sua vida, organizados por mês e ano.

## 2 - Tecnologias

Um pouco das tecnologias que foram utilizadas no projeto:

- NodeJS
- TypeScript
- Fastify
- Prisma
- Zod
- Axios
- Tsx

## 3 - Instalação e uso

Você precisa ter o [Node](https://nodejs.org/en/), o [Git](https://git-scm.com/) e algum gerenciador de pacotes([NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm/) | [Yarn](https://classic.yarnpkg.com/lang/en/docs/install)) instalados em sua máquina.

```bash
1. Clone o repositório:
$ git clone https://github.com/felipems1/spacetime-server.git

2. Acesse a pasta e instale as dependências via terminal:
$ yarn install / npm install

3. Em seguida, crie um arquivo .env, copiando o formato do arquivo .env.example:
$ env.example -> .env

4. Execute as migrations com o comando:
$ yarn prisma migrate dev / npx prisma migrate dev

5. Inicie a aplicação em modo de desenvolvimento:
$ yarn dev / npm run dev

6. O servidor será aberto em http://localhost:3333
```

<p align="center">Projeto feito com ❤️ por <a href="https://www.linkedin.com/in/felipems12/">Felipe Moises</a></p>
