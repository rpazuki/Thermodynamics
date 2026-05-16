---
title: "Ch. VII — Further Discussion of Averages in a Canonical Ensemble"
type: concept
tags: [statistical-mechanics, canonical-distribution, fluctuations, entropy, clausius, average-energy, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter VII: Further Discussion of Averages in a Canonical Ensemble of Systems

## Overview

Chapter VII deepens the analysis of average values begun in Chapter V. It derives additional thermodynamic differential relations from the configurational partition function, makes an explicit and historically significant connection to Clausius's entropy formulas, computes mean-square fluctuations of energy, and demonstrates that these fluctuations become negligible when the number of degrees of freedom is very large.

## Differential Relations for Potential and Kinetic Energies

From the configurational partition function $e^{-\psi_q/\Theta} = \int e^{-\varepsilon_q/\Theta}\,\Delta_{\dot{q}}^{1/2}\, dq_1 \cdots dq_n$, differentiating with respect to $\Theta$ and external coordinates $a_i$ gives

$$d\bar{\varepsilon}_q = -\Theta\, d\bar{\eta}_q - \bar{A}_1\, da_1 - \bar{A}_2\, da_2 - \cdots$$

Gibbs notes explicitly that this differential relation — connecting average potential energy, the modulus, the average index of probability of configuration (taken negatively), and the external forces — is **identical in form** with the relations stated by Clausius for the potential energy of a body, its temperature, the disgregation, and the external forces. Similarly, the kinetic energy relation $d\bar{\varepsilon}_p = -\Theta\, d\bar{\eta}_p$ corresponds to what Clausius called the "transformation-value of the kinetic energy." This identification makes precise the claim that Gibbs's ensemble averages recover classical thermodynamics.

## Mean-Square Fluctuations of Energy

Differentiating the average energy identity $\bar{\varepsilon} = \psi - \Theta\, d\psi/d\Theta$ again with respect to $\Theta$ leads to

$$\overline{\varepsilon^2} = \bar{\varepsilon}^2 + \Theta^2\, \frac{d\bar{\varepsilon}}{d\Theta}.$$

Hence the mean-square *anomaly* (fluctuation) of the energy is

$$\overline{(\varepsilon - \bar{\varepsilon})^2} = \Theta^2\, \frac{d\bar{\varepsilon}}{d\Theta}.$$

Since $d\bar{\varepsilon}/d\Theta \sim \tfrac{1}{2}n$ (from equipartition, $\bar{\varepsilon}_p = \tfrac{1}{2}n\Theta$), the relative fluctuation satisfies

$$\frac{\overline{(\varepsilon - \bar{\varepsilon})^2}}{\bar{\varepsilon}^2} \sim \frac{1}{n}.$$

For $n$ of order $10^{23}$, this is of order $10^{-23}$: the fluctuation is utterly imperceptible. This is the mathematical demonstration that statistical mechanics predicts sharp thermodynamic quantities for macroscopic systems. The same argument applies to the index of probability $\eta$ and to the external forces $A_i$ (when they depend mainly on energy). The conclusion is that the sign of average in the fundamental relation $d\bar{\varepsilon} = -\Theta\, d\bar{\eta} - \cdots$ is operationally irrelevant for large systems, and macroscopic thermodynamics emerges exactly.

## Derivatives of $\psi$ as a Generating Function

The chapter also establishes that $\psi$ functions as a generating function for all moments of the energy distribution:

$$\overline{\varepsilon^2} = \left(\psi - \Theta\frac{d\psi}{d\Theta}\right)^2 - \Theta^3\frac{d^2\psi}{d\Theta^2}.$$

Higher moments and mixed moments (e.g., correlations between energy and external forces) can be obtained by further differentiation. This is the prototype of the modern statement that all thermodynamic quantities follow from the free energy as a function of temperature and external parameters.

## Significance

Chapter VII is the chapter where the equivalence between Gibbs's statistical mechanics and Clausius's classical thermodynamics is made explicit and mathematically rigorous. The identification of Clausius's entropy with $-\bar{\eta}$ (the negative average index of probability) is stated precisely. More importantly, the fluctuation calculation explains *why* this identification works: for large systems, every system in the ensemble is essentially at the average value, so ensemble averages equal thermodynamic quantities without qualification.
