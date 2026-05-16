---
title: "Pogliani & Berberan-Santos 2000 — Constantin Carathéodory and Axiomatic Thermodynamics"
type: source
tags: [thermodynamics, caratheodory, axiomatic-thermodynamics, pfaffian, entropy, second-law, history-of-thermodynamics, mathematics]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

## Citation

Lionello Pogliani and Mario N. Berberan-Santos, "Constantin Carathéodory and the Axiomatic Thermodynamics," *Journal of Mathematical Chemistry*, Vol. 28, Nos. 1–3 (2000), pp. 313–324. Università della Calabria (Pogliani) and Instituto Superior Técnico, Lisboa (Berberan-Santos).

## Raw path

`raw/Thermodynamics/Papers/68.pdf`

## Summary

This paper provides a combined intellectual biography of Constantin Carathéodory and a pedagogical introduction to the axiomatic [[thermodynamics]] he founded in 1909. The authors trace how Carathéodory — influenced by Hilbert's axiomatic geometry and in close collaboration with Max Born — reformulated the two laws of thermodynamics without recourse to idealised engines, cycles, or the concept of heat as a primary quantity, instead anchoring everything in Pfaffian differential equations and an inaccessibility axiom. The reception history is carefully documented, from Born's 1921 revival through Planck's 1926 critique, Buchdahl's post-war simplifications, and the later Anglo-American school (Pippard, Sears, Landsberg, Turner). Substantial space is devoted to a self-contained mathematical treatment of Pfaffians, showing explicitly how the exactness of $dS = dQ/T$ for ideal gases follows from the Schwarz integrability condition. The paper concludes that the method's relative neglect in mainstream textbooks stems from Planck's criticism that it lacks a compelling physical picture of [[entropy]], a criticism the authors regard as equivalent to its mathematical demands.

## Key claims

- Carathéodory published his foundational paper "Untersuchungen über die Grundlagen der Thermodynamik" in *Math. Ann.* 67 (1909), 355–386, and a shorter follow-up in 1925; together these constitute the full axiomatic programme (source: 68.pdf).
- Carathéodory's **first axiom** reformulates the first law: for an adiabatic process, $U_f - U_i + W = 0$, defining internal energy without invoking heat (source: 68.pdf).
- His **second axiom** states: "In the neighbourhood of any equilibrium state of a system there exist states that are inaccessible by reversible adiabatic processes." This inaccessibility principle replaces the Kelvin–Planck and Thomson–Clausius formulations of the [[second-law-of-thermodynamics]], and the two formulations are equivalent (source: 68.pdf).
- Heat is treated as a *derived* quantity, appearing only once the adiabatic restriction is lifted: $dQ = dU - dW$. This is simultaneously the method's conceptual strength (energy rather than heat is conserved) and its pedagogical weakness (heat is easily measured but here it is secondary) (source: 68.pdf).
- The mathematical backbone of the theory is the **Pfaffian differential equation** $df = \sum_i X_i \, dx_i$. Whether this expression is integrable (exact) is determined by the Schwarz condition $\partial X_i / \partial x_j = \partial X_j / \partial x_i$ (source: 68.pdf).
- For an adiabatic ideal gas the Pfaffian $C_v \, dT/T + R \, dV/V = 0$ is exact, yielding $TV^{\gamma-1} = \text{const}$ (source: 68.pdf).
- The non-exactness of $\delta Q$ is demonstrated: the Schwarz condition fails for $dQ = C_v \, dT + (RT/V) \, dV$, showing that heat is not a state function (source: 68.pdf).
- An **integrating factor** $1/T$ converts $\delta Q$ into the exact differential $dS = \delta Q / T$, identifying [[entropy]] $S$ as a state function and $T$ as absolute temperature (source: 68.pdf).
- Carathéodory's main mathematical achievement was proving that an integrating factor exists for Pfaffians in *more than two variables* — the non-trivial case that requires the inaccessibility axiom (source: 68.pdf).
- The paper was essentially ignored for twelve years until Born's 1921 series of articles; Planck's 1926 criticism — that the axiom gives no experimental criterion to distinguish accessible from inaccessible states — remains the principal objection to the method (source: 68.pdf).
- Carathéodory's life (1873–1950) spanned careers in engineering, mathematics (measure theory, complex analysis, variational calculus, geometric optics), and physics; his supervision under Minkowski in Göttingen and friendship with Hilbert and Born were decisive influences (source: 68.pdf).

## Methods

The paper employs two parallel approaches: (1) a historical-biographical narrative drawing on primary and secondary sources, and (2) a self-contained mathematical tutorial. The mathematical sections work through concrete Pfaffian examples — adiabatic ideal gas, general ideal gas, integrating factors — step by step using the Schwarz integrability criterion, making the abstract theory accessible to readers with standard calculus. This pedagogical strategy sets the paper apart from more purely historical treatments.

## Limitations

- The mathematical treatment deliberately restricts to $i = 2$ variables (two-dimensional Pfaffians), acknowledging that this is the trivial case where an integrating factor always exists; the hard $n > 2$ case is stated but not proved.
- The biography relies heavily on a small number of secondary sources (notably Perron's 1952 obituary) and does not engage with recently discovered archival material.
- The reception history focuses on the European and Anglo-American mainstream; non-English-language responses (e.g. Italian, Russian, Portuguese traditions) are underrepresented.
- The paper does not address post-1980 foundational work (e.g. Lieb and Yngvason's rigorous 1999 entropy axiomatics), leaving the contemporary state of the field unclear.

## Connections

- The inaccessibility axiom treated here is the same axiom that [[redlich-fundamental-thermodynamics-since-caratheodory]] analyses critically, arguing that subsequent axiomatists failed to improve upon it substantively.
- The Pfaffian route to [[entropy]] ($dS = \delta Q / T$) is a rigorous mathematical version of the argument Clausius made heuristically in [[clausius-1865-main-equations]].
- Hilbert's *Grundlagen der Geometrie* (1899) and its influence on Carathéodory connect this paper thematically to the broader project of axiomatising physics — the same impulse that drove [[planck-treatise-on-thermodynamics]] (Planck 1897) and later statistical mechanics.
- The zeroth law, treated here as an axiom analogous to Euclid's first postulate, is re-examined by Redlich (see [[redlich-fundamental-thermodynamics-since-caratheodory]]), who argues it is not an empirical law but a rule of order.
- The equivalence of Carathéodory's second axiom with the Kelvin–Planck statement (established by Landsberg 1964) is noted, closing the gap between the axiomatic and engineering traditions of [[thermodynamics]].

## Quotes

> "In 1909 Constantin Carathéodory… published a seminal work on an axiomatic approach to thermodynamics, which practically put the entire subject on a new basis. His method allowed a rigorous mathematical formulation of the consequences of the second thermodynamic law… without recourse to imaginary machines or imaginary cycles, and such strange concepts as the flow of heat." (source: 68.pdf)

> "Carathéodory's 'mathematical' formulation identifies this asymmetry [of entropy] with unattainable 'near' equilibrium states. It can be noticed that in the axioms and definitions of the new method there is no mention of heat, temperature or entropy whatsoever. In fact, heat is regarded as a derived rather than a fundamental quantity." (source: 68.pdf)

> "Looking back at the history of this elegant mathematical method, it really seems that M. Planck's criticism about the difficulty of the method to provide a compelling physical picture of entropy stands even today as the main difficulty, together with its mathematical 'harshness', for a wide acceptance of Carathéodory's treatment." (source: 68.pdf)
