# NLW Setup


## Backend 
* `npm init -y`
* `npm i typescript -D`
* `npx tsc --init`
* `npm i tsx -D`
* `npm i fastify`
* `npm i prisma -D`
* `npm i @prisma/client`
  * `npx prisma init --datasource-provider SQLite`
  * `npx prisma migrate dev`
* `npm i @fastify/cors`

## Frontend
* `npm create vite@latest`
* `npm i tailwindcss postcss autoprefixer`
* `npx tailwindcss init -p`
* `Criar src/styles/global.css`
* `Adicionar essas linhas dentro do global.css`
  ```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
  ```
* `tailwind.config.cjs`> `content` >> `./src/**/*.tsx` 
* `main.tsx` >> `import "./styles/global.css";`