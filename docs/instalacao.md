# Instalação detalhada

Reajuste de Aluguel é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_reajuste-de-aluguel`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_reajuste-de-aluguel` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_reajuste-de-aluguel` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_reajuste-de-aluguel` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.reajustedealuguel` (ou `servers.reajustedealuguel` no VS Code) do config do cliente e reinicie.
