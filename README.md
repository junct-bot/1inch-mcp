# 1inch MCP Server

Hosted MCP server for **1inch** — giving AI agents direct access to 1inch dex data and operations.

> Powered by [Junct](https://junct.dev) — the agent-readiness layer for DeFi.

## Quick Connect

Add to your MCP client config (Claude Desktop, Cursor, Windsurf, etc.):

```json
{
  "mcpServers": {
    "1inch": {
      "url": "https://1inch.mcp.junct.dev/mcp"
    }
  }
}
```

**No setup required** — the server is hosted and maintained by Junct.

## Endpoint

| | |
|---|---|
| MCP URL | `https://1inch.mcp.junct.dev/mcp` |
| Transport | Streamable HTTP |
| Domain | dex |
| Tools | 7 |
| Docs | [llms.txt](https://1inch.mcp.junct.dev/llms.txt) |
| OpenAPI | [openapi.json](https://1inch.mcp.junct.dev/openapi.json) |

## Tools (7)

| Tool | Description |
|---|---|
| `aggregation_controller_get_quote_v6_1` | Find the best quote to swap with 1inch Router Returns: { srcToken: { address: string, symbol: string, name: string, deci |
| `aggregation_controller_get_swap_v6_1` | Generate calldata to swap on 1inch Router Returns: { srcToken: { address: string, symbol: string, name: string, decimals |
| `approve_controller_get_spender_v6_1` | Address of the 1inch Router that is trusted to spend funds for the swap Returns: { address: string }. |
| `approve_controller_get_call_data_v6_1` | Generate approve calldata to allow 1inch Router to perform a swap Returns: { data: string, gasPrice: string, to: string, |
| `approve_controller_get_allowance_v6_1` | Get the number of tokens that the 1inch Router is allowed to swap Returns: { allowance: string }. |
| `protocols_controller_get_protocols_images_v6_1` | List of liquidity sources that are available for routing in the 1inch Aggregation Protocol Returns: { protocols: { id: s |
| `tokens_controller_get_tokens_v6_1` | List of tokens that are available for swap in the 1inch Aggregation protocol Returns: { tokens: { 0x111111111117dc0aa78b |

## Links

- [Junct Dashboard](https://junct.dev/servers/1inch)
- [Server Info](https://1inch.mcp.junct.dev/)
- [llms.txt](https://1inch.mcp.junct.dev/llms.txt)
- [agents.md](https://1inch.mcp.junct.dev/agents.md)
- [MCP Discovery](https://1inch.mcp.junct.dev/.well-known/mcp/server.json)

---

*This server is automatically generated, hosted, and maintained by [Junct](https://junct.dev).*
