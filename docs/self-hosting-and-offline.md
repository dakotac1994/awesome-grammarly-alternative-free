# Self-hosting and offline checking

The privacy argument in one line: every cloud grammar checker — Grammarly, QuillBot, LanguageTool's hosted service — processes your text on someone else's server. If the draft is unpublished, sensitive, or under NDA, run the checker yourself.

## The offline stack

| Need | Tool | How it runs |
|---|---|---|
| Grammar in the browser/editor | [Harper](https://github.com/Automattic/harper) | Browser extension, VS Code, Obsidian, Neovim — 100% local, milliseconds per document |
| Full grammar server (30+ languages) | [LanguageTool Server](https://github.com/languagetool-org/languagetool) | Docker/Java server on your machine or VPS; point the official browser extension at it |
| Docs-as-code style linting | [Vale](https://github.com/vale-cli/vale) | CLI in CI; style-guide rule packs, fully offline |
| LaTeX/Markdown in VS Code | [LTeX+](https://github.com/ltex-plus/ltex-ls-plus) | LSP server wrapping LanguageTool; offline mode supported |
| Spell checking code | [cspell](https://github.com/streetsidesoftware/cspell) / [typos](https://github.com/crate-ci/typos) | CLI/CI; per-project dictionaries |

## Self-hosting LanguageTool

1. Run the official server (Docker image `silvio/docker-languagetool` or the Java server from the repo) on `localhost:8081`.
2. Install the LanguageTool browser extension and set it to use your local server instead of `languagetool.org`.
3. Know the limit: the open-source server ships the **free rule set**. The cloud Premium rules (advanced style, picky mode) are proprietary and do not come with self-hosting. For most drafts, the free rules plus a Hemingway pass are enough.

## Trade-offs to expect

- **You own the updates.** Rule sets improve monthly on the cloud; a self-hosted server only improves when you upgrade it.
- **English depth is thinner offline.** Harper and the OSS LanguageTool rules catch real errors, but Grammarly's cloud models still lead on subtle, context-dependent English mistakes. Offline wins on privacy and price, not on maximum accuracy.
- **Multilingual flips the ranking.** LanguageTool's 30+ languages make it the strongest free option for non-English writing, hosted or self-hosted.
