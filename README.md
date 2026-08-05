# minipuft Plugins

Claude Code plugin marketplace.

## Installation

1. Add marketplace (HTTPS, no auth prompts):
   ```bash
   /plugin marketplace add https://github.com/minipuft/minipuft-plugins.git
   ```

2. Install plugins:
   ```bash
   /plugin install claude-prompts@minipuft
   ```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| [claude-prompts](https://github.com/minipuft/claude-prompts-mcp) | Programmable prompt engine pushing better patterns: symbolic operators, quality gates, and methodology frameworks for reliable AI workflows |

## Plugin Details

### claude-prompts

Marketplace source points to the `dist` branch of `minipuft/claude-prompts-mcp`, which contains the prebuilt plugin artifact (including `server/dist/index.js`). The marketplace uses the HTTPS git URL to avoid SSH auth prompts.

Advanced prompt engineering toolkit for Claude Code featuring:

- **CAGEERF Framework**: Structured methodology for comprehensive responses
- **Chains**: Multi-step prompt workflows with session persistence
- **Gates**: Quality validation and enforcement
- **Styles**: Response formatting control
- **MCP Integration**: Full Model Context Protocol server

**Source**: [minipuft/claude-prompts-mcp](https://github.com/minipuft/claude-prompts-mcp)

## License

MIT
