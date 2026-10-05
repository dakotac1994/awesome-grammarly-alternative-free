# Stacks: ready-made $0 setups

A list of 68 tools is a catalog, not a recommendation. These stacks are the opinionated answer for common setups — each one is $0 (free tiers, open-source, or what you already own), in install order. Pick yours, install top to bottom, stop when it works.

## The $0 Mac stack
1. **Apple Writing Tools** (already on your Mac, if Apple Intelligence) — Proofread/Rewrite baseline in every app. Free, on-device, zero install.
2. **Refine** (free core) *or* **GhostEdit** (free, MIT) — system-wide inline/hotkey fixes beyond Apple's, local-first. Refine if you want polish and 36 languages; GhostEdit if you want open-source and BYOK.
3. **LanguageTool** (browser extension) — the multilingual and in-browser depth Apple doesn't do.
4. **Hemingway** (web, when it matters) — one readability pass before you send anything long.
*Skip if:* your Mac has no Apple Intelligence — start at step 2.

## The $0 Windows stack
1. **WritingTools** (free, open-source) — Apple-style proofread/rewrite popup in any Windows app, local or BYOK.
2. **LanguageTool** (extension + web editor) — grammar depth and 30+ languages.
3. **Microsoft Editor** (Edge/Chrome extension) — free basic checks where you browse, already from Microsoft.
4. **Espanso** (free, open-source) — your snippets everywhere; the augmenting layer.
*Also:* Beeftext if you prefer GUI snippets over Espanso's YAML.

## The $0 Linux stack
1. **LanguageTool Server** (self-hosted) + the browser extension pointed at it — unlimited, private, 30+ languages.
2. **Harper** (editor/browser builds) or **Vale** (docs) — on-device checking in your editor and CI.
3. **Espanso** — cross-platform expansion, same config as your other machines.
4. **LibreOffice Writer** — the document home base; LanguageTool plugs straight in.

## The student stack (essays & thesis)
1. **LanguageTool** or **Scribbr** — everyday grammar in the browser/Docs.
2. **Writefull** (Word/Overleaf free tier) or **Trinka** — academic phrasing and journal style, where generic checkers go quiet.
3. **Quetext / PaperRater** (free tiers) — a plagiarism self-check *before* your institution's check. A match isn't automatically plagiarism; read the report.
4. **Zotero-style citations via QuillBot/EasyBib generators** — free citation formatting on the same accounts.
*Rule:* paraphrasing tools help you *learn* phrasing. Submitting paraphrased source text as your own writing is plagiarism with extra steps.

## The developer-docs stack (Markdown/LaTeX in git)
1. **Vale** in CI — style-guide rules (Microsoft/Google/your own) on every PR.
2. **cspell** or **typos** — spelling for code and docs, per-project dictionaries checked into the repo.
3. **Harper / LTeX+** in the editor — grammar as you type (LaTeX: LTeX+; everything else: Harper).
4. **textstat** in scripts — readability gates for docs changes, if your team wants them.
*Why this stack:* everything runs offline, in CI, with config in version control — no accounts, no per-seat anything.

## The ESL stack (writing in English as an additional language)
1. **LanguageTool** — strongest free multilingual safety net; explanations in your language in many locales.
2. **DeepL Write** — phrasing alternatives that teach you the idiomatic version, not just the corrected one.
3. **Ginger / Virtual Writing Tutor** — learner-focused feedback and rephrasing practice.
4. **Wordvice AI / Trinka** (free tiers) — when the writing becomes academic.
*Tip:* turn on explanations, not just fixes. The goal is needing the stack less every month.

## The privacy-max stack (sensitive drafts)
1. **Harper** (on-device) for in-editor checking.
2. **Self-hosted LanguageTool** for depth — your server, your logs (none, if you set it up that way).
3. **Espanso + local snippets** instead of cloud keyboards/predictors.
4. **No cloud checkers at all** — including the free ones. If a tool's business model isn't obvious, your text is part of it.
*Trade-off, honestly:* offline English accuracy still trails Grammarly's cloud models on subtle errors. This stack buys privacy with a small accuracy tax.

---
Every tool above is in the [catalog](../data/tools.json) with its `languages` and `data_processing` fields, so you can audit each stack or build your own with the picker.
