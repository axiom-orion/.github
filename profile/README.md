# axiom-orion

Small, sharp engineering pieces — each built to make **one failure mode measurable**, then measure it honestly. Eval-driven, CPU-only where it can be, reproducible by anyone: where a repo makes a numeric claim, that number is produced by its `eval/run_eval.py`, **not asserted**. Where a piece is shipped craft rather than a measured claim, it's labelled as such — never dressed up in a metric no eval produces.

These are the public, reproducible demonstrations behind [**Vorion**](https://github.com/vorionsys) — a governed-AI execution platform shipped as the open-source `@vorionsys/*` packages, where the same discipline (governance loops, provenance, measured claims) becomes infrastructure for autonomous agents.

## Projects

| Repo | The claim it turns into a number |
|---|---|
| [**governed-agents**](https://github.com/axiom-orion/governed-agents) · [live](https://governed-agents.vercel.app) | A governed multi-agent loop — Researcher → Reasoner → **policy gate** → execute-or-halt. Watch it **allow one action and block another** (an unverified external send) with a logged rationale, streamed live to a trace UI. |
| [**agent-memory-service**](https://github.com/axiom-orion/agent-memory-service) · [live](https://agent-memory-service-voiwkzrlma-uc.a.run.app) | "Append everything to a vector store" memory returns **stale facts** when facts change. A flat store answers current-fact queries right **0%** of the time; the full memory service reaches **100%** with **0%** staleness. |
| [**art-director**](https://github.com/axiom-orion/art-director) | Most of "good design" we call subjective is **checkable**. Single-shot generation passes WCAG AA contrast on **12%** of text pairings; the same generator inside a critic loop reaches **92%**. |
| [**genealogy-graphrag**](https://github.com/axiom-orion/genealogy-graphrag) | Dense + lexical retrieval **can't answer relational questions** ("maternal grandfather of X?"). Adding kinship-graph resolution takes relational recall@5 from **0.000 → 1.000**, no regression elsewhere. |
| [**cason-heritage**](https://github.com/axiom-orion/cason-heritage) · [flcason.com](https://flcason.com) | Shipped craft: eleven generations of one family as an interactive genealogy — SVG family tree, migration map, timeline, and a sourced evidence board — served as a static site. *(Shipped site, not a measured claim.)* |
| [**brainmix**](https://github.com/axiom-orion/brainmix) | Browser-native discipline, shipped: a full neuroacoustic DJ studio — dual-deck Web Audio engine, BPM detection, live rooms and WAV export — running entirely client-side in **Next.js**, no plugin and no DAW. *(Shipped app, not a measured claim — no eval number is asserted.)* |
| [**gigtrip**](https://github.com/axiom-orion/gigtrip) | A live-events trip-planning app: pull tour, comedy and sports dates from live feeds, map them, and organise a group trip around the ones you care about. *Insight on the roadmap: planning a trip around events is **constrained optimisation, not a sort** — but the preference-weighted optimiser and its eval aren't built yet, so no lift number is claimed.* |

## The through-line

Each repo takes a claim that usually gets hand-waved — *"our memory is smart," "the design looks good," "retrieval works"* — turns it into a reproducible number, and reports the lift honestly (what's measured vs. aspirational, stated plainly). When a piece is shipped craft rather than a measured claim, it earns its place on the strength of what it actually does — not a borrowed metric. Generate-then-critique loops, provenance and audit trails, and disciplined scoping are the same principles the [**Vorion**](https://github.com/vorionsys) governance platform applies to autonomous agents.

Built by **Ryan Cason** — AI systems builder ([@vorionsys](https://github.com/vorionsys)).
