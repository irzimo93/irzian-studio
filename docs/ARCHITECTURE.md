# Technical Architecture — Initial

## Current implementation
- Static HTML, CSS, and minimal JavaScript.
- Public assets live in `public/`.
- Cloudflare Workers serves the static asset directory.
- Wrangler is the local development and deployment tool.

## Deliberate non-goals for version 0.1
- No database
- No user accounts or authentication
- No checkout or payment processing
- No wallet connection or NFT minting
- No collection of personal/customer data

## Future extension points
When the business requires them, introduce separately reviewed components:
- Backend/API for catalog, orders, and customer workflows
- Database with documented retention and backup policies
- Payment provider integration
- Authentication and access control
- Digital-asset metadata and provenance services

Avoid adding infrastructure before there is a real product requirement. Keep secrets out of Git; use platform-managed secrets for future server-side integrations.
