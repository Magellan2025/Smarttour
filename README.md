# SmartTour ✈️🗺️

Multilingual, map-based audio tour guide app with CMS and subscription system.

## Structure

- `apps/mobile/` — React Native app (Expo)
- `apps/web-cms/` — Next.js CMS dashboard (Sanity, Stripe, Clerk Auth)
- `packages/shared/` — Shared schemas, utils

## Setup

1. Install dependencies with `pnpm install`
2. Add `.env.local` with your environment variables
3. Run locally:
   - `pnpm dev:mobile` for the Expo app
   - `pnpm dev:web` for the CMS dashboard

## Deployment

- Deploy `apps/web-cms` via Vercel
- Use Firebase Hosting if preferred for mobile backend
