# Deliberately excluded, and retired

A curated list is defined as much by what it leaves out. Everything below was considered for this catalog and kept out on purpose; the reason is stated for each. If a catalog tool later paywalls its free tier or shuts down, it moves here (via `docs/status-changes.md`) instead of silently disappearing — the monthly freshness watch checks for exactly that.

## Excluded: no real free offer
| Tool | Why it's out |
|---|---|
| [Antidote](https://www.antidote.info) | Excellent French/English checker, but paid software with no free version or free tier. The list's one-time-purchase exception applies only to system-wide Refine-class apps, and Antidote isn't one. |
| [WhiteSmoke](https://www.whitesmoke.com) | Paid subscription only; its "free trial" requires payment details. Free trials don't count as free tiers anywhere in this catalog. |
| [Notion AI](https://www.notion.com/product/ai) | A paid per-member add-on, and it only works inside Notion. Good tool, wrong list. |
| Grammarly itself | The baseline this list replaces. Its free plan exists, but listing the thing being alternatived helps nobody. |

## Excluded: wrong shape for this list
- **Generic AI chatbots** (ChatGPT, Claude, Gemini, …): "paste your paragraph into a chatbot" is a real workflow, so the guides cover it as a pattern — but a general-purpose chatbot is not a grammar checker, and listing three chatbots as "tools" would pad the catalog without informing anyone.
- **Trial-only tools**: anything whose free offer expires in 7–30 days. A trial is a sales funnel, not a free tier.
- **Extension clones and reskins**: browser extensions that wrap someone else's engine (usually LanguageTool's) without adding anything. The engine is listed; the wrapper adds a privacy surface and no capability.

## Dropped during research (honesty log)
- **Grambo** — named in early research for this list, but its official URL could not be verified from any source we trust, so it was never added. If you have the canonical site, open an issue.
- Three catalog entries (**Reverso Grammar Checker, OnlineCorrection.com, Slick Write**) are flagged `verified: false` in `data/tools.json` — live for humans, unreachable from our verification environment. They're kept, flagged, and excluded from automated link-checking rather than quietly deleted or quietly trusted.

## Retired from this catalog
- **Typewise** (removed 2026-10-05) — listed in the System-wide section as a multilingual phone/desktop keyboard with a free tier. Per the monthly freshness watch, its consumer product is gone: the vendor's own site (typewise.app) now describes the company solely as a B2B "AI Customer Experience Platform," and its consumer keyboard chapter closed in 2022. A company that no longer sells a writing tool can't be in a writing-tools list. Verified on the official page 2026-10-05.
- **Readable** (removed 2026-10-05) — listed under Readability as freemium with a free tier. Per the monthly freshness watch, the free offer is now trial-only: the vendor's pricing page (readable.com/pro) shows paid plans with a "7 Days Free Readability Scoring" trial and no perpetual free tier. This list's rule stands: a trial is a sales funnel, not a free tier. Verified on the official page 2026-10-05.
