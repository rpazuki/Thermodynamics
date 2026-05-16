---
title: "Treatise on Thermodynamics — Max Planck (tr. Alexander Ogg)"
type: source
tags: [thermodynamics, classical-thermodynamics, entropy, first-law, second-law, planck, equilibrium, dilute-solutions, phase-rule]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

## Citation

Planck, M. (1897/1903). *Treatise on Thermodynamics* (A. Ogg, Trans.). Longmans, Green & Co. (Original German: *Vorlesungen über Thermodynamik*.)  
Project Gutenberg EBook #50880, LaTeX transcription updated June 2021.

## Raw path

`raw/Thermodynamics/Plank/50880-t.tex`

## Summary

Planck's *Treatise on Thermodynamics* is a systematic, empirically grounded textbook presenting classical thermodynamics from first principles. Planck deliberately avoids kinetic-molecular hypotheses, instead building the entire framework from two empirical laws — the impossibility of perpetual motion of the first kind (First Law) and the impossibility of perpetual motion of the second kind (Second Law). Beginning with operational definitions of temperature, molecular weight, and heat, the book advances through the mathematics of energy and entropy, culminating in a sweeping treatment of chemical and phase equilibria. The work is notable for its unusually rigorous treatment of the Second Law via Clausius's entropy function, and for extending thermodynamic reasoning to dilute solutions and multi-component systems through Gibbs's phase rule and the characteristic function $\Psi$.

## Key claims

- The First Law is the principle of conservation of energy; its mathematical expression is $dU = Q + W$.
- The Second Law is grounded in the irreversibility of friction heat generation; its mathematical expression is $d\Phi \geq 0$ for any isolated system.
- Entropy $\Phi$ of a perfect gas is $M(c_v \log\theta + \tfrac{R}{m}\log v + \mathrm{const})$; it remains constant in reversible adiabatic processes and increases in irreversible ones.
- Helmholtz free energy $F = U - \theta\Phi$ is the maximum work extractable from an isothermal process.
- The Gibbs phase rule $f = \alpha - \beta + 2$ governs the degrees of freedom of a system with $\alpha$ independent constituents and $\beta$ phases.
- Dilute solutions obey laws analogous to perfect gases (osmotic pressure, boiling-point elevation, freezing-point depression) because the entropy of mixing takes the same logarithmic form.

## Methods

The book is entirely deductive, proceeding from postulates (impossibility of perpetual motion, empirical gas laws) through rigorous mathematics (partial differential equations, variational conditions for entropy extrema) to thermochemical and phase-equilibrium results. Reversible cycles (Carnot) are the central analytical tool for proving the Second Law and defining absolute temperature. Graphical methods (isothermal curves in the $p$–$v$ plane) are used to analyse real gases. Gibbs's characteristic function $\Psi = \Phi - (U+pV)/\theta$ provides the unifying equilibrium condition for multi-phase, multi-component systems.

## Limitations

- Assumes perfect-gas behaviour throughout most of Part IV; real-gas corrections are left as measurement problems.
- The book predates modern statistical mechanics (Boltzmann's entropy formula is not used). The molecular interpretation of entropy is deliberately excluded.
- Chemical kinetics and time-dependent processes are outside scope; only equilibrium states are characterised.
- The treatment of the solid–liquid critical point is speculative (§31), acknowledging the experimental inaccessibility of high pressures needed to verify a liquid–solid critical point.

## Connections

- [[entropy]] — central concept; defined and proven to be a state function.
- [[free-energy]] — Helmholtz free energy $F$ introduced; its decrease drives isothermal spontaneous processes.
- [[carnot-cycle]] — used to derive the efficiency formula and prove the Second Law for any substance.
- [[phase-rule]] — Gibbs's rule emerges from the general equilibrium condition.
- [[dilute-solutions]] — analogy between dissolved molecules and perfect gas molecules; osmotic pressure derivation.
- [[van-der-waals-equation]] — discussed as an empirical extension of the perfect-gas equation to real fluids.
- [[absolute-temperature]] — defined rigorously via the Second Law (reversible Carnot cycle), independently of any particular thermometric substance.

## Quotes

> "It is in no way possible, either by mechanical, thermal, chemical, or other devices, to obtain perpetual motion, i.e. it is impossible to construct an engine which will work in a cycle and produce continuous work, or kinetic energy, from nothing." (§55)

> "It is impossible to construct an engine which will work in a complete cycle, and produce no effect except the raising of a weight and the cooling of a heat-reservoir." (§116 — the Second Law axiom)

> "If a system of perfect gases pass in any way from one state to another, and no changes remain in surrounding bodies, the entropy of the system is certainly not smaller, but either greater than, or, in the limit, equal to that of the initial state; in other words, the total change of the entropy ≥ 0." (§126)
