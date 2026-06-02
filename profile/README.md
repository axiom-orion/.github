# axiom-orion

Small, sharp engineering pieces — each built to make **one failure mode measurable**, then measure it honestly. Eval-driven, CPU-only where it can be, reproducible by anyone: the numbers in each repo are produced by its `eval/run_eval.py`, **not asserted**.

These are the public, reproducible demonstrations behind [**Vorion**](https://github.com/vorionsys) — a governed-AI execution platform shipped as the open-source `@vorionsys/*` packages, where the same discipline (governance loops, provenance, measured claims) becomes infrastructure for autonomous agents.

## Projects

| Repo | The claim it turns into a number |
|---|---|
| [**agent-memory-service**](https://github.com/axiom-orion/agent-memory-service) · [live](https://agent-memory-service-voiwkzrlma-uc.a.run.app) | "Append everything to a vector store" memory returns **stale facts** when facts change. A flat store answers current-fact queries right **0%** of the time; the full memory service reaches **100%** with **0%** staleness. |
| [**art-director**](https://github.com/axiom-orion/art-director) | Most of "good design" we call subjective is **checkable**. Single-shot generation passes WCAG AA contrast on **12%** of text pairings; the same generator inside a critic loop reaches **92%**. |
| [**genealogy-graphrag**](https://github.com/axiom-orion/genealogy-graphrag) | Dense + lexical retrieval **can't answer relational questions** ("maternal grandfather of X?"). Adding kinship-graph resolution takes relational recall@5 from **0.000 → 1.000**, no regression elsewhere. |
| [**cason-heritage**](https://github.com/axiom-orion/cason-heritage) · [flcason.com](https://flcason.com) | Zero-framework discipline, shipped: eleven generations of one family as a **single self-contained HTML file**. |

## The through-line

Each repo takes a claim that usually gets hand-waved — *"our memory is smart," "the design looks good," "retrieval works"* — turns it into a reproducible number, and reports the lift honestly (what's measured vs. aspirational, stated plainly). Generate-then-critique loops, provenance and audit trails, and disciplined scoping are the same principles the [**Vorion**](https://github.com/vorionsys) governance platform applies to autonomous agents.

Built by **Ryan Cason** — AI systems builder ([@vorionsys](https://github.com/vorionsys)).
