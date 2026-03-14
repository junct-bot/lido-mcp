# Lido MCP Server

MCP server for Lido. Agent-ready API for Lido.

Hosted at [lido.mcp.junct.dev/mcp](https://lido.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for the crypto stack.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "lido": {
      "url": "https://lido.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Lido API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints, no phantom tools.

- **Protocol:** Lido
- **Endpoint:** `https://lido.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [lido.mcp.junct.dev/llms.txt](https://lido.mcp.junct.dev/llms.txt)
- **Server card:** [lido.mcp.junct.dev/.well-known/mcp/server.json](https://lido.mcp.junct.dev/.well-known/mcp/server.json)

## Links

- [Junct Dashboard](https://junct.dev/servers/lido)
- [llms.txt](https://lido.mcp.junct.dev/llms.txt)
- [agents.md](https://lido.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://lido.mcp.junct.dev/openapi.json)

## Keywords

Lido, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol, hosted MCP
