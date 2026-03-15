# 1inch MCP Server

MCP server for 1inch. Agent-ready API for 1inch.

Hosted at [1inch.mcp.junct.dev/mcp](https://1inch.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for web3.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "1inch": {
      "url": "https://1inch.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the 1inch API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints.

- **Protocol:** 1inch
- **Endpoint:** `https://1inch.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [1inch.mcp.junct.dev/llms.txt](https://1inch.mcp.junct.dev/llms.txt)

## Links

- [Junct Dashboard](https://junct.dev/servers/1inch)
- [llms.txt](https://1inch.mcp.junct.dev/llms.txt)
- [agents.md](https://1inch.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://1inch.mcp.junct.dev/openapi.json)

Keywords: 1inch, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol
