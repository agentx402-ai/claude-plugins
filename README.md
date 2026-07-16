# agentx402 Claude Code plugins

The plugin marketplace for [agentx402](https://agentx402.ai) products.

## Usage

```sh
/plugin marketplace add agentx402-ai/claude-plugins
/plugin install agentkv@agentx402
/plugin install agentscout@agentx402
```

## Plugins

| Plugin | Description |
| --- | --- |
| `agentkv` | Agent-native encrypted KV store paid via x402 — persistent cross-session memory, encrypted secret storage, and shared fleet state, keyed by wallet address and zero-knowledge to the server. |
| `agentscout` | Agent-native web read/extract/crawl paid via x402 — fetch any URL to clean markdown, extract structured JSON against a schema, or crawl a site; paid per fetch in USDC, no accounts or API keys. |

Each plugin's code lives in its own product repository; this marketplace is a thin
index that references it. Adding a plugin here does not vendor its source.
