# Analysis Notes (cross-reference)

This branch was used as a read-only analysis target. The full deep-dive lives in the sibling repo:

**`0x0079/vscode-tingly-i18n` @ branch `claude/analyze-i18n-ally-lgZJL` → `docs/i18n-ally-analysis/`**

The 9-part write-up covers:

1. Top-level architecture and event bus (`src/extension.ts`, `core/Global.ts`, `core/Config.ts`)
2. Framework adapters and key detection (`src/frameworks/*`, `core/KeyDetector.ts`, `core/Analyst.ts`)
3. Loaders and parsers (`core/loaders/*`, `parsers/*`)
4. UI/UX layer (`editor/*`, `views/*`, `webview/panel.ts`)
5. Hard-string detection and extraction (`extraction/*`, `commands/extractString.ts`)
6. Translation engines and review system (`core/Translator.ts`, `core/Review.ts`, `translators/*`)
7. Pain points (P1–P3, ranked by user-observable severity)
8. tingly-i18n's improvement directions (UI/UX, program analysis, VS Code integration)
9. Phased roadmap

Anchor commit analyzed: `4c504c93cec6c4697134eca379f1476d0eb1c9f6`.

No source files in this repository were modified.
