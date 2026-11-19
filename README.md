# telkit-tools

Public downloads for [Telkit](https://telkit.io): the `telkit` command line and the Claude Code plugin.

## CLI

```
curl -fsSL https://telkit.io/install.sh | sh
telkit --version
```

Binaries for macOS and Linux (arm64, x86_64) and `SHA256SUMS` are on the Releases page.

## Claude Code plugin

```
/plugin marketplace add fleek-fitness/telkit-tools
/plugin install telkit@telkit
```

The plugin connects Claude Code to the Telkit remote MCP server (`https://api.telkit.io/mcp`).
