# Spacetime - Back-End

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

### Requisitos:

- [NodeJS](https://nodejs.org/en/)
- [Npm](https://www.npmjs.com) ou [yarn](https://yarnpkg.com)

Clone o projeto em sua máquina e instale as dependências com o comando:

```shell
yarn ou npm install
```

Em seguida, crie um arquivo **.env**, copiando o formato do arquivo **.env.example**:

```
env.example -> .env
```


Execute as migrations com o comando:

```
yarn prisma migrate dev

ou

npx prisma migrate dev
```

Para rodar o servidor localmente:

```
yarn dev

ou

npm run dev
```

---

<p align="center">Projeto feito com ❤️ por <a href="https://www.linkedin.com/in/felipemoises12/">Felipe Moises</a></p>