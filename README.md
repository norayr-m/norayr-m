# Norayr Matevosyan

**Mathematician.** Free boundary problems, distributed reconstruction, graph Turing computation.

PhD KTH Stockholm. University of Vienna, University of Cambridge. Currently working on high performance bio computational algorythms, graph database enignes with native apple GPU acceleration. Motivation is applications to bio-digital twins, medical imaging, and multi-agent reconstruction.

---

> This is an amateur engineering project. We are not HPC professionals and make no competitive claims. Numbers speak; ego doesn't. Errors are likely.

---

## Some Fun Dashboards
---

## Live Demonstrations

### [finance_sp500](https://github.com/norayr-m/finance_sp500) — S&P 500 eyeball
Interactive charts on Shiller 1871–2026 monthly data: a [main chart](https://norayr-m.github.io/finance_sp500/html/sp500_shiller_1871_2026.html) with 3-segment PWLF, two-minima eyeball trend, L¹ fit from 2009, and a [log-log transform](https://norayr-m.github.io/finance_sp500/html/sp500_loglog.html) with draggable anchor circles and live slope/CAGR readout. In April 2025 I drew a line by eye that said 7000 in spring 2026; on April 17 2026 it closed at 7041. One correct call is not a track record. Amateur notebook. Nothing is investment advice.

### [DagDB Engine](https://github.com/norayr-m/dagdb-engine) — 6-Bounded Ranked DAG Database
GPU-accelerated graph database on Apple Silicon. Every node has a programmable LUT6 (64-bit lookup table). Ranked DAG evaluation, Morton Z-curve, 7-coloring parallelism, Carlos Delta persistence. Daemon architecture with POSIX shared memory for zero-copy UMA access. PostgreSQL extension via Rust/pgrx. 27/27 tests, 1M nodes at 0.71 GCUPS. [**Presentation**](https://norayr-m.github.io/DagDB/) | [**SQL Architecture**](https://norayr-m.github.io/DagDB/sql-architecture.html) | [**Podcast (30 min)**](https://norayr-m.github.io/DagDB/podcast.html) | [**Grid Demo**](https://norayr-m.github.io/DagDB/grid-demo.html)

### [Savanna Engine](https://github.com/norayr-m/savanna-engine) — 100 Billion Cells on One Laptop
Ultra-scale spatial lattice engine. 107,374,182,400 autonomous cells (predator-prey ecosystem on hex grid) simulated on Apple M5 Max. 15.8 GCUPS peak. Morton Z-curve memory layout (2.11× at 1B cells). GPU state init in 3.8ms (genesis.metal). 7-coloring lock-free parallelism. WebGL real-time playback. Lossless delta compression: 50× via XOR + Zstandard ([Carlos Mateo architecture](https://github.com/carlosmateo10/delta-compression-demo), MIT License). [**YouTube: 100B test**](https://youtu.be/6QiU7kUD3Os) | [**About**](https://norayr-m.github.io/savanna-engine/about.html) | [**Morton charts**](https://norayr-m.github.io/savanna-engine/morton_charts.html)

### [decoder-of-the-encoder](https://norayr-m.github.io/decoder-of-the-encoder/)
Bach's Fugue No.2 in C minor (BWV 847) mapped to a navigable graph tree. Each voice becomes a branch, each note a leaf. The fugue IS the DRT: subject = f, voice entries = projections Πᵢ, contrapuntal development = internal completion Cᵢ, the full fugue = R(f) > f. Temporal glow, Penrose chainmail curtain, fiber-optic light strands. Single self-contained HTML file.

### [DRT Generator](https://norayr-m.github.io/drt-generator/)
The 7-column signal generator. Produces observer configurations and tests reconstruction fidelity across varying orthogonality conditions.

### [DRT Scanner](https://norayr-m.github.io/drt-scanner/)
The 7-column signal scanner. Analyzes reconstruction quality, identifies hallucination boundaries, measures faithful completion convergence.

### [DRT Pipeline](https://norayr-m.github.io/drt-pipeline/)
The Bach BWV 847 pipeline — composer and decomposer working in parallel. Forward pass: composition → decomposition. Backward pass: decomposition → reconstruction. Visual proof that R(f) > f.

### [Cellular Graph Simulator](https://norayr-m.github.io/drt-cell-simulator/)
Phase 4. Cellular automata on graph topology. Each cell is an observer with local rules. Emergent global behavior from distributed local transitions. DRT as biology.

### [Interstellar Harmony](https://norayr-m.github.io/interstellar-harmony/)
Orbital transformer. Multi-agent graph Turing machine with DRT forward/backward pass. Agents as nodes on a graph, local Turing transitions, distributed reconstruction in real-time. The architecture made visible. Inspired by Hans Zimmer's score for Christopher Nolan's *Interstellar* (2014) — the organ in the dust, time as a physical dimension, love as a variable that crosses the bulk. Zimmer proved that the right harmonic structure can carry information across dimensions. We borrowed the name and the conviction.

### [Supernova 3D Solver](https://norayr-m.github.io/drt-orbital-solver/)
Phase 6. 35 Z-dimensional graph mathematics. Eigenvectors, matrix operations, multi-agent pathfinding across hierarchical 3D structures. The orbital solver — concentric spheres of interconnected nodes.

### [Ternary Lattice](https://norayr-m.github.io/ternary-lattice/)
4D onto 2.5D. Fractal trisistor matrix — recursive tetrahedral network where nodes operate in three states (-1, 0, +1). Macroscopic ether polyphonic wave sweeps through 3D space. GPU vec4 constraints on a tetrahedron topology.

### [Three Basket Egg Save](https://norayr-m.github.io/three-basket-backup_one-liner/)
One-line distributed backup scheduler. `tick = lambda f, d: (baskets[d%3].i_frame() if not f else baskets[f%3].p_frame())` — coprime rotation distributes I-frames (full snapshots) and P-frames (incremental deltas) across three independent storage targets. The same `(mod 3, period 12)` abstract machine appears in DNA codon reading frames, 3-phase power grids, MPEG GOP structure, Raft consensus, ZFS scrub rotation, Postgres replica sync, and the kissing number in R³. Includes a [volumetric lattice gas automaton](https://norayr-m.github.io/three-basket-backup_one-liner/volume.html) running the same lambda as a zero-loss 3D physics simulation on a 16³ tetrahedron lattice.

---

## Research Interests

**Free boundary problems** — tangential touch between free and fixed boundaries (KTH thesis, 2003). Almost monotonicity formulas for elliptic and parabolic operators with variable coefficients (with A. Petrosyan, CPAM 2011). Two-phase semilinear free boundary problem with degenerate phase (with A. Petrosyan, Calc. Var. PDE 2011).

**Distributed reconstruction** — formalizing how incomplete observers collectively reconstruct representations exceeding the original. Rooted in Arakelian approximation theory (tangential approximation, Arakelian sets). Applications to bio-digital twins, multi-agent systems, and information theory.

**Graph Turing computation** — Turing machines on graph topologies. Multi-agent computation where each node executes local transitions and distributed reconstruction emerges from the interaction. DRT as a computational substrate.

**Information theory** — attention as resource allocation under bandwidth constraints. Kelvin inversion eliminating search cost. Missing data as signal.

---

## Links

- [Google Scholar](https://scholar.google.com/citations?user=qV1NHwkAAAAJ)
- [Math Genealogy](https://www.mathgenealogy.org/id.php?id=83126)

---

## Acknowledgments

The *Interstellar Harmony* project draws direct inspiration from Hans Zimmer's score for Christopher Nolan's *Interstellar* (2014). The organ tones reaching across spacetime, the treatment of time as a physical variable, the idea that information can propagate through dimensions we don't inhabit — Zimmer's harmonic architecture carries the same conviction as the DRT: incomplete projections, faithfully completed, reconstruct something larger than the original signal. We are grateful for the work that showed us what distributed reconstruction sounds like before we had the math.

---

## AI Co-Authorship

All interactive demonstrations were co-authored with AI assistants: [Claude](https://claude.ai) (Anthropic) and [Gemini](https://gemini.google.com) (Google). The math is mine. The code was built collaboratively. Both are credited.

---

*Mathematician. Builder. Chicago, IL.*
