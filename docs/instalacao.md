# Instalação detalhada

Calculadora CBS é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_calculadora-cbs`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_calculadora-cbs` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_calculadora-cbs` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_calculadora-cbs` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.calculadoracbs` (ou `servers.calculadoracbs` no VS Code) do config do cliente e reinicie.
