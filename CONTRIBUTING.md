# Contributing

Thanks for helping keep this the most honest directory of free Grammarly alternatives!

## Adding an entry

1. **Check it fits:** the entry must be a grammar, spelling, style, readability, or closely related writing checker with a **genuinely usable free tier** (permanent free plan) or a **free/open-source** license. Free trials do not count. Generic AI chatbots (ChatGPT, Claude, Gemini) do not count as entries — they are covered as a pattern in the guides. A PR must point at a primary source: the vendor's official site/docs or the project's official repo.
2. **Add to the right section** of `README.md`:
   - System-wide Desktop Assistants (Refine-class) → desktop apps that fix writing inside other apps; free, open-source, **or one-time purchase** (label it — this is the only section where a one-time price is acceptable, mirroring Refine's $38 lifetime model)
   - Augmenting Writing → autocomplete, text expansion/snippets, predictive keyboards, and AI drafting aids (each tool lives in one section only; cross-reference overlaps in the guides)
   - Grammar & Style Checkers (Free Tier) → web/extension checkers with a permanent free plan
   - Open Source & Offline → OSS or self-hostable checkers
   - Readability & Clarity → readability scoring and sentence-clarity tools
   - Academic & Student Writing → essay/thesis/journal-focused checkers
   - Already Built In (Free) → checkers included in a browser, OS, or office suite at no extra cost
3. **One entry = one row** in the README table, matching the catalog record.
4. **Add the matching record** to `data/tools.json` with these exact fields:

| field | type | values |
|---|---|---|
| `name` | string | product / project name |
| `org` | string | vendor / organization / author |
| `category` | string | `system-wide` / `augmenting-writing` / `grammar-checkers` / `open-source` / `readability` / `academic` / `built-in-free` |
| `description` | string | one sentence |
| `best_for` | string | 3–7 words: the writing job this tool wins at |
| `url` | string | official https:// URL |
| `license` | string | exact OSS license, or free model in a few words (e.g. `Freemium (free tier)`) |
| `open_source` | bool | `true` / `false` |
| `verified` | bool | `true` only if you confirmed the entry and its free offering on an official source |
| `last_verified` | string | ISO date, e.g. `2026-10-04` |
| `features` | array | 3–5 short strings: free-tier facts, limits, integrations |

5. **Free-tier honesty:** state the cap that matters (words per check, paraphrases/day, reports/day) in `features` or `docs/free-tier-limits.md`. Never write "unlimited free" unless the vendor's official pricing page says so.
6. **Status changes:** if a product is retired, acquired, renamed, or its free tier is removed, update its README entry *and* add a row (newest-first) to `docs/status-changes.md`. If the free tier disappears entirely, the entry moves out of the list and the change is recorded there.

## Style rules

- Link the **official site** (vendor page or project repo), never a blog post, review, or aggregator.
- Facts that can change (pricing, quotas, word limits) get "as of" context or are omitted — link the source instead of hard-coding numbers that rot.
- Vendor claims stay labeled as vendor claims ("vendor claim", "reported by the vendor").
- Never guess a price, quota, or license. If the official source doesn't state it, write what it does state or mark `verified: false` with the reason in `features`.
- Keep README descriptions to one sentence; put depth in `docs/`.

## CI

Every PR runs:
- **Link check** (lychee) over all markdown files — no dead links.
- **JSON validation** — `data/tools.json` must parse, every record must have the required fields, and `category` must be from the allowed set above. The same link check also runs monthly on a schedule to catch link rot.

Run locally before pushing:

```bash
python3 -c "import json; json.load(open('data/tools.json')); print('ok')"
```
