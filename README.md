# Awesome Codex Plugins

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/4/4d/OpenAI_Logo.svg" alt="Codex" width="160" />
</p>

<p align="center">
  <strong>A curated list of plugins, tools, and integrations for Codex.</strong>
</p>

---

## About

This repository is a growing collection of useful plugins for Codex-oriented workflows.

It is intentionally simple for now, but designed to become a polished, community-friendly list.

---

## Plugins

| Name | Description | Link |
|------|-------------|------|
| BulkPublish MCP | Approval-based social publishing from Codex and other AI agents through the BulkPublish API and hosted MCP; supports scheduling, media, and multi-channel publishing. | <https://github.com/azeemkafridi/bulkpublish-api> · <https://app.bulkpublish.com/docs> |
| Taisly Agent Kit | Publish short-form videos to TikTok, Instagram Reels, YouTube Shorts, X, and Facebook from Codex with the Taisly MCP server and bundled social media posting skill. | <https://github.com/taisly/agent> |
| NotFair | Open-source Codex marketing skill pack with 45 SEO, GEO, paid-media, and analytics workflows plus approval-gated MCP connectors for live account work. Clone the repository and open it as a Codex workspace; `AGENTS.md` routes requests to the relevant `SKILL.md`. | <https://github.com/nowork-studio/notfair-plugin> |
| RunAPI MCP | Run AI model jobs from Codex through RunAPI's MCP server for image, video, music/audio, text-to-speech, and LLM workflows. | <https://github.com/runapi-ai/mcp> |
| Tree Ring Memory Framework | Framework-agnostic, local-first memory lifecycle for AI agents with Rust CLI, SQLite/FTS recall, forgetting, audit, consolidation, and DOX/Revolve adapters. | <https://github.com/TerminallyLazy/Tree-Ring-Memory> |
| Hermes Tweet | Native Hermes Agent plugin for X/Twitter research, monitoring, drafting, follower exports, and approved actions. Install with `hermes plugins install Xquik-dev/hermes-tweet --enable`. | <https://github.com/Xquik-dev/hermes-tweet> |
| codex-profiles | Switch Codex CLI and Desktop accounts with isolated `CODEX_HOME` profile directories instead of copying auth files. | <https://github.com/Ducksss/codex-profiles> |
| Codex Skin Pack Installer | Codex plugin and Skill for installing verified public-safe Codex desktop skin packs with theme validation and restore guidance. Install with `codex plugin marketplace add ChannelerH/codex-skin-packs --ref main --sparse .agents/plugins --sparse plugins/codex-skin-pack-installer`. | <https://github.com/ChannelerH/codex-skin-packs> |
| emet | Grounded web research MCP plugin for Codex with live sources, cited answers, and current-doc lookup; install via `codex plugin marketplace add https://github.com/endgegnerbert-tech/emet`. | <https://github.com/endgegnerbert-tech/emet> |
| agenttrace | Local-first trace analysis and CI regression gates for Codex and AI coding agent sessions. | <https://github.com/luoyuctl/agenttrace> |
| codex-patch-overlay | Patched Codex CLI builds carrying community-requested features upstream hasn't merged yet (live TUI reasoning streaming, completion sound, WebP image input, timed CLI queueing). Install by downloading a release binary (macOS arm64 / Linux x86_64-musl, sha256-checksummed) or via the Nix overlay `github:salty-flower/codex-patch-overlay/latest-release`. | <https://github.com/salty-flower/codex-patch-overlay> |

> Note: Add focused plugins, tools, and integrations that improve Codex-oriented workflows.

---

## Contributing

Contributions are welcome. When adding a plugin, please include:
- name
- short description
- installation or usage notes
- link to the project or documentation

---

## Status

- Initial version
- Plugin list is currently minimal
- No license section as requested
