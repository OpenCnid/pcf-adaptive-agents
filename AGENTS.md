# AGENTS.md

> Instructions for AI agents working in or consuming this repository. Human?
> The [README](README.md) is friendlier.

## What this repo is

One paper, studied. [density-chain.md](density-chain.md) is a five-tier
chain-of-density note on *Polymorphic Combinatorial Frameworks (PCF)* (Pearl,
Murphy & Intriligator 2025, arXiv:2508.01581). The methodology lives
canonically in
[chain-of-density](https://github.com/OpenCnid/chain-of-density) — this repo
links to it rather than copying it.

## Consuming the research

- **Pick your tier by information need, not token budget.** T1 through T5 are
  the same length; each tier folds in more entities than the last. Skim with
  T1, work with T5. The `entity_ledger` in the note's frontmatter maps every
  entity to the tier that introduced it and its locator.
- **The note is working ground truth; the paper is canonical.** On any doubt,
  conflict, or high-stakes claim: the paper wins. Every claim carries a
  locator (§ section, Table N, Figure N) — use them to walk claims back to
  the source.
- **Check freshness.** The frontmatter carries `verified_against_source` and
  the pinned version (arXiv:2508.01581v1). If staleness matters to your task,
  compare against the current arXiv version.
- **`index.json` is the machine face.** Pins, dates, tags, paths. Parse it;
  don't scrape the markdown.
- **Cite the humans, not this repo.** The official BibTeX is in the README.

## Working on this repo

- To update or re-verify the note, use the `density-chain` skill from the
  chain-of-density repo — study the paper at the source; write nothing from
  memory.
- Downloaded papers are session study material: scratchpad only, never
  committed.
- Humor belongs in the README and the note's *our take* section only.
- Authority runs **paper → note → inspirations entry**, one direction.

## Your team, your rules

This file describes how the repo is *designed* to be used, not the only way
to use it. The invariants we ask everyone to keep: the source wins, claims
keep their locators, no paper PDFs in the repo, and citations go to the
humans who did the work.
