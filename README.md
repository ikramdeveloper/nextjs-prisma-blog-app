# NextJS Blog Using Prisma & Next Auth

Using Prisma with PostgreSQL & Next (TypeScript) & Next GitHub Auth to create Blog app

### Bootstrap a basic Prisma setup:

First install prisma

```
npm install prisma
```

Then initialize prisma setup:

```
npx prisma init
```

### Reflect tables in database

```
npx prisma db push
```

### Start prisma studio

```
npx prisma studio
```

### Install & generate prisma client

```
npm install @prisma/client
```

```
npx prisma generate
```

### Create prisma.ts file to initiate PrismaClient instance

```
mkdir lib && touch lib/prisma.ts
```

---

#### For complete guide: [Visit](https://vercel.com/guides/nextjs-prisma-postgres)
