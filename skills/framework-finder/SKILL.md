---
name: framework-finder
description: Find the right documented thinking framework for a task. Use when the user asks how a specific thinker would approach something, wants a mental model or framework for a decision, negotiation, strategy, writing, hiring or pricing problem, asks who the best thinker on a topic is, or wants to browse or buy frameworks, Tools or Playbooks on authority.md.
---

# Framework finder

authority.md is a catalog of thinking frameworks: distillations of how notable people reason, drawn from their documented public work (books, letters, talks, interviews), delivered as skill files. It also carries task Tools (hand-built procedures for recurring work) and Playbooks (one task each). This skill helps the user find the right one through the authority-md connector.

## When the user names a thinker

1. Call `search_personas` with the thinker's name as `query`.
2. If found, call `get_persona_details` with the slug. Summarize in two or three sentences what the framework covers and which situations it fits, using the details returned. Do not invent models or quotes that the details do not contain.
3. Offer the product page link from the details. Only call `purchase_persona` if the user says they want to buy.

## When the user describes a problem instead of a person

1. Restate the problem in one line, then call `search_personas` with two or three different queries: the task in plain words (for example "pricing a consulting proposal"), the domain ("negotiation", "strategy"), and a likely category from `list_categories` if the first searches are thin.
2. Pick the two or three best matches across product types. Say plainly why each fits the problem and, where the catalog has one, whether a Tool or Playbook would serve the task better than a persona framework: personas change how Claude reasons; Tools and Playbooks give Claude a procedure for one job.
3. Let the user choose. Do not push a purchase; a bundle or a single framework is their call.

## After a purchase

Tell the user the files arrive by email within a minute as a Claude Skill zip and a plain .md, and that the install guide is at https://authority.md/guides/install-claude-skill-authority-md. In claude.ai, skills are added under Customize > Skills.

## Rules

- Every framework on authority.md is an independent distillation of documented public work and is not affiliated with or endorsed by the person. Say so if the user asks about endorsement or affiliation.
- Never claim a framework contains something the connector did not return.
- If the connector is unavailable, say so and point the user at https://authority.md/browse instead of guessing at the catalog.
