# Choosing a free Grammarly alternative

There is no single best free checker — there is a best checker for the writing you actually do. Work through these steps in order.

## Step 1: What are you writing?

- **Email, Slack, docs at work** → a browser-extension checker (LanguageTool, QuillBot, Microsoft Editor). The value is checking *where you already type*, not in a separate tab.
- **Essays, theses, journal papers** → an academic checker (Trinka, Writefull, Paperpal) plus a plagiarism pass (Quetext, PaperRater). Generic checkers miss journal style guides entirely.
- **Blog posts and marketing copy** → readability first (Hemingway, WebFX Readability Tool), grammar second. A grammatically perfect paragraph nobody finishes reading is still a failure.
- **Code documentation (Markdown, LaTeX)** → open-source linters (Vale, Harper, LTeX+, cspell). They run in CI next to your tests and never phone home.
- **Non-English or multilingual writing** → LanguageTool (30+ languages) or Grammalecte (French). Grammarly's non-English support is the thinnest part of its product.

## Step 2: Where can your text go?

- **Text cannot leave your machine** (unpublished manuscripts, legal, journalistic sources) → offline tools only: Harper, self-hosted LanguageTool, Vale. Every cloud checker, Grammarly included, sends your text to a server.
- **Text is public anyway** (blog drafts, social posts) → any free cloud tier is fine; pick on features.

## Step 3: What does "free" actually cover?

Read [free-tier limits](free-tier-limits.md) before committing. The patterns:

- **Word-capped free tiers** (ProWritingAid: 500 words/check) work for email, not manuscripts.
- **Feature-capped free tiers** (LanguageTool, QuillBot) give unlimited basic checks and paywall the advanced style rules — usually the best deal.
- **Completely free tools** (Hemingway web, Scribens, built-in Docs/Edge checkers) have no caps because they do less — no account, no sync, no team features.

## Step 4: The stack most people end up with

You do not need one tool; you need two passes:

1. **Grammar pass** — LanguageTool (cloud or self-hosted) or Harper (offline).
2. **Readability pass** — Hemingway, pasted in at the end.

That stack is $0, covers Grammarly's core job, and the readability pass is something Grammarly's free plan does not really do. Add a dedicated academic or API tool only when your writing demands it.

## Red flags

- "Unlimited free forever" with no visible business model — your text is probably the product.
- No way to see *why* a change was suggested. A checker that rewrites silently teaches you nothing and will eventually change your meaning.
- Accuracy claims ("99% accurate!") with no named test set. There is no standard grammar benchmark vendors report against; treat all such numbers as marketing.
- Free tiers that require a credit card. That is a trial, not a free tier, and it does not belong on this list.
