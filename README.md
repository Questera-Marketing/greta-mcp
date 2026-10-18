# Greta MCP server

<!-- mcp-name: sh.greta/greta -->

Connect your AI agent to [Greta](https://www.greta.sh), the AI app builder. Ask Claude, ChatGPT, Cursor or any MCP client to build you a website or an app, and Greta makes a real hosted project with a live URL, not a mockup.

This is a **remote** MCP server. There is nothing to install or run.

```
https://mcp.greta.sh
```

Transport: Streamable HTTP. Auth: OAuth 2.1 (your client opens a browser and you sign in to Greta).

## Connect

**Claude Code**

```bash
claude mcp add greta --transport http https://mcp.greta.sh
```

Then run `/mcp`, pick **greta** and sign in.

**Claude.ai, ChatGPT, Cursor, VS Code and other MCP clients**: add a custom connector or server with the URL above; the client signs you in to Greta.

## What your agent can do

- **Build** a full-stack app (frontend, backend, database) or a self-growing website by chatting with Greta's builder, and follow each build
- **Start from a template**: search Greta's marketplace of finished apps and make one your own
- **Deploy** an app's backend and **publish** a website to its live address
- **Grow a website**: run its nightly growth loop with a credit cap, see what it suggests to be cited by AI answer engines, queue pages, review what the publish gate held, and read what each night ran and cost
- **Check** projects, credits and how a site is doing

Building, deploying and growth runs use Greta credits. Every paid action states its cost, and the agent can cap what a call may spend.

## Links

- Website: https://www.greta.sh
