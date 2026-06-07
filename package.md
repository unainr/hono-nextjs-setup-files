# Package Installation Guide

This document contains all the necessary package installations for the Hono + Next.js setup.

## Required Packages

### Authentication
```bash
pnpm add @clerk/nextjs
pnpm add @clerk/hono
```

### Data Fetching & State Management
```bash
pnpm add @tanstack/react-query
```

### Backend Framework
```bash
pnpm add hono
pnpm add @hono/zod-validator
```

### UI Components
```bash
pnpm dlx shadcn@latest init -t next
pnpm dlx shadcn@latest add --all
```

### Animation
```bash
pnpm add motion
```

### Validation
```bash
pnpm add zod
```

### File/Image Management
```bash
pnpm add @imagekit/nodejs
```

### Database
```bash
pnpm add drizzle-orm @neondatabase/serverless dotenv
```

### Development Dependencies
```bash
pnpm add -D drizzle-kit tsx
```

## Quick Install (All at Once)

```bash
pnpm add @clerk/nextjs @tanstack/react-query hono @hono/zod-validator @clerk/hono motion zod @imagekit/nodejs drizzle-orm @neondatabase/serverless dotenv
pnpm add -D drizzle-kit tsx
```

Then run:
```bash
pnpm dlx shadcn@latest init -t next
pnpm dlx shadcn@latest add --all
```
