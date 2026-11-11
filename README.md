# Admin Dashboard (Vue 3 + Nuxt 3)

An admin dashboard for managing customers, products and transactions, built with Vue 3 and Nuxt 3.

## What's in it

- **Authentication** with JWT and route middleware that protects signed-in pages
- **Customers, products and transactions** views with sortable, paginated tables (TanStack Table)
- **Forms validated with Zod** through VeeValidate, sharing schemas between client and server
- **State management with Pinia**
- **Server API routes** in Nuxt's `server/` directory, serving seeded demo data
- **Charts** for transaction activity
- UI built with Tailwind CSS and Radix Vue components

## Stack

Vue 3, Nuxt 3, TypeScript, Pinia, TanStack Table, VeeValidate, Zod, Tailwind CSS

## Run it locally

```bash
npm install
npm run dev
```

The app runs at `http://localhost:3000`.

## Project layout

| Folder | Purpose |
|---|---|
| `pages/` | Routes: auth, customers, products, transactions, profile |
| `components/` | UI components |
| `stores/` | Pinia stores |
| `schemas/` | Zod validation schemas |
| `middleware/` | Route guards |
| `server/` | API routes and demo data |
