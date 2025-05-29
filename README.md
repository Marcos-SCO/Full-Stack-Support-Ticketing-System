# Full-Stack-Support-Ticketing-System
Full Stack Support Ticketing System - NextJS + Postgres and Error Monitoring

# Services used
- Sentry (Application logs)
- Neon (database)
- Next.js 15.3.2
- Vercel (Hosting)

# Commands that i used

```bash
npx create-next-app@latest quick-ticket
```

## Dependencies

```bash
npm i prisma @prisma/client react-icons
```

## Sentry configuration

```bash
npx @sentry/wizard@latest -i nextjs --saas --org sco-qn --project javascript-nextjs
```

## Prisma

```bash
npx prisma init
```
### General prisma commands used

```bash
npx prisma migrate dev --name init
```

```bash
npx prisma generate
```

```bash
npx prisma studio
```

### Generate a key to AUTH_SECRET variable
```bash
openssl rand -base64 32
```