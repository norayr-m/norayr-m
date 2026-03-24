# Norayr Matevosyan

**Mathematician → Grid Infrastructure.** Free boundary problems, distributed reconstruction, AI/ML for power systems.

PhD KTH Stockholm. University of Vienna, University of Cambridge. Collaborated with Luis Caffarelli and Peter Markowich. Now building distributed AI into power grid infrastructure — utility data science serving ~10M people.

---

## Distributed Reconstruction Theorem

**Core result:** Incomplete observers interacting iteratively reconstruct representations that exceed the original.

```
R(f) = Σ φᵢ · Cᵢ(Πᵢ f)    where ‖R(f)‖ > ‖f‖
```

Observer graph with boundary projections Πᵢ and internal completions Cᵢ. Aggregate reconstruction exceeds original under sufficient observer orthogonality and faithful completion. Sequence is Cauchy. Memory is reconstruction, not replay.

**Paper:** N. Matevosyan, C. Apidae, A. Petrosyan — *Distributed Reconstruction from Incomplete Boundary Projections with Non-Trivial Internal Completion* (2026)

---

## Live Demonstrations

### [decoder-of-the-encoder](https://norayr-m.github.io/decoder-of-the-encoder/)
Bach's Fugue No.2 in C minor (BWV 847) mapped to a navigable graph tree. Each voice becomes a branch, each note a leaf. The fugue IS the DRT: subject = f, voice entries = projections Πᵢ, contrapuntal development = internal completion Cᵢ, the full fugue = R(f) > f. Temporal glow, Penrose chainmail curtain, fiber-optic light strands. Single self-contained HTML file.

### DRT Generator
The 7-column signal generator. Produces observer configurations and tests reconstruction fidelity across varying orthogonality conditions.

### DRT Scanner
The 7-column signal scanner. Analyzes reconstruction quality, identifies hallucination boundaries, measures faithful completion convergence.

### DRT Pipeline
The Bach BWV 847 pipeline — composer and decomposer working in parallel. Forward pass: composition → decomposition. Backward pass: decomposition → reconstruction. Visual proof that R(f) > f.

### Cellular Graph Simulator
Phase 4. Cellular automata on graph topology. Each cell is an observer with local rules. Emergent global behavior from distributed local transitions. DRT as biology.

### Interstellar Harmony
Orbital transformer. Multi-agent graph Turing machine with DRT forward/backward pass. Agents as nodes on a graph, local Turing transitions, distributed reconstruction in real-time. The architecture made visible. Inspired by Hans Zimmer's score for Christopher Nolan's *Interstellar* (2014) — the organ in the dust, time as a physical dimension, love as a variable that crosses the bulk. Zimmer proved that the right harmonic structure can carry information across dimensions. We borrowed the name and the conviction.

### Graph-DRT
Grid-scale DRT. Physical power grid graph — nodes as sensors, rank boundaries as isolating devices, local measurements as projections, distributed reconstruction of grid state. Companion: CityDRT — urban-scale simulation.

---

## Research Interests

**Free boundary problems** — tangential touch between free and fixed boundaries (KTH thesis, 2003). Almost monotonicity formulas for elliptic and parabolic operators with variable coefficients (with A. Petrosyan, CPAM 2011). Two-phase semilinear free boundary problem with degenerate phase (with A. Petrosyan, Calc. Var. PDE 2011).

**Distributed reconstruction** — formalizing how incomplete observers collectively reconstruct representations exceeding the original. Rooted in Arakelian approximation theory (tangential approximation, Arakelian sets). Application to power grid state estimation, multi-agent systems, and information theory.

**AI/ML for power systems** — GraphFormer on physics-aware grid topology. Cable failure prediction from high-frequency sensor data. Federated learning across utility boundaries. Grid modernization at scale.

**Information theory** — attention as resource allocation under bandwidth constraints. Kelvin inversion eliminating search cost. Missing data as signal.

---

## Links

- [Google Scholar](https://scholar.google.com/citations?user=qV1NHwkAAAAJ)
- [Math Genealogy](https://www.mathgenealogy.org/id.php?id=83126)

---

## Acknowledgments

The *Interstellar Harmony* project draws direct inspiration from Hans Zimmer's score for Christopher Nolan's *Interstellar* (2014). The organ tones reaching across spacetime, the treatment of time as a physical variable, the idea that information can propagate through dimensions we don't inhabit — Zimmer's harmonic architecture carries the same conviction as the DRT: incomplete projections, faithfully completed, reconstruct something larger than the original signal. We are grateful for the work that showed us what distributed reconstruction sounds like before we had the math.

---

*Mathematician. Builder. Chicago, IL.*
