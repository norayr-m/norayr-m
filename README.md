# Norayr Matevosyan

**Mathematician.** Free boundary problems · high-performance computation on Apple GPUs · graph databases · applications to biological digital twins. Chicago.

PhD, KTH Stockholm (2003) — *Tangential touch between free and fixed boundaries*, advisor Henrik Shahgholian. Postdoctoral work at the University of Vienna and the University of Cambridge.

- *Almost monotonicity formulas for elliptic and parabolic operators with variable coefficients* — **Comm. Pure Appl. Math.**, 2011
- *A two-phase semilinear free boundary problem with degenerate phase* — **Calc. Var. PDE**, 2011
- [Google Scholar](https://scholar.google.com/citations?user=qV1NHwkAAAAJ) · [Mathematics Genealogy](https://www.mathgenealogy.org/id.php?id=83126)

---

## Current work — three repositories with measured results

**[Savanna Engine](https://github.com/norayr-m/savanna-engine)** — large-scale spatial lattice engine on Apple Metal. **15.8 billion cell-updates per second** at 64M cells on one M5 Max laptop, 10-run validated ([benchmark methodology](https://github.com/norayr-m/savanna-engine/blob/main/BENCHMARK.md)); one tiled existence run at 100 billion cells. Lock-free parallelism by 7-colouring, Morton Z-curve layout, lossless delta recording. [White paper](https://norayr-m.github.io/savanna-engine/whitepaper.html) · [1B-cell playback](https://norayr-m.github.io/savanna-engine/playback.html)

**[DagDB Engine](https://github.com/norayr-m/dagdb-engine)** — a 6-bounded ranked DAG database on Apple Silicon: every node a 64-bit programmable lookup table, ternary state, acyclic by construction. Daemon with zero-copy shared memory, PostgreSQL extension, **210 tests green on a clean checkout**, 0.71 GCUPS at 1M nodes. [Architecture](https://github.com/norayr-m/dagdb-engine/blob/main/ARCHITECTURE.md) · [Presentation](https://norayr-m.github.io/dagdb-engine/site/index.html)

**[Isomorphic Walk](https://github.com/norayr-m/isomorphic-walk)** — graph walks on protein contact networks, with pre-registered acceptance gates. Result: contact-graph tubes recover published allosteric-pathway residues better than a straight-line baseline in 6 of 7 systems (median ΔF1 +0.07; absolute agreement is low, median F1 0.18, and the README says so). Includes a printed REJECT of the spectral-walk hypothesis.

*All three are personal, amateur engineering projects: single laptop, no controlled benchmarks, no competitive claims. Numbers are stated with what was and was not measured.*

---

## Research directions

**Free boundary problems** — tangential touch, almost-monotonicity formulas for operators with variable coefficients, two-phase problems with degenerate phase.

**Distributed reconstruction** — how a family of partial observers, each with a projection and a completion back to the global state, aggregates. An earlier norm-growth formulation has been retracted; the current claim is conditional (bounded computational budget, four explicit hypotheses). Work in progress.

**Sparse attention by geometry** — self-similar hexagonal hierarchies where the hubs are forced by curvature (Euler's twelve pentagonal defects, pentagons as the only defect), every softmax pool stays at seven or fewer, and a route between two nodes is computed from their two addresses alone. One sealed result: forced defects beat at least 90% of random engineered anchor placements and are unbeaten on algebraic connectivity by the best of fifty. Work in progress; the repository opens on my word.

**Graph computation on GPUs** — bounded-degree graph engines where every node executes a local rule; the substrate for the two engines above and the intended path to tissue-scale biological twins.

---

## Demonstrations (archived)

Browser demos from the March–June 2026 exploration of the distributed-reconstruction ideas — Bach's BWV 847 as a navigable graph, a 7-column generator/scanner pair, cellular automata on graph topology, an orbital solver, a ternary tetrahedral lattice. Archived and read-only; each carries its own retraction note. [drt-generator](https://github.com/norayr-m/drt-generator) · [drt-scanner](https://github.com/norayr-m/drt-scanner) · [drt-cell-simulator](https://github.com/norayr-m/drt-cell-simulator) · [drt-pipeline](https://github.com/norayr-m/drt-pipeline) · [decoder-of-the-encoder](https://github.com/norayr-m/decoder-of-the-encoder) · [interstellar-harmony](https://github.com/norayr-m/interstellar-harmony) · [drt-orbital-solver](https://github.com/norayr-m/drt-orbital-solver) · [DRT-Encoder-Brain](https://github.com/norayr-m/DRT-Encoder-Brain) · [ternary-lattice](https://github.com/norayr-m/ternary-lattice)

Also: [three-basket-backup](https://github.com/norayr-m/three-basket-backup_one-liner) (a one-line rotating backup scheduler) · [finance_sp500](https://github.com/norayr-m/finance_sp500) (an S&P 500 eyeball notebook; not investment advice).

---

Interactive demonstrations were built with AI assistants (Claude, Gemini). The mathematics is mine; the code was collaborative.

---

Content of this profile repository: Apache 2.0 (see `LICENSE`). Each linked project carries its own licence.
