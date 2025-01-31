This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.


PS C:\swift edge\task-manager> npm i -d prisma
npm info using npm@11.0.0
npm info using node@v20.17.0
npm http fetch GET 200 https://registry.npmjs.org/prisma 3122ms (cache miss)
npm http fetch GET 200 https://registry.npmjs.org/@prisma%2fengines 2326ms (cache miss)
npm http fetch GET 200 https://registry.npmjs.org/@prisma%2fdebug 3514ms (cache miss)
npm http fetch GET 200 https://registry.npmjs.org/@prisma%2fengines-version 5540ms (cache miss)       
npm http fetch GET 200 https://registry.npmjs.org/@prisma%2fget-platform 6759ms (cache miss)
npm http fetch GET 200 https://registry.npmjs.org/@prisma%2ffetch-engine 7129ms (cache miss)
npm http cache @prisma/fetch-engine@https://registry.npmjs.org/@prisma/fetch-engine/-/fetch-engine-6.3.0.tgz 1ms (cache hit)
npm http cache @prisma/get-platform@https://registry.npmjs.org/@prisma/get-platform/-/get-platform-6.3.0.tgz 0ms (cache hit)
npm http cache @prisma/engines-version@https://registry.npmjs.org/@prisma/engines-version/-/engines-version-6.3.0-17.acc0b9dd43eb689cbd20c9470515d719db10d0b0.tgz 0ms (cache hit)
npm http cache @prisma/debug@https://registry.npmjs.org/@prisma/debug/-/debug-6.3.0.tgz 0ms (cache hit)
npm http cache @emnapi/runtime@https://registry.npmjs.org/@emnapi/runtime/-/runtime-1.3.1.tgz 0ms (cache hit)
npm http cache @prisma/engines@https://registry.npmjs.org/@prisma/engines/-/engines-6.3.0.tgz 0ms (cache hit)
npm http cache prisma@https://registry.npmjs.org/prisma/-/prisma-6.3.0.tgz 0ms (cache hit)
npm http fetch GET 200 https://registry.npmjs.org/@prisma/engines-version/-/engines-version-6.3.0-17.acc0b9dd43eb689cbd20c9470515d719db10d0b0.tgz 239ms (cache miss)
npm http fetch GET 200 https://registry.npmjs.org/@prisma/fetch-engine/-/fetch-engine-6.3.0.tgz 294ms (cache miss)
npm http fetch POST 200 https://registry.npmjs.org/-/npm/v1/security/advisories/bulk 372ms
npm http fetch GET 200 https://registry.npmjs.org/@prisma/get-platform/-/get-platform-6.3.0.tgz 379ms (cache miss)
npm http fetch GET 200 https://registry.npmjs.org/cookie 173ms (cache updated)
npm http fetch GET 200 https://registry.npmjs.org/@prisma/debug/-/debug-6.3.0.tgz 800ms (cache miss)  
npm http fetch GET 200 https://registry.npmjs.org/@prisma/engines/-/engines-6.3.0.tgz 812ms (cache miss)
npm http fetch GET 200 https://registry.npmjs.org/@clerk%2fbackend 902ms (cache updated)
npm http fetch GET 200 https://registry.npmjs.org/@clerk%2fnextjs 1010ms (cache updated)
npm http fetch GET 200 https://registry.npmjs.org/prisma/-/prisma-6.3.0.tgz 3187ms (cache miss)       
npm info run prisma@6.3.0 preinstall node_modules/prisma node scripts/preinstall-entry.js
npm info run prisma@6.3.0 preinstall { code: 0, signal: null }
npm info run @prisma/engines@6.3.0 postinstall node_modules/@prisma/engines node scripts/postinstall.js
npm info run @prisma/engines@6.3.0 postinstall { code: 0, signal: null }

added 6 packages, and audited 460 packages in 27s  

146 packages are looking for funding
  run `npm fund` for details

3 low severity vulnerabilities

To address all issues, run:
  npm audit fix

Run `npm audit` for details.
npm info ok
PS C:\swift edge\task-manager> npx prisma init

✔ Your Prisma schema was created at prisma/schema.prisma
  You can now open it in your favorite editor.     

warn Prisma would have added DATABASE_URL but it already exists in .env
warn You already have a .gitignore file. Don't forget to add `.env` in it to not commit any private information.

Next steps:
1. Set the DATABASE_URL in the .env file to point to your existing database. If your database has no tables yet, read https://pris.ly/d/getting-started  
2. Set the provider of the datasource block in schema.prisma to match your database: postgresql, mysql, sqlite, sqlserver, mongodb or cockroachdb.       
3. Run prisma db pull to turn your database schema into a Prisma schema.
4. Run prisma generate to generate the Prisma Client. You can then start querying your database.      
5. Tip: Explore how you can extend the ORM with scalable connection pooling, global caching, and real-time database events. Read: https://pris.ly/cli/beyond-orm

More information in our documentation:
-started

PS C:\swift edge\task-manager>
                               npx prisma generate
Environment variables loaded from .env
Prisma schema loaded from prisma\schema.prisma

✔ Installed the @prisma/client and prisma packages in your project

✔ Generated Prisma Client (v6.3.0) to .\node_modules\@prisma\client in 133ms

Start by importing your Prisma Client (See: https://pris.ly/d/importing-client)

Tip: Want to turn off tips and other hints? https://pris.ly/tip-4-nohints

PS C:\swift edge\task-manager> npx prisma migrate dev
Environment variables loaded from .env
Prisma schema loaded from prisma\schema.prisma
Datasource "db": PostgreSQL database "zcrum", schema "public" at "ep-fancy-shape-a8abgcpx-pooler.eastus2.azure.neon.tech"

√ Enter a name for the new migration: ... create-tables
Applying migration `20250130133039_create_tables`

The following migration(s) have been created and applied from new schema changes:

migrations/
  └─ 20250130133039_create_tables/
    └─ migration.sql

Your database is now in sync with your schema.     

✔ Generated Prisma Client (v6.3.0) to .\node_module
