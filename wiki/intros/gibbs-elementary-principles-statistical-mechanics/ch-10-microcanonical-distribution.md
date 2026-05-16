---
title: "Ch. X — On a Distribution in Phase Called Microcanonical"
type: concept
tags: [statistical-mechanics, microcanonical-distribution, fixed-energy, entropy, temperature, phase-volume, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter X: On a Distribution in Phase Called Microcanonical in which all the Systems have the same Energy

## Overview

Chapter X introduces and analyses the *microcanonical distribution* — the ensemble in which every system has precisely the same total energy $\varepsilon$. This is the ensemble most directly connected to the classical picture of an isolated system, and Gibbs shows how it gives rise to an alternative (and for some purposes more natural) set of thermodynamic analogues.

## Definition of the Microcanonical Distribution

The microcanonical distribution arises as the limit of an ensemble with uniform density-in-phase between two closely spaced energy surfaces $\varepsilon'$ and $\varepsilon''$, as $\varepsilon'' - \varepsilon' \to 0$. In this limit all systems have energy exactly $\varepsilon$ and are distributed uniformly over the energy surface in phase space. Equivalently, the microcanonical ensemble can be seen as the limit of a canonical ensemble of very large number of systems whose energy fluctuations become imperceptible.

Microcanonical averages are denoted $\langle u \rangle$ (to distinguish from canonical averages $\bar{u}$). They are computed as surface integrals over the energy shell, expressible as

$$\langle u \rangle = e^{-\phi} \int_{V_q = 0}^{\varepsilon_q = \varepsilon} u\, e^{\phi_p}\, dV_q,$$

where $\phi_p$ is evaluated at kinetic energy $\varepsilon_p = \varepsilon - \varepsilon_q$.

## Partition of Energy Between Kinetic and Potential Parts

In the microcanonical ensemble the kinetic and potential energies fluctuate subject to $\varepsilon_p + \varepsilon_q = \varepsilon$. The average kinetic energy satisfies

$$e^{-\phi} V = \frac{2}{n}\, \langle \varepsilon_p \rangle,$$

and the important relation

$$\frac{d\phi}{d\varepsilon} = \left(\frac{n}{2} - 1\right) \langle \varepsilon_p^{-1} \rangle \quad (n > 2)$$

connects the density-of-states slope directly to average kinetic energy.

## Thermodynamic Differential Equation

Gibbs derives the fundamental differential equation for the microcanonical ensemble:

$$d\varepsilon = e^{-\phi} V\, d(\log V) - \langle A_1 \rangle\, da_1 - \langle A_2 \rangle\, da_2 - \cdots$$

This is structurally identical to the thermodynamic relation $dU = T\, dS - \sum A_i\, da_i$. The correspondences are:
- Temperature $T \leftrightarrow e^{-\phi} V = d\varepsilon / d(\log V)$
- Entropy $S \leftrightarrow \log V$

The quantity $\log V$ — the logarithm of the phase-space volume below energy $\varepsilon$ — is a natural candidate for the microcanonical entropy. It is simpler in some respects than $-\bar{\eta}$ (the canonical entropy), since energy itself (not its average) appears in the differential relation.

## Relation to the Canonical Ensemble

Every canonical ensemble can be decomposed as a continuous superposition of microcanonical ensembles (weighted by the Boltzmann factor $e^{(\psi - \varepsilon)/\Theta}$). Conversely, for large $n$, the microcanonical ensemble at energy $\varepsilon_0$ looks like the canonical ensemble at modulus $\Theta$ satisfying $d\phi(\varepsilon_0)/d\varepsilon = 1/\Theta$ — the equivalence of ensembles.

Gibbs notes that the microcanonical distribution fails (becomes ill-defined) at certain critical energies where $e^\phi$ is infinite, and that analytically the canonical distribution is far more tractable. This assessment has been borne out by the subsequent history of the subject: most calculations in statistical mechanics use canonical or grand canonical ensembles.

## Significance

Chapter X completes the pair of fundamental ensembles. The microcanonical ensemble represents an isolated system with fixed energy; the canonical ensemble represents a system in thermal contact with a reservoir at temperature $\Theta$. Both give the same thermodynamics in the large-$n$ limit, but through different mathematical paths. The identification $S = \log V$ (microcanonical) versus $S = -\bar{\eta}$ (canonical) anticipates the famous Boltzmann formula $S = k_B \ln W$ — where $W$ is the number of accessible microstates — though Gibbs's $V$ is a continuous phase volume rather than a discrete count.
