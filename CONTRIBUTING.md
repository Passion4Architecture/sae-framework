# Contributing to the SAE Framework

Thank you for helping build the future of software engineering! The framework lives in two places:

- **This repository** — README, license, diagrams, canonical overview.
- **The [Wiki](https://github.com/Passion4Architecture/sae-framework/wiki)** — the living, expandable playbook (Modules 1–5, toolkit, community pages).

Most content contributions belong in the Wiki; structural changes belong here.

## What we're looking for

- **Tooling & stacks** — new "Zero‑Ops" tools (UI generation, instant backends, QA agents), scored against the [Zero‑Ops scorecard](https://github.com/Passion4Architecture/sae-framework/wiki/Module-4:-The-Lean-SAE-Tech-Stack) → [Approved Zero‑Ops Tooling List](https://github.com/Passion4Architecture/sae-framework/wiki/Approved-Zero-Ops-Tooling-List).
- **Case studies** — real, solo, shipped‑to‑production stories. **We publish failures and limits, not just wins** → [Solo Production Case Studies](https://github.com/Passion4Architecture/sae-framework/wiki/Solo-Production-Case-Studies).
- **Spec templates** — reusable Markdown SDD templates → [SDD Spec Template](https://github.com/Passion4Architecture/sae-framework/wiki/SDD-Spec-Template).
- **Module refinement** — sharper explanations, diagrams, and honest **Reality Checks**.

## Contribution process

**Repository (README, license, diagrams):**
1. **Fork** the repository.
2. **Branch** for your change: `git checkout -b feature/sae-<topic>`.
3. **Commit** with clear, concise messages.
4. **Push** and open a **Pull Request** against `main`.

**Wiki (playbook content)** — the wiki is its own git repo:
```bash
git clone https://github.com/Passion4Architecture/sae-framework.wiki.git
# edit the .md files, then
git commit -am "Add <tool / case study / section>"
git push
```

## Style guide

- **Reduce human friction; maximize AI context hygiene.** Every addition should serve one of those two ends.
- **Earn your bold claims.** Pair strong assertions with an honest **Reality Check** that names the limits. The framework's credibility is its moat.
- **Avoid legacy PM jargon** (sprints, story points, standups) unless explicitly contrasting it.
- **Show, don't assert** — prefer tables, diagrams, code blocks, and worked examples over adjectives.
- **Keep wiki filenames ASCII** — use plain hyphens (`-`), never smart/Unicode hyphens, or sidebar links break.
- **Link generously** across pages to keep the playbook navigable.
