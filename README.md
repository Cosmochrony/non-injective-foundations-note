This repository contains the source of the **Non-Injective Foundations Presentation Note** of the Cosmochrony programme (out/NonInjectiveFoundationsNote.pdf).

This note is the synthesis paper of the **non-injective foundations sub-programme** (Branch I of the Cosmochrony programme). It gathers the foundational papers that establish the axiomatic base of the framework on top of a single primitive: the local structure of admissible non-injective transitions between observable states.

## Sub-Programme Scope

The non-injective foundations sub-programme covers the papers that:

- justify non-injective projection as a structural necessity of genuine emergence,
- erect the minimal axiomatic basis (axioms A1--A4) from which the rest of the Cosmochrony programme is derived,
- supply the structural identifications (Heisenberg primitive, absence of an external dimensional scale) that downstream sub-programmes (spectral admissibility, geometric emergence, gauge structure, spectral gravity, entanglement, Lorentz capacity) take as input.

## Constituent Papers

- **White Paper** -- *Cosmochrony: A Non-Injective Projection Theory of Emergent Physics* (programme overview).
- **ENI** -- *Emergence and Non-Injectivity*: structural justification of non-injectivity as the signature of genuine emergence.
- **Foundation** -- *Admissible Non-Injective Transitions as the Primitive*: minimal axiomatic basis (A1--A4) of the framework.
- **HeisenbergStructure** -- detailed derivation of the non-factorisability theorem (Foundation Theorem 5.6).
- **noscale** -- absence of an external dimensional scale at the level of admissibility.

## Position in the Programme

- Branch I of the Cosmochrony programme (Foundation track).
- Provides the axiomatic input on which Branch II (O-series, spectral admissibility) and Branch III (Q-series, applications) build.
- The non-injective projection $\Pi$ introduced here is the primitive shared by every downstream sub-programme.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex` on
`tex/NonInjectiveFoundationsNote.tex` and produces `out/NonInjectiveFoundationsNote.pdf`.