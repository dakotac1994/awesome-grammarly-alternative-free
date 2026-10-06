# Refine-class apps: system-wide writing assistants

**Refine-class** (named for [Refine](https://refine.sh/), the app that defined the modern form) = a desktop assistant that fixes your writing *inside whatever app you're already typing in*, instead of asking you to paste text into a website.

## What defines the class

1. **System-wide injection** — suggestions appear inline (underlines, cards, hotkey popups) in Mail, Slack, your browser, your editor. No copy-paste round trip.
2. **Local-first or BYOK inference** — a model on your machine (Gemma/Qwen-class via MLX/llama.cpp/Ollama), or your own API key sent directly to the provider. Your text is not a SaaS's training corpus by default.
3. **A floating editor / hotkey fallback** — select text anywhere, hit a shortcut, get it fixed in place. This is what saves these apps in Electron/canvas apps where inline underlines can't reach.
4. **Per-app and per-language control** — allow/deny lists, personal dictionary, custom instructions scoped by app or site.
5. **No subscription by default** — free, open-source, or one-time purchase ($29–39 is the going rate). This is the economic break from Grammarly.

## The field, honestly

| App | Platform | Engine | Price | Pick it if… |
|---|---|---|---|---|
| [Apple Writing Tools](https://support.apple.com/guide/mac-help/writing-tools-write-improve-summarize-mchldcd6c260/mac) | macOS / iOS / iPadOS | On-device (Apple Intelligence) | Free (built-in) | You have an Apple Intelligence device and want zero installs — the baseline this whole class is compared against |
| [Refine](https://refine.sh/) | macOS 14+ | Local models + BYOK | Free core / $38 once | You want the most complete offline Grammarly replacement on Mac |
| [GhostEdit](https://github.com/nareshnavinash/GhostEdit) | macOS 13+ | Local HF models / BYOK | Free (MIT) | You want that idea open-source, hotkey-driven, $0 |
| [GrammarGem](https://www.grammargem.com/) | macOS (Apple Silicon) | On-device | $39 once | You want one hotkey, writing modes, zero setup |
| [RewriteBar](https://rewritebar.com/) | macOS | BYOK / Ollama / LM Studio / Apple Intelligence | $29 once | You prefer a command palette and custom actions |
| [Fixkey](https://fixkey.ai/) | macOS | BYOK/cloud | One-time | You want 60+ tools and presets, not just grammar |
| [Kerlig](https://www.kerlig.com/) / [BoltAI](https://boltai.com/) | macOS | BYOK | One-time | You already pay for API keys and want inline AI commands everywhere |
| [WritingTools](https://github.com/theJayTea/WritingTools) | Windows | Local / BYOK | Free, open-source | You're on Windows and envy macOS Writing Tools |
| [GemType](https://github.com/riponcm/GemType) | Chrome/Safari + desktop | Your free Gemini key | Free, open-source | You want in-browser underlines at $0 using Google's free tier |
| [Elephas](https://elephas.app/) | Mac/iPhone/iPad | Cloud / BYOK | Freemium | You write across Apple devices and want replies + rewrites, not just fixes |
| [Cotypist](https://cotypist.app/) | macOS (Apple Silicon) | On-device Gemma | Free plan | You want autocomplete that writes *with* you (adjacent to checking, not a checker) |

## What to watch for

- **Accessibility permission is the product.** Every app here needs macOS Accessibility (or the Windows equivalent) to read and replace text. Grant it only to apps you trust; open-source entries let you audit why.
- **App compatibility is a matrix, not a promise.** Native apps (Mail, Notes, TextEdit) work best; Electron and canvas apps vary. Every serious vendor publishes a compatibility list — check yours before paying.
- **Local models need hardware.** Apple Silicon with 16 GB RAM is the comfortable floor for on-device checking; below that, BYOK (your key, cloud model) is the pragmatic path — Refine itself steers low-RAM machines this way.
- **"One-time purchase" ≠ free**, and this list labels it as such. The Refine-class section is the one place this repo includes paid tools, because a $38 lifetime license is a genuinely different proposition from a $144/year subscription — and because the free/open-source members of the class (GhostEdit, WritingTools, GemType) deserve to be found next to the app that defined it.
