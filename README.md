# Crustdata MCP

Real-time B2B data for AI agents: search and enrich 1B+ people and 200M+ company profiles.

Crustdata's MCP server is hosted, so there is nothing to install or run. Point any MCP client at:

```
https://install.crustdata.com/mcp
```

Transport: streamable HTTP. Auth: OAuth 2.1 (your client opens a sign-in window on first use).

## What you can do

- Search people by title, employer, seniority, location, education and skills
- Search companies by funding, headcount, growth, industry and technology
- Enrich a company from a domain or a person from a LinkedIn URL
- Find work emails and phone numbers
- Track job postings, hiring and job changes
- Search and fetch the live web

Typical uses: recruiting, sales prospecting, investment research.

## Connect

**Claude:** Settings > Connectors > Add custom connector, paste the URL above.

**Claude Code:**

```bash
claude mcp add --transport http crustdata https://install.crustdata.com/mcp
```

**Cursor / VS Code / any MCP client:**

```json
{
  "mcpServers": {
    "crustdata": {
      "url": "https://install.crustdata.com/mcp"
    }
  }
}
```

## Registry

Published in the official MCP Registry as `io.github.mhimed-crustdata/crustdata`.

## Links

- Website: https://crustdata.com
- Docs: https://docs.crustdata.com/general/mcp
