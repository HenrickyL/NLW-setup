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