# Seaynic Labs plugins

A Claude Code plugin marketplace for the free, MIT-licensed bundles by [Seaynic Labs](https://seayniclabs.com). Each bundle installs its MCP tools and its skills together.

```
/plugin marketplace add seayniclabs/plugins
/plugin install gauge@seayniclabs
/plugin install schematic@seayniclabs
```

| Plugin | What it does | Repository |
|---|---|---|
| `bench` | USB hardware discovery for your AI assistant: find maker boards (Arduino, ESP32, Pico), their serial ports and chips, plus skills for bring-up, serial debugging, crash decoding and safe flashing. | [seayniclabs/bench](https://github.com/seayniclabs/bench) |
| `gauge` | Your website's Umami analytics and Resend email, plus skills for weekly reports, copy, SEO and email. | [seayniclabs/gauge](https://github.com/seayniclabs/gauge) |
| `homelab` | Nginx Proxy Manager, Docker and Cloudflare DNS in your AI assistant, with approval for every change, plus skills for setup, exposing services, troubleshooting and health checks. By Seaynic Labs. | [seayniclabs/homelab-infra-mcp](https://github.com/seayniclabs/homelab-infra-mcp) |
| `knowledge` | Search and write your self-hosted Open Notebook from your AI assistant, plus skills for meeting notes, decision records, weekly reviews and source-backed research. By Seaynic Labs. | [seayniclabs/knowledge](https://github.com/seayniclabs/knowledge) |
| `lathe` | Local file and media tools for your AI assistant: images, PDFs, audio and video, OCR, batch runs and metadata removal, with skills for getting started, PDF output, fillable forms and web photo prep. By Seaynic Labs. | [seayniclabs/lathe](https://github.com/seayniclabs/lathe) |
| `privacyops` | Track credit-report disputes and draft dispute letters, kept on your own computer, with skills that walk you through each dispute. Not legal advice. By Seaynic Labs. | [seayniclabs/privacyops](https://github.com/seayniclabs/privacyops) |
| `schematic` | Diagram skills for your AI assistant: editable draw.io files, network maps, codebase maps, and animated or dark architecture diagrams. Skills only, no server. By Seaynic Labs. | [seayniclabs/schematic](https://github.com/seayniclabs/schematic) |

`bench` needs its binary first: `brew install seayniclabs/tap/bench` (macOS). The plugin adds its skills and connects to it.

Every entry is pinned to an exact release commit, so a plugin only changes when we publish a new version here. Each bundle also installs without Claude Code: see its repository.

Built by [Seaynic Labs](https://seayniclabs.com). MIT.
