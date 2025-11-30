# Dyad - AI App Builder

## Overview
Dyad is a free, local, open-source AI app builder built with Electron. It provides a graphical interface for building AI applications with support for multiple AI providers (OpenAI, Anthropic, Google, Azure, etc.).

## Project Structure
- **src/**: Source code (React + TypeScript)
- **main/**: Electron main process
- **workers/**: Background workers
- **drizzle/**: Database migrations and schemas
- **e2e-tests/**: End-to-end tests with Playwright
- **.vite/**: Vite build output

## Technology Stack
- **Framework**: Electron + React 19 + TypeScript
- **UI**: Radix UI + Tailwind CSS + Geist
- **Database**: SQLite with Drizzle ORM
- **Build**: Vite + Electron Forge
- **Testing**: Vitest + Playwright
- **Linting**: ESLint + Oxlint + Prettier

## Setup
1. Dependencies are managed with npm
2. Use `npm install` to install all packages
3. Run `npm start` to start the dev environment

## Development Commands
- `npm start` - Start Electron app in dev mode
- `npm run dev:engine` - Start with local LLM engine
- `npm run test` - Run unit tests
- `npm run test:watch` - Watch mode for tests
- `npm run e2e` - Run end-to-end tests
- `npm run lint` - Lint code
- `npm run prettier` - Format code
- `npm run db:push` - Apply database migrations
- `npm run ts` - Type-check TypeScript

## Database
- Uses SQLite with Drizzle ORM
- Migrations in `drizzle/` directory
- Schema defined in TypeScript

## Recent Changes
- Project imported to Replit
- Development environment configured
