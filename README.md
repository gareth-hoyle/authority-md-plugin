# authority.md plugin

[![HOL Guard Scanner](https://img.shields.io/badge/HOL%20Guard-passing-00a67e)](https://github.com/hashgraph-online/hol-guard)

Find the right documented thinking framework for any task, from inside Claude.

authority.md is a catalog of 640+ thinking frameworks: distillations of how notable people reason, drawn from their documented public work (books, letters, talks and interviews), delivered as Claude Skills and plain `.md` files. The catalog also carries hand-built task Tools and single-job Playbooks. This plugin bundles the authority.md MCP server with a skill that knows how to use it, plus one complete framework as a free sample.

## What is in the plugin

- **`authority-md` connector** (`.mcp.json`): a remote MCP server at `https://authority.md/api/mcp` with four tools: `search_personas`, `get_persona_details`, `list_categories` and `purchase_persona`. No authentication required. `purchase_persona` only generates a checkout link; payment happens on authority.md.
- **`framework-finder` skill**: when you name a thinker or describe a problem, Claude searches the catalog, explains which frameworks fit and why, and links the product page. It does not push purchases.
- **`sherlock-holmes` skill**: a complete framework from the catalog, free. Deduction, negative-space reasoning and the elimination ladder, drawn from Arthur Conan Doyle's public-domain stories.

## Install

**Claude Code** (terminal):

```bash
claude plugin marketplace add gareth-hoyle/authority-md-plugin
claude plugin install authority-md@authority-md
```

Then try `/authority-md:framework-finder` or ask: "How would Warren Buffett evaluate this acquisition?" Run `/mcp` to confirm the `plugin:authority-md:authority-md` server is connected.

**claude.ai and Cowork**: download this repository as a zip (Code > Download ZIP), then go to Customize > Plugins > Add > Upload plugin and select it. The plugin folder is the repository root, so the zip works as downloaded. Connect the bundled connector from the plugin's Connectors tab.

**Any MCP client**: add `https://authority.md/api/mcp` as a streamable HTTP server. Setup notes for Claude Desktop, Cursor and others are at https://authority.md/mcp.

## Data

The connector sends your search queries and any slugs you request to authority.md. It stores nothing about you and sets no cookies through the plugin. Checkout links open on authority.md, where payment is handled by Stripe. Nothing in this plugin executes code: it is Markdown and JSON only. File hashes for every product are published at https://authority.md/hashes.json and the full statement is at https://authority.md/security.

## Compatibility

Skills follow the open Agent Skills format (`SKILL.md`), which Claude, Codex, Gemini CLI and Cursor read. The MCP server is standard streamable HTTP and works with any MCP client.

## Attribution

Every framework in the catalog is an independent distillation of documented public work. None is affiliated with, endorsed by, or a substitute for the thinker's own books, courses or products, which the frameworks point readers toward. Fictional and mythological figures are drawn from public-domain source texts only.

## License

MIT. See `LICENSE`.
