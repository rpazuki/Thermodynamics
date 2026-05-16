---
title: "Ch. XIV — Discussion of Thermodynamic Analogies"
type: concept
tags: [statistical-mechanics, thermodynamics, temperature, entropy, canonical-distribution, microcanonical-distribution, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter XIV: Discussion of Thermodynamic Analogies

## Overview

Chapter XIV is the philosophical centrepiece of the book. Gibbs systematically surveys *three* different mechanical analogues of temperature and entropy — one from the canonical ensemble and two from the microcanonical ensemble — and discusses their relative merits. He also acknowledges honestly what his theory does *not* explain: the anomalous heat capacities of polyatomic molecules, and the failure of classical mechanics for radiation.

## The Goal: An A Priori Foundation for Thermodynamics

Gibbs states the problem clearly: "If we wish to find in rational mechanics an *a priori* foundation for the principles of thermodynamics, we must seek mechanical definitions of temperature and entropy." The quantities found must satisfy the thermodynamic fundamental relation

$$d\varepsilon = T\, dS - A_1\, da_1 - A_2\, da_2 - \cdots$$

and must reproduce the tendency of heat to flow from hot to cold.

## First Analogy: Canonical Ensemble (Preferred)

From the canonical distribution, the thermodynamic fundamental relation is exactly reproduced by the differential equation

$$d\bar{\varepsilon} = -\Theta\, d\bar{\eta} - \bar{A}_1\, da_1 - \cdots$$

The correspondences are:
- Temperature: $T \leftrightarrow \Theta$ (the modulus)
- Entropy: $S \leftrightarrow -\bar{\eta}$ (negative average index of probability)
- Free energy: $F \leftrightarrow \psi = \bar{\varepsilon} + \Theta\bar{\eta}$

For large $n$, fluctuations of $\eta$ and $\bar{A}_i$ are negligible, so the averages are the observed thermodynamic values. The mathematical derivation of this analogy from $e^{-\psi/\Theta} = \int e^{-\varepsilon/\Theta}\, dp\, dq$ shows how to pass from the microscopic Hamiltonian to macroscopic thermodynamic functions: this is precisely the calculation of the partition function.

Gibbs regards this as the most complete and mathematically tractable analogy.

## Second Analogy: Microcanonical, $\log V$ as Entropy

From the microcanonical differential relation:
- Temperature: $T \leftrightarrow d\varepsilon / d(\log V) = e^{-\phi} V$
- Entropy: $S \leftrightarrow \log V$

This is more natural from some perspectives: energy and entropy are free of averaging signs, and $\log V$ is a simpler and more intuitive concept than $-\bar{\eta}$. The correspondence $\log V = S$ anticipates Boltzmann's $S = k_B \ln W$ almost exactly. Gibbs notes that $\log V$ has the right additivity properties and the right response to adiabatic changes.

## Third Analogy: Microcanonical, $\phi$ as Entropy

- Temperature: $T \leftrightarrow d\varepsilon/d\phi$ (inverse slope of density of states)
- Entropy: $S \leftrightarrow \phi$

This is slightly simpler to define (no integration required), but is ill-defined for systems of one or two degrees of freedom, making it less general.

## Gibbs's Assessment

For systems of very many degrees of freedom, all three analogies give the same answers to human precision. The canonical analogy is preferred for analytical work because $\psi$ is more easily manipulated than $V$ or $\phi$. The $\log V$ analogy is preferred conceptually for its directness. Gibbs declines to declare one universally superior.

## Honest Limitations

Gibbs acknowledges two serious failures of the classical framework:
1. **Equipartition anomaly**: A diatomic gas should have 6 degrees of freedom per molecule (giving $C_v = 3R$), but observation gives 5 ($C_v = \tfrac{5}{2}R$). This was "long recognized by physicists" and points to the failure of classical mechanics at the molecular level — what would require quantum mechanics to resolve.
2. **Radiation**: The phenomena of radiant heat (what we now call blackbody radiation) and electrical phenomena in atomic combination show that "the hypothesis of systems of a finite number of degrees of freedom is inadequate" — a remarkable anticipation of the ultraviolet catastrophe that Planck resolved in 1900.

## Significance

Chapter XIV provides the most explicit and careful statement anywhere in the book of what statistical mechanics is and what it accomplishes. It maps the mathematical structure of Chapters IV–XIII onto the empirical framework of classical thermodynamics, locates the exact and approximate regimes of the correspondence, and honestly demarcates the boundaries of the classical theory. This chapter is the logical summary of the book's central argument.
