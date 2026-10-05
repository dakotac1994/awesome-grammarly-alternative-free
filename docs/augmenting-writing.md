# Augmenting writing: predict, expand, draft

Everything else in this repo **corrects** text that already exists. This part is about tools that help the text come into existence faster — the difference Cotypist's maker calls *"augmenting your writing, not replacing it."*

## The four augmenting modes

### 1. Predictive autocomplete — the tool guesses your next words
You type; it offers the continuation inline; Tab accepts. The good ones suggest *your* words, not generic AI prose.
- **Everywhere on Mac, on-device:** [Cotypist](https://cotypist.app/) (System-wide section) — Gemma on your Mac, free plan.
- **In Gmail:** Smart Compose — Tab-accept phrases as you compose; free with Gmail.
- **On your phone:** [Microsoft SwiftKey](https://www.microsoft.com/en-us/swiftkey) and [Typewise](https://www.typewise.app/) (System-wide) — prediction tuned per language.
- Try this first if your bottleneck is *typing speed on repetitive text* (status updates, scheduling, follow-ups).

### 2. Snippets & text expansion — your own phrases, on a trigger
You define `;sig`, `;intro`, `;pricing-faq`; the tool expands them anywhere. No AI, no guessing — pure leverage on text you write every week.
- **Free & open-source, everywhere:** [Espanso](https://github.com/espanso/espanso) (Win/Mac/Linux, YAML config, forms & scripts).
- **Windows, GUI-first:** [Beeftext](https://github.com/xmichelo/Beeftext); **programmable:** [AutoHotkey](https://www.autohotkey.com/) hotstrings.
- **Browser/support work:** [Text Blaze](https://blaze.today/) — snippets with fill-in forms and calculations, built for Gmail/helpdesk replies.
- **Already in your launcher:** [Raycast Snippets](https://www.raycast.com/core-features/snippets) (free core). Refine (System-wide) ships snippets too, with a global Snippet Picker.
- Rule of thumb: give every trigger a deliberate prefix (`;` or `//`) so expansions never fire mid-word.

### 3. AI continuation & drafting — unstick the paragraph
You have half a sentence and no next one. These draft *with* you inside the document:
- **[Lex](https://lex.page/)** — a minimal editor whose AI continues, reworks, and gives feedback in place.
- **[Apple Writing Tools](https://support.apple.com/guide/mac-help/writing-tools-write-improve-summarize-mchldcd6c260/mac)** (Built-in Free) — Rewrite tones and Compose on supported devices, in most apps.
- **[Wordtune](https://www.wordtune.com/) / [DeepL Write](https://www.deepl.com/en/write)** (Grammar Checkers) — sentence-level alternatives when the draft exists but reads wrong.
- Keep the human in charge: continuation is best treated as a *suggestion engine for your first draft*, then edited like anything else.

### 4. Voice drafting (adjacent — know it exists)
Dictation is augmenting too: speak the draft, then correct it. Modern options (macOS/iOS built-in Dictation, Windows Voice Typing, dedicated apps like Wispr Flow) pair naturally with everything above: **dictate → augment → correct**. Dedicated dictation apps are tracked in the speech lists of the Awesome-llms-labs family rather than here; the built-in OS dictation you already have is the $0 starting point.

## How to stack augmenting + correcting

```
Draft (augment)  →  Structure (readability)  →  Correct (grammar)  →  Send
Cotypist/Espanso    Hemingway                   LanguageTool/Harper
Lex/Smart Compose                               Refine-class inline
```

1. **Draft with augmenting tools** — autocomplete for speed, snippets for the repetitive 20%, continuation only when stuck.
2. **One readability pass** — Hemingway or Readable; cut the sentences the autocomplete made too long.
3. **One correction pass** — your checker of choice (see [choosing-a-checker](choosing-a-checker.md)). Autocomplete and expansion *introduce* their own errors (wrong expansion, stale snippet text), so the corrector always goes last.

## Privacy note (read this before installing five of these)

Autocomplete, prediction, and expansion tools see **everything you type, in every app** — that's how they work. Prefer, in order:
1. **On-device / local config** — Espanso, Beeftext, Cotypist: your keystrokes and snippet library never leave the machine.
2. **Your own key (BYOK)** — Refine-class apps sending text only to a provider you chose.
3. **Cloud prediction** — Smart Compose, SwiftKey, Lex: convenient, but your writing is processed on the vendor's servers under their policy. Check the policy before using them on sensitive drafts.
