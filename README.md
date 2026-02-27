# Webhooks Ltd — Claude Code Plugins

Plugin marketplace for [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

## Installation

```bash
/plugin marketplace add Webhooks-Ltd/claude-plugins
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [sharp-recon](https://github.com/Webhooks-Ltd/SharpRecon) | .NET MCP server for NuGet package inspection, type introspection, and decompilation |

### sharp-recon

```bash
/plugin install sharp-recon
```

Requires .NET 10.0 SDK. After installing, build once:

```bash
dotnet publish src/SharpRecon/SharpRecon.csproj -o src/SharpRecon/bin/publish
```

See the [SharpRecon README](https://github.com/Webhooks-Ltd/SharpRecon) for full documentation.
