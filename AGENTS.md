# AGENTS.md — Research Wiki (Codex)

You are a **reading and drafting companion** for this research wiki. The wiki is primarily maintained by Claude (which handles ingestion, literature search, and structured workflows). Your role is to read existing wiki pages, answer questions from them, and draft new content that follows the established conventions.

The full agent schema — page conventions, frontmatter schemas, citation rules, cross-referencing style, log/index formats — is in `.claude/CLAUDE.md`. **Read it before writing any wiki page.** This file only adds Codex-specific guidance on top of it.

---

## What you can do

| Task | How |
|------|-----|
| Answer a research question | Read `wiki/index.md` → read relevant pages → synthesise with citations |
| Draft a concept or entity page | Follow the schemas in `.claude/CLAUDE.md`; save to `wiki/concepts/` or `wiki/entities/` |
| Draft an analysis page | Follow the Analysis schema; save to `wiki/analyses/` |
| Update an existing page | Read it first, then edit — always update the `updated:` frontmatter date |
| Add a glossary entry | Read `wiki/glossary.md` first; insert in alphabetical order |
| Lint the wiki | Scan for broken `[[wikilinks]]`, orphan pages, index gaps, frontmatter issues |

---

## What you should NOT do

- **Do not modify anything in `raw/`** — those files are immutable source documents.
- **Do not run literature searches or download papers** — that requires the Web of Science MCP and bioRxiv MCP, which are Claude-only infrastructure in this project.
- **Do not ingest new PDFs** — ingestion is a multi-step workflow (summarise → discuss → write source page → update concept/entity pages → update index and log) that Claude owns. You can draft pages from content the user pastes directly, but don't attempt to read and process raw PDFs autonomously.
- **Do not reformat or restructure existing wiki pages** unless explicitly asked — they follow deliberate conventions.

---

## How to answer a question from the wiki

1. Read `wiki/index.md` to find relevant pages.
2. Read those pages and synthesise a coherent answer.
3. Cite every claim with an inline `[[page-name]]` wikilink.
4. If the wiki doesn't cover something, say so clearly — don't fill gaps with unsourced claims.
5. Offer to save a substantial answer as a new analysis page at `wiki/analyses/<slug>.md`.

If you save an analysis page, also:
- Add it to `wiki/index.md` under `## Analyses`: `- [[slug]] — one-line description`
- Append to `wiki/log.md`:
  ```
  ## [YYYY-MM-DD] query | <short question title>
  Analysis page: wiki/analyses/<slug>.md
  Pages cited: <comma-separated list>
  Notes: <one sentence>
  ```

---

## How to draft a new wiki page

1. Read `wiki/index.md` to check whether a page already exists for this topic.
2. Read `.claude/CLAUDE.md` for the required frontmatter and section structure for that page type.
3. Read any closely related existing pages so your new page cross-links correctly.
4. Write the page, using `[[page-name]]` wikilinks on **first mention** of any concept or entity that has its own page.
5. Add the new page to `wiki/index.md` under the appropriate section.
6. Append to `wiki/log.md` with the correct entry type (see `.claude/CLAUDE.md` for log format).

---

## Key files to know

| File | Purpose |
|------|---------|
| `wiki/index.md` | Master catalog — read this first for any task |
| `wiki/log.md` | Append-only operation log — append after every write |
| `wiki/overview.md` | Field synthesis — update only for major conceptual shifts |
| `wiki/glossary.md` | Alphabetical term definitions |
| `wiki/concepts/` | One page per method, algorithm, or mathematical idea |
| `wiki/entities/` | One page per organism, tool, database, or model |
| `wiki/sources/` | One page per ingested paper (written by Claude after ingestion) |
| `wiki/analyses/` | Query answers and comparisons you write here |
| `.claude/CLAUDE.md` | Full agent schema — authoritative reference for all conventions |

---

## Style rules (summary — see CLAUDE.md for full detail)

- **Wikilinks:** `[[page-name]]` on first mention of any concept or entity with its own page.
- **Math:** LaTeX inline `$...$` — Obsidian renders this natively.
- **Citations:** `(source: filename.pdf)` after factual claims. Mark unsourced claims as needing verification.
- **Filenames:** lowercase with hyphens — e.g. `flux-variability-analysis.md`.
- **Contested claims:** use the Contested callout format defined in `.claude/CLAUDE.md`.
- **Never invent sources** — if you don't have evidence from an existing wiki page, say so.
