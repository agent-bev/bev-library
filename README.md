# agent-bev Library

The trade rulebook for beverage alcohol, country by country, each section with its official sources.

Library: https://bev-cuvee.org · Hub: https://agent-bev.ai

**Know what a market allows before the trade.**

The Library is agent-bev's book of market rules for beer, wine and spirits. Each
country has its own page at `<country>.bev-cuvee.org` (for example
https://es.bev-cuvee.org), and every page carries the same sections, in the
same order: Market status, Who can trade, Customs and duty, Labelling, Age and
sale limits, Protected names, GTIN authority, Open items and as-of date. Every
section lists its official sources beneath it. Where an official source has not
been found, the page says "Not yet sourced" rather than guess.

## Connect an agent
Add one address to Claude, ChatGPT, Gemini or any agent that speaks the
Model Context Protocol (MCP), the open standard for connecting artificial
intelligence (AI) agents to tools. Read-only, no account.

    https://mcp.bev-cuvee.org/mcp

- `list_countries` — every country in the Library with its code, its page and its as-of date.
- `get_rulebook` — the trade rulebook for one country by its two-letter code (uk for the United Kingdom).

Official MCP Registry: `ai.agent-bev/library` · Agent Card: https://agent.bev-cuvee.org/.well-known/agent-card.json

The Library supports x402 payment on Base in USDC and Open USD. Reads are free today.

## In this repository
- `server.json` — the Official MCP Registry entry `ai.agent-bev/library`, as published
- `agent-card.json` — the Library's Agent Card, as served

## Contact
https://formspree.io/f/xvkgwljq

Artificial intelligence makes mistakes. agent-bev is an information source, not a recommendation.

No ads, ever · No rank for sale · Trade only

Operated by Agentic Enterprises S.A., Barcelona · security keys held by Agentic KG Holdings
https://agent-bev.ai · Library: https://bev-cuvee.org · Doors: https://github.com/agent-bev/bev-door
