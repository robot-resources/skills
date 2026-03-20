# Robot Resources — Agent Skills

**Human Resources, but for your AI agents.**

This repo contains agent skills for [Robot Resources](https://robotresources.ai) — the free, local toolkit that cuts LLM costs and compresses web content.

## What's included

### `robot-resources` skill

Teaches AI agents how to install and use Robot Resources:

- **Router** — Routes each LLM call to the cheapest capable model. 60-90% cost savings across OpenAI, Anthropic, and Google.
- **Scraper** — Compresses web pages to clean markdown. 70-80% fewer tokens per page.

## Install the skill

### Claude Code / Codex CLI

```bash
npx skills add robot-resources/skills
```

### ClawHub

```bash
clawhub install robot-resources
```

## Install Robot Resources

```bash
npx robot-resources
```

One command sets up the Router proxy, configures your agents, and gets you saving immediately.

## Links

- [Website](https://robotresources.ai)
- [Router MCP](https://github.com/robot-resources/router-mcp)
- [Scraper MCP](https://github.com/robot-resources/scraper-mcp)
- [npm: robot-resources](https://www.npmjs.com/package/robot-resources)

## License

MIT
