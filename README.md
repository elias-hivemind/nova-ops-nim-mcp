# nova-ops-nim-mcp
An MCP (Model Context Protocol) server that gives AI clients two tools — nim_generate_image (Flux Pro / Flux Realism) and nim_generate_video (Kling Pro image-to-video) — through NVIDIA NIM. Both tool schemas together cost ~198 tokens per turn, measured.

## Part of the Nova Ops shelf

nova-ops-nim-mcp is one tool on the [Nova Ops](https://github.com/elias-hivemind)
shelf — local-first tools, verified working before they are trusted:

- **[Elias HiveMind](https://github.com/elias-hivemind/obsidian-elias-hivemind)** —
  an Obsidian plugin for offline summaries, tags, links, and digests.
  No API key, no account, no telemetry.
- **[release-gate](https://github.com/elias-hivemind/release-gate)** —
  a fail-closed release verifier: `seal` writes SHA256SUMS plus a
  hash-chained ledger; `verify` refuses on tamper, missing files, or
  stale seals.
