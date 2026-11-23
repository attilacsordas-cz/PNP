# PNP — The Twin Complexity Conjecture

**A Universal Structural Principle Implying P = NP**

*Identical inputs, different mathematical questions.*

## The question

Is there a general structural reason why polynomial-time and NP-complete questions repeatedly occur as close companions on the **same input object**?

The starting intuition is Eulerian versus Hamiltonian traversal: keep the same graph, but change what must be visited exactly once — edges or vertices. The mathematical object remains unchanged, while the computational question changes.

The **Twin Complexity Conjecture**, proposed by Attila Csordas, generalises this observation into a universal, constructive, reciprocal same-input principle: every nonconstant polynomial-time decision question has an NP-complete structural twin, and conversely, every nonconstant NP-complete question has a polynomial-time twin.

## Position and novelty

The proposed novelty lies in the **universal conjecture itself**, not in the established complexity results motivating it. Earlier graph and norm complexity comparisons provide conceptual precedents.

The paper proves that the literal universal conjecture **implies P = NP**, and identifies its logical structure through an additional universal structural companion principle. This is a conditional consequence, **not a proof of P = NP**.

The conjecture is deliberately offered without proof, inviting mathematical investigation, generalisation, refinement, and possible refutation.

## Paper

**[The Twin Complexity Conjecture — PDF](./Twin_Complexity_Conjecture_Attila_Csordas_CZ_v1_0.pdf)**

Attila Csordas · CriticalZero Ltd, Cambridge, UK

First draft: 8 November 2026  
Current release: 23 November 2026

A small Lean 4 companion library is planned.

## License

The manuscript is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) license.

You may share and adapt the manuscript for non-commercial purposes with appropriate attribution to the author. Any future Lean source code will have its licensing specified separately.
