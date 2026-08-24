# New Blood LLC — Plugin Marketplace

A [Claude Code plugin marketplace](https://claude.ai/code) for tools built by New Blood LLC.

## Available Plugins

| Plugin | Description |
|---|---|
| **db-query** | Structured read-only database querying for AI agents — MCP server exposing allowlisted PostgreSQL and SQL Server tables/views through portable filter operators |
| **decision-traces** | Decision trace logger — MCP server with dynamic multi-schema support and configurable storage/embedding backends |
| **fetch-guard** | MCP server for controlled web fetching with URL whitelist enforcement |
| **skill-cache** | Cache the output of any side-effect-free skill — returns cached results on hits, delegates and caches on misses |
| **state-machine** | Drive agent workflows as explicit, resumable state machines. |

## Installation

Add the marketplace to Claude Code:

```
/plugin marketplace add new-blood-llc/marketplace
```

Then install a plugin:

```
/plugin install db-query@new-blood-llc
/plugin install decision-traces@new-blood-llc
/plugin install fetch-guard@new-blood-llc
/plugin install skill-cache@new-blood-llc
/plugin install state-machine@new-blood-llc
```

## Access

This marketplace repo is public. The plugin repos it references are private — you need read access to the corresponding repo to install a plugin. Contact New Blood LLC for access.

## License

Proprietary. All rights reserved.
