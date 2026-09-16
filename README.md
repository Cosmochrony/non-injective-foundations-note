# The Non-Injective Foundations Sub-Programme

Source for *The Non-Injective Foundations Sub-Programme (Presentation Note 5)*.

Version 1.5 aligns the note with Foundation version 2.2 and HeisenbergStructure version 2.1.
The ENI no-go theorem establishes non-injectivity under explicit hypotheses. Within Foundation,
A1 and A2 give immediate information loss along non-injective transitions; the arrow of time
follows only under the acyclicity hypothesis [H-acyc], which is not established. Irreducibility
of the admissible fibre is conditional on a representation-theoretic dictionary, and A1--A3 and
Born--Infeld parity do not derive the discrete Heisenberg group. Once that group and a
non-trivial central character are supplied, Stone--von Neumann identifies the Heisenberg/Schrödinger representation on
\(L^2(\mathbb Z/q\mathbb Z)\); the associated Weil action is distinct further symplectic data.

## Carrier-selection obstruction

The finite countermodel of
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

| Paper | Central output | Status |
|---|---|---|
| ENI | Non-injectivity as a necessity of genuine emergence | proved |
| ENI Corollary 6 | Recursive non-injectivity; structural colour-confinement reading | proved / structural |
| Foundation M | Immediate information loss; temporal order under [H-acyc]; carrier-selection obstruction (Theorem 5.7) | proved / conditional / proved |
| HeisenbergStructure 2.1 | Finite \(S_3\) obstruction; Schrödinger representation once group and non-trivial central character are supplied; Weil action separate | obstruction proved / representation conditional / Weil action supplied |
| noscale | No independent dimensional parameter beyond \(c_{\mathrm{BI}}\) | proved under stated hypotheses |

## Open deliverables

- **Carrier selection:** derive an independently motivated condition that excludes the
  countermodel and selects a central extension, or retain the carrier as an explicit model
  choice.
- **Born rule:** derive it in any sector; Q3's singlet and correlator are conditional on a
  supplied bipartite carrier and an unestablished diagonal-\(2I\) invariance hypothesis, and do
  not establish the Born rule.
- **Level 2 scale determination:** determine whether emergent scales are fixed from
  \(c_{\mathrm{BI}}\) and the remaining structure.

## Open bridge

- **Continuous Hilbert limit:** supply a spatial second-order limit operator, the unestablished
  hypothesis [H-L] of [Q5b](https://doi.org/10.5281/zenodo.19686700). On its canonical Fourier
  filtration, [Q5a](https://doi.org/10.5281/zenodo.19642369) proves that the published
  admissibility form converges to the zero form and, under its depth and weight hypotheses, that
  no common scalar normalisation yields a non-trivial toric differential operator.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex` and writes
`out/NonInjectiveFoundationsNote.pdf`.
