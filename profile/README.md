# GetAppNiche

**App market intelligence for people who ship apps.** Explore 4M+ apps indexed across the App Store &
Google Play with revenue & download data, ASO keyword scoring, review analytics — in a dashboard, over a REST API, and through a hosted
MCP server your AI agent can call directly.

### Start here

- 🌐 **Product** — [getappniche.com](https://getappniche.com)
- 📊 **Dashboard** — [app.getappniche.com](https://app.getappniche.com)
- 🤖 **MCP server for AI agents** — [getappniche.com/mcp](https://getappniche.com/mcp)
- 🧠 **Agent skills** — [`getappniche/aso-skills`](https://github.com/getappniche/aso-skills):
  `npx skills add getappniche/aso-skills`
- 🔌 **MCP server & stdio bridge** — [`getappniche/mcp`](https://github.com/getappniche/mcp):
  hosted endpoint + zero-dependency bridge for stdio-only clients
- 📚 **Docs & guides** — [getappniche.com/docs](https://getappniche.com/docs)
- 🐦 **X / Twitter** — [@getappniche](https://x.com/getappniche)

### For AI agents, in one line

```bash
claude mcp add --transport http getappniche https://api.getappniche.com/mcp \
  --header "Authorization: Bearer YOUR_API_KEY"
```

Questions → [yaro@getappniche.com](mailto:yaro@getappniche.com)
