# Awesome Grammarly Alternative (Free) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated, verified directory of **free Grammarly alternatives** — grammar, spelling, style, and readability checkers with a genuinely usable free tier, plus open-source and offline tools you can run yourself. Every paid upsell is labeled; every free-tier limit we could confirm is stated, and entries we could not verify on an official source carry an honest `verified: false` flag in the machine-readable catalog ([`data/tools.json`](data/tools.json)).

Grammarly's free plan only covers basic grammar and spelling. This list exists for the other 90%: multilingual checking (LanguageTool, 30+ languages), privacy-first offline checking (Harper, Vale), readability scoring (Hemingway), academic writing (Trinka, Writefull), and the checkers already built into Google Docs, Microsoft Edge, and LibreOffice — all $0.

## Contents

- [Grammar & Style Checkers (Free Tier)](#grammar-style-checkers-free-tier)
- [Open Source & Offline](#open-source-offline)
- [Readability & Clarity](#readability-clarity)
- [Academic & Student Writing](#academic-student-writing)
- [Already Built In (Free)](#already-built-in-free)
- [Guides](#guides)
- [Contributing](#contributing)
- [License](#license)

---

## Grammar & Style Checkers (Free Tier)

Web and extension checkers that catch grammar, spelling, punctuation, and style as you write. Every entry here has a usable free tier; limits are stated honestly in the catalog.

| Name | Org | What it does | Free model / License | OSS |
|---|---|---|---|---|---|
| [LanguageTool](https://languagetool.org/) | LanguageTool | Open-source writing assistant that checks grammar, spelling, punctuation, and style in 30+ languages via browser extensions, editor add-ons, and a web editor. | LGPL-2.1 (open-source core); freemium cloud | Yes |
| [QuillBot](https://quillbot.com/) | QuillBot (Course Hero) | AI writing platform whose free Grammar Checker fixes grammar, spelling, and punctuation, alongside a paraphraser, summarizer, and citation generator. | Freemium (free tier) | No |
| [ProWritingAid](https://prowritingaid.com/) | ProWritingAid | Writing editor with 25+ reports on grammar, style, readability, pacing, and overused words, aimed at long-form writers and authors. | Freemium (free tier) | No |
| [Ginger](https://www.gingersoftware.com/) | Ginger Software | Grammar and spelling checker with sentence rephrasing, synonyms, translation, and a personal trainer for English learners. | Freemium (free tier) | No |
| [Sapling](https://sapling.ai/) | Sapling.ai | AI writing assistant for customer-facing teams, with grammar and spelling checks, autocomplete, snippets, and CRM/helpdesk integrations. | Freemium (free tier) | No |
| [Linguix](https://linguix.com/) | Linguix | AI writing assistant that checks grammar, punctuation, and style across the web, with paraphrasing and productivity stats. | Freemium (free tier) | No |
| [Scribens](https://www.scribens.com/) | Scribens | Free web grammar, spelling, and punctuation checker for English and French with detailed explanations of each correction. | Free (premium upsell) | No |
| [Outwrite](https://www.outwrite.com/) | Outwrite | AI proofreader that checks spelling, grammar, style, and plagiarism, with paraphrasing and eloquence suggestions. | Freemium (free tier) | No |
| [Wordvice AI](https://www.wordvice.ai/) | Wordvice | AI proofreader and paraphraser aimed at academic and ESL writers, with proofreading modes for essays, research papers, and business documents. | Freemium (free tier) | No |
| [SentenceCheckup](https://sentencecheckup.com/) | SentenceCheckup | Free web tool that checks sentences for grammar, spelling, punctuation, and word-choice errors and suggests rephrased alternatives. | Free (ad-supported) | No |
| [TextGears](https://textgears.com/) | TextGears | Grammar, spelling, and readability checking API with a free tier, for developers who want to embed proofreading in their own apps. | Freemium API (free tier) | No |
| [Reverso Grammar Checker](https://www.reverso.net/spell-checker/english-spelling-grammar/) | Reverso | Free spelling and grammar checker for English and French, integrated with Reverso's dictionary, conjugation, and translation tools. | Free (ad-supported) | No |
| [OnlineCorrection.com](https://www.onlinecorrection.com/) | OnlineCorrection.com | Free web page that checks English text for spelling, grammar, and style errors and suggests corrections inline. | Free (ad-supported) | No |
| [EasyBib Grammar Checker](https://www.easybib.com/grammar-and-plagiarism) | EasyBib (Chegg) | Free grammar and plagiarism checker from the citation-generator service, aimed at students writing essays and papers. | Freemium (free tier) | No |
| [DeepL Write](https://www.deepl.com/en/write) | DeepL | AI writing companion that fixes grammar and punctuation and offers alternative phrasing, style, and tone suggestions in 9 languages. | Freemium (free tier) | No |
| [Wordtune](https://www.wordtune.com/) | AI21 Labs | AI rewriting assistant that suggests alternative phrasings, tone changes (formal/casual), and shorten/expand rewrites for selected sentences. | Freemium (free tier) | No |

## Open Source & Offline

Free and open-source checkers you can run locally or self-host. Your text never leaves your machine — the privacy-first answer to Grammarly.

| Name | Org | What it does | Free model / License | OSS |
|---|---|---|---|---|---|
| [Harper](https://github.com/Automattic/harper) | Automattic | Offline, privacy-first English grammar checker written in Rust; runs locally in browsers, VS Code, Obsidian, and other editors in milliseconds. | Apache-2.0 | Yes |
| [LanguageTool Server (self-hosted)](https://github.com/languagetool-org/languagetool) | LanguageTool | Self-hosted LanguageTool server: the open-source core grammar checker you run on your own infrastructure, with no per-request limits. | LGPL-2.1 | Yes |
| [Vale](https://github.com/vale-cli/vale) | Vale (vale-cli) | Command-line prose linter that checks Markdown and other docs against style-guide rules (Microsoft, Google, write-good, proselint and custom rules). | MIT | Yes |
| [Grammalecte](https://grammalecte.net/) | Grammalecte | French grammar, spelling, and typography checker for LibreOffice, Firefox, Thunderbird, and the command line. | GPL-3.0 | Yes |
| [LTeX+](https://github.com/ltex-plus/ltex-ls-plus) | ltex-plus | Grammar and spell checking for LaTeX and Markdown in VS Code and other LSP editors, powered by LanguageTool, with offline support. | EPL-2.0 / MPL-2.0 (see repo) | Yes |
| [TeXidote](https://github.com/sylvainhalle/textidote) | Sylvain Hallé | Command-line grammar, spelling, and style checker for LaTeX documents that strips LaTeX commands before checking the prose. | GPL-3.0 | Yes |
| [write-good](https://github.com/btford/write-good) | btford | Naive JavaScript linter for English prose that flags passive voice, weasel words, lexical illusions, and overly complex phrasing. | MIT | Yes |
| [alex](https://github.com/get-alex/alex) | get-alex | Catch insensitive, inconsiderate writing: a Markdown prose linter that flags gendered, polarizing, race-related, and otherwise exclusionary language. | MIT | Yes |
| [proselint](https://github.com/amperser/proselint) | amperser | Linter for English prose aggregating advice from classic style guides (Strunk & White, Pinker, Butterick and others) into automated checks. | BSD-3-Clause (see repo) | Yes |
| [RedPen](https://github.com/redpen-cc/redpen) | redpen-cc | Document checker for English and Japanese that validates sentence length, terminology consistency, symbols, and expression styles. | Apache-2.0 | Yes |
| [cspell](https://github.com/streetsidesoftware/cspell) | Streetside Software | Spell checker for code and docs that understands camelCase, snake_case, and technical vocabularies, with custom dictionaries per project. | MIT | Yes |
| [typos](https://github.com/crate-ci/typos) | crate-ci | Fast Rust spell checker for source code and docs that finds and fixes typos with low false positives, designed for CI. | MIT OR Apache-2.0 | Yes |

## Readability & Clarity

Tools that score and improve readability rather than grammar: complex sentences, passive voice, and reading level. Free web versions or libraries.

| Name | Org | What it does | Free model / License | OSS |
|---|---|---|---|---|---|
| [Hemingway Editor](https://hemingwayapp.com/) | Hemingway | Readability editor that highlights complex sentences, passive voice, adverbs, and hard-to-read phrases, with a readability grade score. | Free web version; paid desktop/Plus | No |
| [Slick Write](https://www.slickwrite.com/) | Slick Write | Free web editor that checks grammar, flow, passive voice, adverb use, and readability statistics for pasted text. | Free (ad-supported) | No |
| [Readable](https://readable.com/) | Readable (ConnectedText) | Readability scoring tool that grades text with Flesch-Kincaid, Gunning Fog, SMOG and other formulas, plus keyword and sentiment analysis. | Freemium (free tier) | No |
| [WebFX Readability Tool](https://www.webfx.com/tools/read-able/) | WebFX | Free web page that scores the readability of pasted text or a URL with Flesch-Kincaid, Gunning Fog, SMOG, Coleman-Liau, and ARI scores. | Free | No |
| [Datayze Readability Analyzer](https://datayze.com/readability-analyzer) | Datayze | Free readability analyzer that scores text with several formulas and highlights hard sentences, passive voice, and complex words. | Free (ad-supported) | No |
| [textstat](https://github.com/textstat/textstat) | textstat contributors | Python library for computing readability statistics (Flesch-Kincaid, Gunning Fog, SMOG, Coleman-Liau, ARI, Dale-Chall and more) in your own code. | MIT | Yes |

## Academic & Student Writing

Checkers built for essays, theses, and journal manuscripts, with free tiers or free student tools.

| Name | Org | What it does | Free model / License | OSS |
|---|---|---|---|---|---|
| [Trinka](https://www.trinka.ai/) | Trinka (Enago) | AI writing assistant built for academic and technical writing, checking grammar, tone, and journal style-guide consistency (AMA, APA, AGU and more). | Freemium (free tier) | No |
| [Writefull](https://www.writefull.com/) | Writefull | AI academic writing tool trained on research papers, offering sentence revising, paraphrasing, and title/abstract generation in Word and Overleaf. | Freemium (free tier) | No |
| [Paperpal](https://paperpal.com/) | Paperpal (Cactus Communications) | AI academic writing assistant that checks language, suggests edits, and helps prepare manuscripts for journal submission. | Freemium (free tier) | No |
| [PaperRater](https://www.paperrater.com/) | PaperRater | Free student tool that checks grammar, spelling, word choice, and plagiarism, with readability scoring for essays and papers. | Freemium (free tier) | No |
| [Virtual Writing Tutor](https://virtualwritingtutor.com/) | Virtual Writing Tutor | Free ESL-focused checker that counts words, checks grammar, spelling, and vocabulary, and gives targeted feedback for English learners. | Free | No |
| [Scribbr Grammar Checker](https://www.scribbr.com/grammar-checker/) | Scribbr | Free online grammar checker from the academic proofreading service, checking grammar, spelling, and punctuation in essays and theses. | Free tool (paid proofreading upsell) | No |
| [Quetext](https://www.quetext.com/) | Quetext | Plagiarism checker with a free basic plan, plus grammar checking and citation assistance for students and teachers. | Freemium (free tier) | No |

## Already Built In (Free)

Writing help already included in the browser, office suite, or OS you use — $0 because you already have it.

| Name | Org | What it does | Free model / License | OSS |
|---|---|---|---|---|---|
| [Microsoft Editor](https://www.microsoft.com/en-us/microsoft-365/microsoft-editor) | Microsoft | Writing assistant built into Microsoft Edge and available as a browser extension, with free basic spelling and grammar checks. | Free basic tier (Microsoft 365 upsell) | No |
| [Google Docs spelling & grammar suggestions](https://support.google.com/docs/answer/57859) | Google | Built-in spelling, grammar, and style suggestions in Google Docs (and Gmail), free with a Google account. | Free with Google account | No |
| [LibreOffice Writer](https://www.libreoffice.org/) | The Document Foundation | Free, open-source office suite whose Writer includes spell checking and can run LanguageTool and other grammar extensions offline on the desktop. | GPL / LGPL (free and open source) | Yes |
| [ONLYOFFICE Docs](https://www.onlyoffice.com/) | ONLYOFFICE | Free office suite (desktop and self-hosted) with spell checking and plugin support, usable as a no-subscription Docs/Word alternative. | AGPL-3.0 (Community Edition) | Yes |

## Guides

- [Choosing a free checker](docs/choosing-a-checker.md) — which category fits your writing (email, essays, code docs, multilingual, private drafts).
- [Free-tier limits, honestly](docs/free-tier-limits.md) — what each free tier actually caps (words, paraphrases, reports) and when paying is genuinely worth it.
- [Self-hosting & offline](docs/self-hosting-and-offline.md) — running LanguageTool, Harper, Vale and friends locally, and pointing extensions at your own server.
- [Glossary](docs/glossary.md) — grammar checker vs prose linter vs readability score, free tier vs freemium, and friends.
- [Status changes](docs/status-changes.md) — rebrands, shutdowns, and pricing-model changes, newest first.
- [Machine-readable catalog](data/tools.json) — every entry with pricing/license, open-source, and verification flags.

## Contributing

Entries and corrections are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Every PR is checked by CI: lychee link check over all markdown files (also re-run monthly to catch link rot) and JSON validation of `data/tools.json`, including the exact field set and category values documented in CONTRIBUTING.md.

## License

[MIT](LICENSE) © 2026 dakotac1994
