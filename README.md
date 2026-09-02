# The Non-Injective Foundations Sub-Programme

Source for *The Non-Injective Foundations Sub-Programme (Presentation Note 5)*.

Version 1.5 synchronises the carrier-selection correction with HeisenbergStructure version 2.1.
The ENI no-go theorem establishes non-injectivity under explicit hypotheses, and the other
constituent papers retain their independent results. However, A1--A3 and Born--Infeld parity
do not derive the discrete Heisenberg group. Once that group and a non-trivial central character
are supplied, Stone--von Neumann identifies the Heisenberg/Schrödinger representation on
\(L^2(\mathbb Z/q\mathbb Z)\); the associated Weil action is distinct further symplectic data.

## Carrier-selection correction

The finite countermodel incorporated into
[*A Finite Obstruction to Heisenberg Carrier Selection from Admissibility Constraints* version 2.1](https://doi.org/10.5281/zenodo.19635395)
uses
\(G=S_3\), \(X=(12)\), and \(Y=(23)\). The pair is exchanged by an involutive automorphism,
minimally generates \(S_3\), and acts faithfully and irreducibly in the standard
two-dimensional representation. Nevertheless,

$$
[X,Y]=(132)\notin Z(S_3).
$$

Thus a non-trivial commutator does not imply a central commutator or a Heisenberg
presentation. The Heisenberg group, Schrödinger representation, and separate associated Weil
action remain coherent supplied data, and downstream results that consume them are conditional
on those choices.

## Constituent papers

| Paper | Central output | Corrected status |
|---|---|---|
| ENI | Non-injectivity as a necessity of genuine emergence | proved |
| ENI Corollary 6 | Recursive non-injectivity; structural colour-confinement reading | proved / structural |
| Foundation M | Axioms, temporal ordering, and proposed carrier selection | structural / carrier claim refuted |
| HeisenbergStructure 2.1 | Finite \(S_3\) obstruction; Schrödinger representation once group and central character are supplied; Weil action separate | obstruction proved / representation conditional / Weil action supplied |
| noscale | No independent dimensional parameter beyond \(c_{\mathrm{BI}}\) | proved under stated hypotheses |

## Open deliverables

- **Carrier selection:** derive an independently motivated condition that excludes the
  countermodel and selects a central extension, or retain the carrier as an explicit model
  choice.
- **Born rule:** derive it in any sector; Q3's singlet and correlator are conditional on an
  unestablished diagonal-(2I) invariance hypothesis and do not establish the Born rule.
- **Continuous Hilbert limit:** supply the open non-trivial spatial-limit bridge [H-L]; Q5a
  version 3.2 instead proves the zero-form/no-go result for its canonical filtration.
- **Level 2 scale determination:** determine whether emergent scales are fixed from
  \(c_{\mathrm{BI}}\) and the remaining structure.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex` and writes
`out/NonInjectiveFoundationsNote.pdf`.
