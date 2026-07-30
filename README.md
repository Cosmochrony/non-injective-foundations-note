# The Non-Injective Foundations Sub-Programme

Source for *The Non-Injective Foundations Sub-Programme (Presentation Note 5)*.

Version 1.3 corrects the status of the programme's carrier-selection claim. The ENI no-go
theorem establishes non-injectivity under explicit hypotheses, and the other constituent
papers retain their independent results. However, A1--A3 and Born--Infeld parity do not
derive the discrete Heisenberg group or its Weil representation.

## Carrier-selection correction

The finite countermodel in [*A Finite Countermodel to Heisenberg Carrier Selection from
Admissibility Axioms*](https://doi.org/10.5281/zenodo.21710123) uses
\(G=S_3\), \(X=(12)\), and \(Y=(23)\). The pair is exchanged by an involutive automorphism,
minimally generates \(S_3\), and acts faithfully and irreducibly in the standard
two-dimensional representation. Nevertheless,

$$
[X,Y]=(132)\notin Z(S_3).
$$

Thus a non-trivial commutator does not imply a central commutator or a Heisenberg
presentation. The Heisenberg/Weil carrier remains a coherent supplied realization, and
downstream results that consume it are conditional on that choice.

## Constituent papers

| Paper | Central output | Corrected status |
|---|---|---|
| ENI | Non-injectivity as a necessity of genuine emergence | proved |
| ENI Corollary 6 | Recursive non-injectivity; structural colour-confinement reading | proved / structural |
| Foundation M | Axioms, temporal ordering, and proposed carrier selection | structural / carrier claim refuted |
| HeisenbergStructure | Representation once the carrier is supplied | carrier claim refuted / conditional |
| HeisenbergCarrierObstruction | Finite \(S_3\) countermodel to carrier selection | proved |
| noscale | No independent dimensional parameter beyond \(c_{\mathrm{BI}}\) | proved under stated hypotheses |

## Open deliverables

- **Carrier selection:** derive an independently motivated condition that excludes the
  countermodel and selects a central extension, or retain the carrier as an explicit model
  choice.
- **Born rule for general observables:** extend the existing sector-specific result.
- **Level 2 scale determination:** determine whether emergent scales are fixed from
  \(c_{\mathrm{BI}}\) and the remaining structure.

## Build

```bash
bash compile.sh
```

This runs `pdflatex -> bibtex -> pdflatex -> pdflatex` and writes
`out/NonInjectiveFoundationsNote.pdf`.
