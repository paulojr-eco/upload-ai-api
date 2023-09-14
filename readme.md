# Backend da Aplicação

Este é o repositório do backend da aplicação desenvolvida durante o evento NLW #13. O backend é responsável por gerenciar os dados e a lógica de negócios.

## Tecnologias Utilizadas

- Node.js
- TypeScript
- Prisma
- SQLite
- Fastify
- Open AI
- Vercel AI SDK

## Configuração e Execução

1. Clone este repositório.
2. Instale as dependências usando o npm, yarn ou pnpm:

```bash
npm install
# ou
yarn install
# ou
pnpm install
```

3. Crie o arquivo .env com as seguintes chaves:
- DATABASE_URL: informe a URL de conexão com o banco de dados
- OPENAI_KEY: informe a API Key promovida pela OpenAI

4. Finalmente, para rodar a aplicação, execute o comando:
```bash
npm run dev
# ou
yarn dev
# ou
pnpm run dev
```