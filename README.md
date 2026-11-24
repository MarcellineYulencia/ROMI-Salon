# ROMI Salon

A full stack salon reservation and membership application built with React, TypeScript, Express, and Drizzle ORM. Customers can browse services, book visits, and track membership benefits; administrators manage salon operations.

## Live demo

https://digital-craft-studio--huanivan9.replit.app

## Development

Use Node.js 24 and pnpm. Install dependencies with `pnpm install`, then run the frontend and API development scripts in their respective workspace packages. See [application documentation](artifacts/romi-salon/README.md) for configuration, demo accounts, payment simulation, and checks. PostgreSQL is selected through `DATABASE_URL`; a SQLite fallback is available. Keep production credentials in environment variables.

## Checks

- `pnpm run typecheck`
- `pnpm --filter @workspace/romi-salon run build`
- `pnpm --filter @workspace/api-server run build`

The VM deployment workflow is manual and requires repository secrets to be configured.
