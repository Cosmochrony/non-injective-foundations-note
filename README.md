This repository contains the source of the **Non-Injective Foundations Presentation Note** of the Cosmochrony programme
[*The Non-Injective Foundations Sub-Programme (Presentation Note 5)*](out/NonInjectiveFoundationsNote.pdf).

This note synthesises the **non-injective foundations sub-programme**, the axiomatic spine of the Cosmochrony corpus. Starting from four axioms (A1--A4) governing admissible transitions between observable states, it derives as **theorems** --- not postulates --- the structural necessity of non-injectivity, the irreversibility of observable evolution, the discrete Heisenberg group $\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$ and its Weil representation $V_\rho$ as the unique admissible fibre, and the absence of any independent dimensional parameter beyond $c_\chi$.

## Central Question

> Which structures are forced once admissible non-injective projection is taken as the sole primitive?

The sub-programme answers: **all of them**. The Heisenberg group, the Weil representation, the Born--Infeld saturation constraint, and the arrow of time are not postulates but consequences of A1--A4.

## Logical Chain

$$
\text{A1--A4}
\;\Longrightarrow\;
\Pi \text{ non-injective},\; S_\Pi > 0
\;\Longrightarrow\;
[X,\sigma(X)] = Z \neq 0
\;\Longrightarrow\;
\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})
\;\Longrightarrow\;
V_\rho.
$$

## The Four Axioms

- **A1 (Local projective admissibility):** there exists a non-empty set $F_n$ of admissible successor directions from any observable state $O_{n-1}$.
- **A2 (Structural non-injectivity):** distinct admissible directions may lead to the same resolved state; $\Pi_n$ is generically non-injective.
- **A3 (Non-premature selection):** an admissible transition preserves the full multiplicity of open directions until projection locking.
- **A4 (Projection locking):** resolution occurs only when continuous BI saturation meets the discrete shell support.

## Constituent Papers

| Paper | Central output | Status |
|---|---|---|
| **ENI** | $\Pi$ non-injective $\Leftrightarrow$ $S_\Pi > 0$ $\Leftrightarrow$ genuine emergence | proved |
| **ENI Cor. 6** | Recursive non-injectivity; colour confinement structural | proved / structural |
| **Foundation M** | A1--A4 $\Rightarrow$ $[X,Y]=Z\neq 0$ $\Rightarrow$ $\mathrm{Heis}_3$ $\Rightarrow$ $V_\rho$ | proved |
| **HeisenbergStructure** | Detailed proof of Foundation Theorem 5.7; uncertainty principle from A3 | proved |
| **noscale** | No independent dimensional parameter beyond $c_\chi$ | proved |

The white paper~\cite{Cosmochrony} is the programme overview, not a constituent of this sub-programme: its preliminary $\chi$/relaxation/iterated-projection vocabulary is **superseded** by the axiomatic formulation collected here. The substrate is static; the admissibility constraint replaces relaxation throughout the corpus.

## Position in the Programme

The foundations sub-programme is **Level 1** of the three-level architecture (Level 1 = primitive, Level 2 = spectral fibre, Level 3 = physical observables). It has no upstream dependencies within the corpus other than the Born--Infeld uniqueness result (BornInfeld), and every other sub-programme takes one or more of its outputs as inputs:

- **Note 1 (Spectral Admissibility):** consumes $\mathrm{Heis}_3(\mathbb{Z}/q\mathbb{Z})$, $V_\rho$, the BI bound $A_n \leq c_\chi/\sqrt{\lambda_n}$, the parity involution $c \leftrightarrow q-c$.
- **Note 2 (Emergent Geometry):** consumes $V_\rho$ and the four-dimensional Carnot convergence as starting point of the Mosco limit.
- **Note 3 (Gauge Structure):** consumes the phase fibre and projective incompleteness as the origin of gauge freedom.
- **Note 4 (Spectral Gravity):** consumes $S_\Pi > 0$ as the structural condition forcing an effective gravitational sector.

## Open Deliverables

- **Born rule for general observables.** The Born rule is established within the SU(2) sector (Q3); extension to arbitrary observables, multipartite systems, and continuous spectra is the primary open structural problem of this sub-programme.
- **Level 2 scale determination.** Proving that every emergent scale (masses, couplings, cosmological constant) is uniquely determined from $c_\chi$ and the cascade (noscale Level 2) would make the framework fully predictive with a single dimensional free parameter.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex` on `tex/NonInjectiveFoundationsNote.tex` and produces `out/NonInjectiveFoundationsNote.pdf`.