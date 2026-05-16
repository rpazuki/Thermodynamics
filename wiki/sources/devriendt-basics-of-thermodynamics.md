---
title: "Basics of Thermodynamics"
type: source
tags: [thermodynamics, pedagogy, zeroth-law, first-law, second-law, third-law, entropy, carnot-cycle, statistical-mechanics, free-energy]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

## Citation

Devriendt, Julien. *Basics of Thermodynamics* (lecture notes). No publication date given; author affiliation not stated in document. Approximately 55 pages.

## Raw path

`raw/Thermodynamics/Papers/basic_thermo.pdf`

## Summary

This is a concise, pedagogical set of lecture notes covering classical [[thermodynamics]] from first principles. The text works through all four laws of thermodynamics in logical sequence, developing the vocabulary of thermodynamic systems, states, and equilibrium before introducing internal energy, work, and heat via the first law. A detailed treatment of the [[carnot-cycle]] and the [[carnot-cycle|Carnot engine]] leads naturally to the [[second-law-of-thermodynamics]] and Clausius's theorem, from which [[entropy]] is defined as a state function. The second half covers practical thermodynamics through thermodynamic potentials (Helmholtz and Gibbs free energies, enthalpy), Maxwell's relations, thermodynamic coefficients, and open systems with chemical potential. The notes conclude with a generalisation of thermodynamic work beyond pressure–volume expansion, illustrated with an elastic rod. The text assumes no microscopic theory and is self-contained as a macroscopic, phenomenological account.

## Key claims

- A thermodynamic macrostate is characterised by four variables: pressure $p$, temperature $T$, volume $V$, and particle number $N$; only two of the intensive variables ($p$, $T$) and one extensive variable are independently variable for a closed system in equilibrium (source: basic_thermo.pdf).
- The zeroth law — transitivity of thermal equilibrium — is stated as a prerequisite for defining temperature as a meaningful thermodynamic variable (source: basic_thermo.pdf).
- The first law in differential form is $dU = \delta Q - \delta W$; internal energy $U$ is a function of state, whereas heat $Q$ and work $W$ are path-dependent (source: basic_thermo.pdf).
- The [[carnot-cycle]] consists of two reversible isothermal and two reversible adiabatic processes; its efficiency $\eta_C = 1 - T_2/T_1$ is the maximum achievable between two reservoirs and depends only on temperatures (source: basic_thermo.pdf).
- Clausius's theorem states $\oint dQ/T \leq 0$ with equality for reversible cycles; this leads to the definition of [[entropy]] $S$ via $dS = \delta Q_{\rm rev}/T$, which is a state function (source: basic_thermo.pdf).
- For an isolated system, equilibrium corresponds to maximum entropy; depending on the thermodynamic constraints (fixed $T$ and $p$, fixed $T$ and $V$, etc.), the equilibrium condition corresponds to minimisation of the Gibbs free energy $G$, Helmholtz free energy $F$, enthalpy $H$, or internal energy $U$ respectively (source: basic_thermo.pdf).
- Maxwell's four relations, derived from the exactness of the differentials of the four potentials, relate hard-to-measure partial derivatives to experimentally accessible ones; e.g. $(\partial S/\partial V)_T = (\partial p/\partial T)_V$ (source: basic_thermo.pdf).
- For open systems, the chemical potential $\mu \equiv (\partial G/\partial N)_{T,p}$ is introduced as the intensive conjugate to particle number $N$; diffusive equilibrium requires equal $\mu$ across the boundary (source: basic_thermo.pdf).
- Thermodynamic work is not restricted to $p\,dV$: the framework applies to elastic rods ($dW = t\,dL$), liquid films ($dW = \gamma\,dA$), dielectric and magnetic materials; the elastic-rod example illustrates how entropy and tension are related via a Maxwell relation (source: basic_thermo.pdf).

## Methods

The notes adopt a purely macroscopic, axiomatic approach to thermodynamics, introducing concepts through formal definitions followed by worked examples and exercises. Statistical mechanics is mentioned but not developed; the microscopic interpretation of entropy is alluded to (disorder, microstates) without formal derivation. Proofs of key theorems (Carnot, Clausius) use standard constructive arguments (decomposing arbitrary cycles into elementary Carnot sub-cycles). Real engines (Otto, Diesel) are discussed as applications. Mathematical tools include partial differential calculus, exact and inexact differentials, the reciprocity and reciprocal theorems, and convexity arguments.

## Limitations

- The statistical mechanical foundation of thermodynamics is left implicit; there is no derivation of entropy from microstates or any discussion of the Boltzmann formula $S = k_B \ln \Omega$.
- The treatment of irreversible processes is limited to the statement of Clausius's inequality; there is no discussion of entropy production or non-equilibrium thermodynamics.
- No discussion of the third law of thermodynamics (Nernst theorem) or of phase transitions beyond a passing mention of open systems.
- As lecture notes, the text lacks a bibliography or references to primary or secondary literature.
- The [[caloric-theory]] is mentioned historically (Lavoisier's "caloric") but not developed.

## Connections

- Provides the axiomatic macroscopic framework within which sources such as [[brush-kinetic-theory-randomness-irreversibility]] and [[lieb-yngvason-mathematics-second-law]] operate.
- The [[carnot-cycle]] treatment connects to [[carnot-reflections-motive-power-of-heat]] (original source) and [[planck-treatise-on-thermodynamics]] (systematic development).
- The definition of [[entropy]] via Clausius's theorem is the classical route that [[lieb-yngvason-mathematics-second-law]] seeks to replace with a more rigorous axiomatic derivation.
- Maxwell's relations and thermodynamic potentials are central tools in applications of [[thermodynamics]] to chemistry, biology, and engineering.

## Quotes

> "Thermodynamics is the study of how heat moves around in 'macroscopic' objects. [...] One important thing to remember is that what looks obvious to the modern physicist, was not so in the 18th and early 19th century, when Thermodynamics was developed!" (source: basic_thermo.pdf, p. 9)

> "The [form of availability] is strangely reminiscent of that of the Gibbs free energy ..." (source: basic_thermo.pdf, p. 50)

> "Not only do the electric and magnetic work involve a dot product between vectors, but a different differential form to that we have just defined will be used in most problems. This is due to the fact that the system [...] will generally be plunged in an external (vacuum) field, and that we will only be interested in the work that is associated with changing the polarization/magnetization of the material rather than in the work associated with changing the external field." (source: basic_thermo.pdf, p. 55)
