# Pinafly for coding agents

Your agent writes a UAT. You walk it and pin problems. It reads and fixes them. You verify.
Also: your agent walks you through any tool, one step at a time.

This repo is generated from the Pinafly app. Do not edit it by hand.

## Claude Code

```
claude plugin marketplace add pinafly/agent
claude plugin install pinafly@pinafly          # review: /pinafly:uat, /pinafly:fix, /pinafly:wait
claude plugin install pinafly-guides@pinafly   # guides: /pinafly-guides:guide, /pinafly-guides:write
```

The first time a tool runs, your client opens a Pinafly consent screen. Press Allow. No token to paste.

## Cursor

Install `pinafly` (review) and `pinafly-guides` from the Cursor marketplace, or add this repo as a plugin source.

## Gemini CLI

```
gemini extensions install https://github.com/pinafly/agent
```

Installs the review server (UAT). Guides are not packaged for Gemini yet; use the MCP URL below.

## Any MCP client

| Server | URL |
|---|---|
| UAT (review) | `https://pinafly.com/mcp/uat` |
| Guides | `https://pinafly.com/mcp/guides` |

Docs: https://pinafly.com/docs

## Licence

The files in this repo (plugin manifests, commands and skills) are MIT. Pinafly the service is not open
source, and its terms are at https://pinafly.com/terms.
