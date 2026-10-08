# Install Crustdata MCP

Crustdata's MCP server is hosted. There is nothing to clone, build or run locally.

1. Add a remote MCP server (streamable HTTP) with this URL:

   `https://install.crustdata.com/mcp`

2. For a client that uses a JSON config, add:

   ```json
   {
     "mcpServers": {
       "crustdata": {
         "url": "https://install.crustdata.com/mcp"
       }
     }
   }
   ```

3. On first use the client opens an OAuth sign-in window. Sign in with a Crustdata account (a free account works).

No API key or environment variables are needed.
