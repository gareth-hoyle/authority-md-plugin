# Security

This plugin contains Markdown and JSON only. It executes no code, installs no dependencies, runs no scripts and sets no environment variables.

- The bundled connector points at `https://authority.md/api/mcp`, a streamable HTTP MCP server that requires no authentication. It receives your search queries and requested slugs and stores nothing about you.
- `purchase_persona` only generates a checkout URL. No payment detail passes through the server or this plugin; payment is handled on authority.md by Stripe.
- Every product file authority.md delivers is instruction-only. SHA-256 hashes for all of them are published at https://authority.md/hashes.json and the full statement is at https://authority.md/security.

To report a vulnerability in this plugin or the MCP server, email hello@authority.md with "security" in the subject. We acknowledge within two working days.
