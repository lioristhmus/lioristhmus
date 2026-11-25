# Two-Chirality Twistor Correspondences for Einstein Geometry

**Lior Isthmus**

These four preprints address Penrose’s gravitational googly problem. What twistor data determine a four-dimensional Einstein geometry when both chiralities of gravity interact? We construct local and global correspondences for analytic Einstein geometry at each fixed cosmological constant, and for smooth Lorentzian vacuum gravity, with the global smooth result formulated on globally hyperbolic spacetimes.

---

## The Four-Paper Series

In the two local forward constructions (Papers 1 and 3), the unknown Einstein metric is an output. The global constructions (Papers 2 and 4) also require data specifying how local charts fit together.

| # | Scope | Paper & Links | Construction and result |
| --- | --- | --- | --- |
| **1** | **Local · Analytic**<br>Any fixed $\Lambda\in\mathbb{C}$ | **A projective twistor correspondence for local analytic Einstein germs** *(v1.1)*<br>[Repo](https://github.com/lioristhmus/projective-twistor-einstein-germs) · [PDF](https://github.com/lioristhmus/projective-twistor-einstein-germs/releases/download/paper-v1.1/projective-twistor-einstein-germs-v1.1.pdf) · [Hexagon v2](https://hexagonmath.org/2611.00123v2) · [Zenodo](https://doi.org/10.5281/zenodo.24197319) · [Computations](#paper-1-local-analytic-einstein-germs) | Given the marking and cosmological constant, two analytic Čech classes of weights $+2$ and $-6$ on the fixed flat twistor germ determine each finite reconstruction step ([Prop. 5.9](https://github.com/lioristhmus/projective-twistor-einstein-germs/blob/paper-v1.1/release/paper-v1.1/manuscript.md?plain=1#L1159)). The Cartan comparison proves convergence ([Thm. 6.3](https://github.com/lioristhmus/projective-twistor-einstein-germs/blob/paper-v1.1/release/paper-v1.1/manuscript.md?plain=1#L1289)). The construction recovers every marked local analytic Einstein germ, of any Weyl type. |
| **2** | **Global · Analytic**<br>Any fixed $\Lambda\in\mathbb{C}$ | **Global twistor sources for analytic Einstein spacetimes** *(v1.0.1)*<br>[Repo](https://github.com/lioristhmus/global-twistor-sources) · [PDF](https://github.com/lioristhmus/global-twistor-sources/releases/download/v1.0.1/global-twistor-sources-en-v1.0.1.pdf) · [Hexagon v2](https://hexagonmath.org/2611.00425v2) · [Zenodo](https://doi.org/10.5281/zenodo.24239028) · [Computations](#paper-2-global-analytic-einstein-spacetimes) | The atlas supplies a complex point manifold, local pairs from Paper 1, and overlap comparisons with spin lifts ([Def. 5.1](https://github.com/lioristhmus/global-twistor-sources/blob/v1.0.1/paper/manuscript.md?plain=1#L1349)). The decoder constructs the global Einstein metric ([Thm. 5.6](https://github.com/lioristhmus/global-twistor-sources/blob/v1.0.1/paper/manuscript.md?plain=1#L1527)). These atlases, two null-monodromy descriptions, and holomorphic spin Einstein four-manifolds form four equivalent categories. |
| **3** | **Local · Smooth**<br>$\Lambda=0$ | **A two-chirality twistor correspondence for smooth Lorentzian Ricci-flat germs** *(v1.1)*<br>[Repo](https://github.com/lioristhmus/smooth-twistor-germs) · [PDF](https://github.com/lioristhmus/smooth-twistor-germs/releases/download/v1.1/smooth-twistor-germs-en-v1.1.pdf) · [Hexagon v3](https://hexagonmath.org/2611.00698v3) · [Zenodo](https://doi.org/10.5281/zenodo.24498374) · [Computations](#paper-3-smooth-lorentzian-vacuum-germs) | Two admitted CR classes on the fixed space $\mathbb{R}^3\times\mathbb{CP}^1$ ([Def. 3.11](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/paper/smooth-twistor-germs-en-v1.1.md?plain=1#L2195)) generate vacuum initial data $(h,K)$ ([Thm. 4.18](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/paper/smooth-twistor-germs-en-v1.1.md?plain=1#L3984)). Cauchy development gives the metric at its physical scale. Conversely, every marked smooth vacuum germ admits such a presentation ([Thm. 5.7](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/paper/smooth-twistor-germs-en-v1.1.md?plain=1#L4615)). |
| **4** | **Global · Smooth**<br>$\Lambda=0$ | **Global wave completion and recognition of smooth twistor sources** *(v1.1)*<br>[Repo](https://github.com/lioristhmus/smooth-global-twistor-sources) · [PDF](https://github.com/lioristhmus/smooth-global-twistor-sources/releases/download/v1.1/smooth-global-twistor-sources-en-v1.1.pdf) · [Hexagon v2](https://hexagonmath.org/2611.00888v2) · [Zenodo](https://doi.org/10.5281/zenodo.24498661) · [Computations](#paper-4-global-wave-completion) | Local metrics come from executing the pairs of Paper 3. An atlas supplies their overlap and spin comparisons and must pass the quotient and global hyperbolicity tests ([Def. 11.2](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L2580)). The atlas admits a global completion ([Thm. 1.4](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L156)). The wave construction on a given metric ([Thm. 1.1](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L97)) and recognition of an independently supplied source ([Thm. 1.2](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L115)) are separate results. |

---

## Where to Start

- **Twistor gravity — A convergent two-class correspondence and Penrose’s active patching.** For each fixed cosmological constant, two analytic Čech classes of weights $+2$ and $-6$ on a fixed twistor germ recover every marked local analytic Einstein germ, of any Weyl type ([Paper 1, Thm. 2.4](https://github.com/lioristhmus/projective-twistor-einstein-germs/blob/main/release/paper-v1.1/manuscript.md#thm:gg-main)). The correspondence realizes Penrose’s 2015 active-patching proposal in a projective Heisenberg operator model ([Thm. 9.12](https://github.com/lioristhmus/projective-twistor-einstein-germs/blob/main/release/paper-v1.1/manuscript.md#thm:gg-unified-projective-gravitational-correspondence)).
- **Schwarzschild near the future horizon and the comparison with Adamo et al. (2026).** Proposition 10.5 gives piecewise finite-readout optical bounds for a compact family of nonradial trajectories crossing the horizon ([Paper 1, §10](https://github.com/lioristhmus/projective-twistor-einstein-germs/blob/main/release/paper-v1.1/manuscript.md#10-schwarzschild-near-the-future-horizon)). The calibrated comparison of local primitives specifies the projector and residue conventions ([App. K.5](https://github.com/lioristhmus/projective-twistor-einstein-germs/blob/main/release/paper-v1.1/manuscript.md#k5-a-calibrated-schwarzschild-source-primitive)).
- **Global twistor geometry — Null monodromy and the Nariai obstruction.** Null monodromy and parametrized incidence give an equivalence between four descriptions of global holomorphic Einstein geometry, from atlases of two-class data to oriented spin Einstein four-manifolds ([Paper 2, Thm. 1.1](https://github.com/lioristhmus/global-twistor-sources/blob/main/paper/manuscript.md#thm:global-source-correspondence-v08)). Nariai spacetime shows why the choice of description matters. No Hausdorff contact space carries the full complex skies over all its real points ([Thm. 8.2](https://github.com/lioristhmus/global-twistor-sources/blob/main/paper/manuscript.md#thm:nariai-no-hausdorff-whole-sky-carrier)), and in the product complexification each real point sky has nonclosed saturation ([Thm. 8.6](https://github.com/lioristhmus/global-twistor-sources/blob/main/paper/manuscript.md#thm:nariai-all-real-nonclosed-point-skies-v09)).
- **Smooth vacuum gravity — Two-class presentations of every marked Lorentzian vacuum germ.** Two hypersurface-twistor CR cohomology classes encode vacuum initial data whose Cauchy development recovers the germ at its physical scale ([Paper 3, Thm. 1.1](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/paper/smooth-twistor-germs-en-v1.1.md?plain=1#L48)). In the forward construction, three negative contact responses yield the flat scalar and York inverses ([Thm. 4.12](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/paper/smooth-twistor-germs-en-v1.1.md?plain=1#L3375), [code](https://github.com/lioristhmus/smooth-twistor-germs/blob/main/computations/green.py)). In the converse direction, a relative extension based on Czimek’s exterior construction gives a presentation for every such germ ([Thm. 5.7](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/paper/smooth-twistor-germs-en-v1.1.md?plain=1#L4615), [App. B](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/paper/smooth-twistor-germs-en-v1.1.md?plain=1#L8083)).
- **Microlocal analysis / AQFT — Four Cauchy traces determine the global Hadamard singularity class.** Among scalar bisolutions modulo smooth kernels, the four traces on the entire product of one Cauchy hypersurface with itself characterize the canonical class ([Paper 4, Thm. 4.4](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L843) and [Thm. 4.5](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L901)). A flat-torus example shows why the full product matters. Its bisolution vanishes near the diagonal yet has singularities at distant pairs of points ([Ex. 4.7](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L952), [code](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/main/computations/check.py)).
- **Mathematical GR / PDE — Analytic persistence for compact Cauchy data.** Every smooth globally hyperbolic vacuum development of compact connected analytic Cauchy data admits a unique compatible real-analytic structure in which the metric and initial embedding are analytic ([Paper 4, Appendix A, Thm. A.4](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L4743)). The proof uses no twistor-correspondence inputs. Theorem 16.8 uses this result to identify the smooth and analytic maximal developments.
- **Category theory — Descent and terminal developments.** Compatible local twistor atlases descend under the global admission conditions, and global completion is fully faithful. For fixed marked vacuum initial data, the maximal globally hyperbolic development corresponds to a terminal object in the category of twistor source developments ([Paper 4, Thms. 1.3–1.4](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L132)).

---

## Computational Supplements

Each supplement includes the inputs, software environment, negative controls, recorded results, and checksums needed to reproduce its calculations. The checks cover selected identities and examples. The arguments for analytic convergence, topology, and categorical equivalence are given in the manuscripts.

### Paper 1. Local analytic Einstein germs

The 28 records include exact checks of twistor formulas and numerical diagnostics for the record recursion. The `independent/` directory contains cross-checks using a second implementation. [Check index](https://github.com/lioristhmus/projective-twistor-einstein-germs/blob/paper-v1.1/computations/CHECKS.md) · [Supplement ZIP](https://github.com/lioristhmus/projective-twistor-einstein-germs/releases/download/paper-v1.1/local-einstein-computations-0.2.0-r3.zip)

### Paper 2. Global analytic Einstein spacetimes

The 68 symbolic checks cover Nariai curvature, null and conic geometry, tractor normalizations, and curvature and contracted Bianchi identities in Gaussian coordinates. [Check index](https://github.com/lioristhmus/global-twistor-sources/blob/v1.0.1/computations/CHECKS.md) · [Source ZIP including the supplement](https://github.com/lioristhmus/global-twistor-sources/releases/download/v1.0.1/global-twistor-sources-v1.0.1-source.zip)

### Paper 3. Smooth Lorentzian vacuum germs

The additional experiments test York inversion, free-space transport, and reconstruction and extension of a smooth nonanalytic vacuum plane wave. [Original checks](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/computations/README.md) ([ZIP](https://github.com/lioristhmus/smooth-twistor-germs/releases/download/v1.0/smooth-twistor-germs-computations-v1.0.zip)) · [Additional experiments](https://github.com/lioristhmus/smooth-twistor-germs/blob/v1.1/additional-computations/paper3-smooth-twistor-additional-computations-2026-11-24-r2/README.md) ([ZIP](https://github.com/lioristhmus/smooth-twistor-germs/releases/download/v1.1/paper3-smooth-twistor-additional-computations-2026-11-24-r2.zip)).

### Paper 4. Global wave completion

The additional experiments follow wave kernels on Kasner and torus backgrounds, including Cauchy-surface transport and singularities away from the diagonal. [Original checks](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/computations/README.md) ([ZIP](https://github.com/lioristhmus/smooth-global-twistor-sources/releases/download/v1.0/smooth-global-twistor-sources-computations-v1.0.zip)) · [Additional experiments](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/additional-computations/paper4-global-wave-additional-computations-2026-11-24-r2/README.md) ([ZIP](https://github.com/lioristhmus/smooth-global-twistor-sources/releases/download/v1.1/paper4-global-wave-additional-computations-2026-11-24-r2.zip)).

---

## Logical Architecture & Modularity

The smooth Lorentzian correspondence (Papers 3–4) does **not** logically depend on Papers 1–2 except in the dedicated analytic-locus comparison sections (Paper 3 §9; Paper 4 §§15–16). Paper 4 Appendix A uses no twistor-correspondence inputs and feeds into the analytic–smooth marked development comparison (Theorem 16.8, Corollary 16.9).

```mermaid
---
config:
  theme: neutral
  block:
    padding: 20
  themeCSS: |
    .flowchart-link[id$="-P1-P3"], .flowchart-link[id$="-P2-B4"], .flowchart-link[id$="-P4-B4"] {
      stroke-dasharray: 5 4 !important;
    }
---
block-beta
    columns 3
    Analytic["Analytic Branch<br/>(arbitrary Λ ∈ ℂ)"] space Smooth["Smooth Lorentzian Branch<br/>(Λ = 0, independent of 1–2)"]
    P1["Paper 1: Local Analytic<br/>(T₀ Čech pairs, optical bundle,<br/>Heisenberg operator model,<br/>Schwarzschild)"] space P3["Paper 3: Local Smooth<br/>(CR pairs on ℝ³×ℂℙ¹,<br/>3-response York inverse,<br/>Czimek exterior extension,<br/>covariant wave kernel)"]
    P2["Paper 2: Global Analytic<br/>(Source atlases, null monodromy,<br/>parametrized incidence,<br/>Nariai obstructions)"] space P4["Paper 4: Global Smooth<br/>(4-trace global wave class,<br/>causal embeddings,<br/>atlas completion,<br/>maximal developments, families)"]
    A4["Paper 4, Appendix A<br/>(Thm. A.4)<br/>(No twistor inputs: analytic<br/>persistence for compact Cauchy data)"] space B4["Paper 4, §§15–16<br/>(Thm. 16.8, Cor. 16.9)<br/>(Analytic–smooth maximal<br/>source comparison)"]
    P1 --> P2
    P3 --> P4
    P1 -- "Analytic locus<br/>(Paper 3 §9)" --> P3
    P2 --> B4
    P4 --> B4
    A4 --> B4
    classDef paper fill:#f5f5f5,stroke:#000000,stroke-width:1px,color:#111111
    class P1,P2,P3,P4,A4,B4 paper
    style Analytic fill:transparent,stroke-width:0px
    style Smooth fill:transparent,stroke-width:0px
```

---

## Preprint Status & Lean Formalization

All four manuscripts are unrefereed preprints on classical four-dimensional gravity. [Paper 4, §§17.2–17.3](https://github.com/lioristhmus/smooth-global-twistor-sources/blob/v1.1/paper/smooth-global-twistor-sources-en-v1.1.md?plain=1#L4490) discusses the scope of the correspondence. Critical scrutiny, counterexamples, and independent verification of the manuscripts are welcome.

The Lean 4 formalization of Paper 1 is in progress in a private repository. Its current milestone is the coefficient comparison in Theorem 6.3, a step toward the main correspondence in Theorem 2.4.

---

**Licenses:** Manuscripts, documentation, and recorded data are **CC BY 4.0**; code is **Apache-2.0**.