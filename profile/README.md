<div align="center">
  <img src="https://itauvwgtmctneefilcff.supabase.co/storage/v1/object/public/public-assets/logo.png" alt="Turbodoc Logo" width="120"/>

  <h3>The open-source knowledge base for humans and AI agents</h3>

  [turbodoc.ai](https://turbodoc.ai) · [Use with Claude & MCP](https://turbodoc.ai/mcp) · [Docs](https://turbodoc.ai/docs)
</div>

# Turbodoc

Bookmarks, markdown notes, code snippets, and diagrams — saved from anywhere, synced everywhere, and readable/writable by your AI assistants.

## 🤖 Use with Claude & AI Agents (MCP)

Turbodoc ships a hosted [Model Context Protocol](https://modelcontextprotocol.io) server with 22 tools, so any MCP client — Claude, Claude Code, Cursor, VS Code, Windsurf — can save, search, and organize your library for you.

```bash
# Claude Code
claude mcp add --transport http turbodoc https://api.turbodoc.ai/mcp
```

- **Endpoint**: `https://api.turbodoc.ai/mcp` (Streamable HTTP)
- **Auth**: OAuth 2.0 — sign in with your Turbodoc account, no API keys
- **Setup guide**: [turbodoc.ai/docs/mcp](https://turbodoc.ai/docs/mcp)

## Open Source & Free

Turbodoc is completely **open source** and **free to use** (while in beta). All applications are available without cost and the source code is publicly accessible for contribution and transparency.

## Applications

| App | Built with | Get it |
|---|---|---|
| **Web** | TanStack Start, React | [turbodoc.ai](https://turbodoc.ai) |
| **iOS** | SwiftUI, SwiftData | [App Store](https://apps.apple.com/nl/app/turbodoc/id6749333065) |
| **Chrome extension** | Manifest V3 | [Chrome Web Store](https://chromewebstore.google.com/detail/turbodoc/fjncckldanedaaaoeapkponpplkahbdg) |
| **Firefox add-on** | Manifest V2 | [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/turbodoc/) |
| **API + MCP server** | Cloudflare Workers, Hono | [api.turbodoc.ai/swagger](https://api.turbodoc.ai/swagger) |

## Repositories

- **API & MCP server**: [turbodoc-api](https://github.com/turbodoc-org/turbodoc-api)
- **Web app**: [turbodoc-web-v2](https://github.com/turbodoc-org/turbodoc-web-v2)
- **iOS app**: [turbodoc-ios](https://github.com/turbodoc-org/turbodoc-ios)
- **Browser extensions**: [turbodoc-extensions](https://github.com/turbodoc-org/turbodoc-extensions)

## License

MIT
