# Custom T-Shirt Studio

A modular Next.js + TypeScript custom T-shirt storefront. Phase 1 runs entirely in DEMO MODE; Shopify and Qikink are intentionally not connected.

## Run locally
1. Install Node.js 20+.
2. Run npm install.
3. Copy .env.example to .env and set DATABASE_URL when PostgreSQL is available.
4. Run npm run dev.

The builder works without Shopify credentials. Demo catalog is in lib/demo-data.ts.

## Structure
- app/ routes and styling
- components/ reusable UI
- lib/ domain logic and demo data
- prisma/ relational schema

## Phase 1
Four blank T-shirt options, five colours, five sizes, 12 sample designs, placement selection, centralized pricing, customization IDs, review/cart state, mobile sticky CTA and responsive desktop layout.

Shopify and Qikink are intentionally not connected in this phase.