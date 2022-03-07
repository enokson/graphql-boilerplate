# TS - GraphQL Boilerplate

## Dev server
```
npm run dev
```

* GraphiQL can befound at http://localhost:3000/graphql

## Prisma migrations
```
npx prisma migrate dev
```

Behind the scenes, when you are using Prisma, it generates files to /node_modules/@prisma/client, so every time you use the PrismaClient, you get a tailer-made types that matches your models.

## Prisma studio
```
npx prisma studio
```

## Order of operations
1. update the prisma/schema.prisma file with new models
2. run the migration
```
npx prisma migrate dev --name "<migration name>"
```
