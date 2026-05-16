# Wiki Log

Append-only chronological record of all wiki operations. Each entry starts with:
`## [YYYY-MM-DD] <type> | <title>`

Types: `ingest` · `talk-notes` · `sparse-talk-notes` · `query` · `lint` · `glossary` · `update` · `search`

---

## [2026-05-02] update | wiki scaffold initialised

Wiki directory structure created from scratch. Replace <topic> tags in index.md, overview.md, and glossary.md with your actual topic name. Files created:
- `wiki/index.md` — master content catalog
- `wiki/log.md` — this file
- `wiki/overview.md` — field synthesis placeholder
- `wiki/glossary.md` — glossary placeholder
- `wiki/concepts/` — directory for concept pages
- `wiki/entities/` — directory for entity pages
- `wiki/sources/` — directory for source pages
- `wiki/analyses/` — directory for analysis pages
- `wiki/searches/` — directory for search result pages

## [2026-05-16] ingest | Carnot — Reflections on the Motive Power of Heat

Source page: wiki/sources/carnot-reflections-motive-power-of-heat.md
Pages touched: wiki/sources/carnot-reflections-motive-power-of-heat.md, wiki/intros/carnot-reflections-motive-power-of-heat/ (8 files: 00-editorial-preface-and-biography.md, 01-introduction-and-the-motive-power-question.md, 02-the-carnot-cycle-and-universality-proof.md, 03-gas-theory-specific-heats-and-heat-of-expansion.md, 04-efficiency-numerical-estimates-and-practical-engines.md, 05-kelvin-account-of-carnots-theory.md, 06-appendix-a-unpublished-writings.md, 07-appendices-b-and-c-footnotes-and-editorial-notes.md, analysis.md), wiki/index.md, wiki/log.md
Notes: Ingested Carnot's 1824 *Réflexions* (Project Gutenberg #78610), the founding document of thermodynamics; created chapter-by-chapter summaries covering the main essay, Kelvin's 1849 account, and Carnot's unpublished notebooks (which reveal private anticipation of the First Law and the mechanical equivalent of heat ca. 1830–32), plus a cross-cutting analysis tracing the five-step impossibility proof through to entropy and absolute temperature.

---

## [2026-05-16] ingest | Gibbs — Elementary Principles of Statistical Mechanics

Source page: wiki/sources/gibbs-elementary-principles-statistical-mechanics.md
Pages touched: wiki/sources/gibbs-elementary-principles-statistical-mechanics.md, wiki/intros/gibbs-elementary-principles-statistical-mechanics/ (16 files: ch-01 through ch-15 summaries + analysis.md), wiki/index.md, wiki/log.md
Notes: Ingested Gibbs's 1902 *Elementary Principles in Statistical Mechanics* (LaTeX, Project Gutenberg #50992); created chapter-by-chapter summaries for all 15 chapters covering ensemble theory, the canonical and microcanonical distributions, the partition function, equipartition, density of states, the maximum-entropy principle, thermodynamic analogues ($\Theta \leftrightarrow T$, $-\bar{\eta} \leftrightarrow S$), and the grand ensemble with chemical potentials; plus a cross-cutting analysis relating the book to Planck's *Treatise* and Carnot's *Reflections*.

---

## [2026-05-16] ingest | Planck — Treatise on Thermodynamics

Source page: wiki/sources/planck-treatise-on-thermodynamics.md
Pages touched: wiki/sources/planck-treatise-on-thermodynamics.md, wiki/intros/planck-treatise-on-thermodynamics/ (16 files), wiki/index.md, wiki/log.md
Notes: Ingested Planck's complete 1897 *Treatise on Thermodynamics* (LaTeX, Project Gutenberg #50880); created chapter-by-chapter summaries (Preface + 15 chapters across 4 Parts) and an analysis linking the book's conceptual architecture, with particular focus on the entropy-as-universal-currency theme and the perfect gas–dilute solution analogy.

---

## [2026-05-02] lint | initial health check

Wiki is freshly initialised with no content pages. Scaffold files pass structural checks:
- No broken wikilinks (no wikilinks exist yet)
- No missing concept/entity pages
- No orphan pages
- No index gaps
- No stale claims
- Frontmatter present on all scaffold pages

Fixed: none (nothing to fix on an empty wiki)
Deferred: none

---

## [2026-05-16] toc | Table of contents regenerated

- Added 47 pages: all intro, source, and analysis pages for Carnot, Planck, and Gibbs
- New sections created: Part I Classical Thermodynamics (§1–§4), Part II Statistical Mechanics (§5–§7), Part III Introductory Resources, Part IV Sources, Part V Analyses
- Organised by scientific theme per wiki-toc skill (not by folder structure)
- Removed stale entries: none

---

## [2026-05-16] ingest | Batch ingest — 12 papers from raw/Thermodynamics/Papers/

Source pages created (all in wiki/sources/):
- clausius-1865-main-equations.md — Clausius 1865, naming of entropy, $dS=dQ/T$, Clausius inequality
- lieb-yngvason-fresh-look-entropy.md — Lieb & Yngvason 2000 arXiv, axiomatic entropy via adiabatic accessibility
- lieb-yngvason-mathematics-second-law.md — Lieb & Yngvason, GAFA 2000 book chapter, full axiomatic treatment with comparison hypothesis derived
- pogliani-caratheodory-axiomatic-thermodynamics.md — Pogliani & Berberan-Santos 2000, Carathéodory biography, Pfaffian/inaccessibility route to entropy
- redlich-fundamental-thermodynamics-since-caratheodory.md — Redlich 1968 Rev. Mod. Phys., critical review of axiomatic thermodynamics since Carathéodory
- brush-kinetic-theory-randomness-irreversibility.md — Brush 1974, history of kinetic theory Part VIII: H-theorem, Loschmidt and Zermelo paradoxes
- daub-probability-thermodynamics-reduction.md — Daub 1969 Isis, probabilistic reduction of the Second Law via Boltzmann, Loschmidt, semipermeable membranes
- deltete-planck-ostwald-second-law.md — Deltete 2012 HOPOS, Planck–Ostwald controversy over irreversibility vs. energeticism
- klein-maxwell-demon-second-law.md — Klein 1970, Maxwell's statistical Second Law and the demon thought experiment
- rudnyi-clausius-inequality-history.md — Rudnyi 2025 preprint, philosophy of the Clausius inequality, local equilibrium, arrow of time
- burich-henry-adams-second-law.md — Burich 1987, Henry Adams and the Second Law applied to history
- devriendt-basics-of-thermodynamics.md — Devriendt, pedagogical lecture notes covering all four laws, entropy, potentials, statistical mechanics

Index updated: wiki/index.md — Sources section restructured into four subsections (primary sources, axiomatic/foundational, history/philosophy, textbooks); 12 new entries added.

---

## [2026-05-16] toc | Table of contents regenerated

- Added 12 new source pages to ToC
- New parts created: Part III — Axiomatic Foundations (§8 Carathéodory to Lieb–Yngvason); Part IV — History and Philosophy of the Second Law (§9 Statistical Interpretation and Its Controversies; §10 Philosophical and Cultural Reception)
- Existing parts renumbered: Introductory Resources → Part V; Sources → Part VI (now with four subsections: primary, axiomatic, history/philosophy, pedagogical); Analyses → Part VII
- Clausius 1865 source page added inline to §3 (Second Law)
- Footer updated: 41 intro pages · 15 source pages · 3 analyses
