# IIS-Student-Tournament-backend

Ako prvé si stiahnite tieto komponenty:
node.js, npm, tsc, typescript, yarn, nodemon, ts-node

Po naklonovaní repozitára si ako prve zadajte `npm i`

Aby ste využívali lokalné prostredie zadajte `make up`

Nainštalujte si docker a zadajte na druhom termináli príkaz `docker-compose up`

Po tomto budete schopný sa pripojiť na lokalnu DB ktorej `username`, `host`, `password` a `db`
najdete v súbore `docker-compose.yml`

Pre zmigrovanie databáze použite príkaz `npx knex migrate:up` a pre seed dát `npx knex seed:run`
