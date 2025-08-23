# Kilo Code

Tidewave can be used with [Kilo Code](https://kilocode.ai) - an agent for VS Code.

In addition to reading the instructions below, you may wish to read [Kilo Code's MCP configuration documentation](https://kilocode.ai/docs/features/mcp/using-mcp-in-kilo-code).

Project-specific MCP configuration is stored at `.kilocode/mcp.json`. An editor for this file can be opened in VS Code by clicking the MCP Servers icon in the top navigation of Kilo Code's pane and then using the 'Edit Project MCP' button.

Does Kilo Code have need of the proxy? Test.

Is the 'disabled: false' line required? Test.

<!-- tabs-open -->

### Rails

```
{
  "mcpServers": {
    "Tidewave": {
      "url": "http://localhost:4000/tidewave/mcp",
      "type": "streamable-http"
    }
  }
}
```

### Phoenix

```
{
  "mcpServers": {
    "Tidewave": {
      "url": "http://localhost:4000/tidewave/mcp"
    }
  }
}
```

<!-- tabs-close -->
