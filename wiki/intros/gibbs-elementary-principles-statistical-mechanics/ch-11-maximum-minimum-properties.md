---
title: "Ch. XI — Maximum and Minimum Properties of Various Distributions"
type: concept
tags: [statistical-mechanics, entropy-maximum, canonical-distribution, variational-principle, h-theorem, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter XI: Maximum and Minimum Properties of Various Distributions in Phase

## Overview

Chapter XI provides the variational foundation of the canonical distribution: it proves that the canonical distribution minimises the average index of probability $\bar{\eta}$ (equivalently, maximises entropy) subject to constraints on the energy distribution. This is the statistical-mechanical analogue of the thermodynamic maximum-entropy principle, and it also serves as Gibbs's analogue of Boltzmann's H-theorem.

## Theorem I: Minimum Average Index for Fixed Energy Distribution

Among all distributions in phase that produce the same distribution in energy (i.e., the same probability density $p(\varepsilon)$), the one that minimises $\bar{\eta}$ is the one where the index $\eta$ depends only on energy. The proof is direct: any deviation $\Delta\eta$ from an energy-function index that preserves the energy distribution leads to

$$\int \Delta\eta\, e^{\Delta\eta} + 1 - e^{\Delta\eta}) e^\eta\, dp\, dq > 0,$$

since $x e^x + 1 - e^x \geq 0$ with equality only at $x = 0$.

## Theorem II: Canonical Distribution Minimises Average Index at Fixed Average Energy

Among all distributions with the same average energy $\bar{\varepsilon}$, the canonical distribution achieves the minimum value of $\bar{\eta}$. This is the key result: the canonical distribution is the *unique* maximum-entropy distribution subject to a constraint on the mean energy. Any other distribution with the same $\bar{\varepsilon}$ has a larger $\bar{\eta}$ and hence lower (negated) entropy.

## Theorem III: Free-Energy Minimum

For any positive constant $\Theta$, the average of $\eta + \varepsilon/\Theta$ is minimised by the canonical distribution of modulus $\Theta$. This generalises Theorem II and provides a direct mechanical analogue of the thermodynamic principle that the Helmholtz free energy $F = U - TS$ is minimised at equilibrium (at constant temperature $T$). In the canonical ensemble $\eta + \varepsilon/\Theta = \psi/\Theta$ is constant, so its average equals $\psi/\Theta$ — the minimum attainable value.

## Theorems IV–VI: Generalisations

These extend the above results to distributions where the index is a linear function of arbitrary phase functions $F_1, F_2, \dots$ rather than just energy. The structure is identical: the distribution that minimises $\bar{\eta}$ subject to fixed average values of $F_1, F_2, \dots$ is the one with $\eta$ a linear function of $F_1, F_2, \dots$

## Theorem VII: Additivity and Subadditivity of Average Indices

If a system consists of two parts, the average index of the whole is *greater than or equal to* the sum of the average indices of the parts (when each part is described by its marginal distribution):

$$\bar{\eta}_{\text{whole}} \geq \bar{\eta}_1 + \bar{\eta}_2,$$

with equality if and only if the phases of the two parts are statistically independent. This is the classical analogue of the subadditivity of quantum entropy, and it expresses the fact that correlations between parts of a system always reduce the overall entropy below the sum of the parts' entropies. When parts are uncorrelated (e.g., in a canonical ensemble of non-interacting subsystems), equality holds.

## Significance

Chapter XI provides the rigorous foundation for the maximum-entropy interpretation of equilibrium statistical mechanics: the canonical distribution is not merely *a* distribution consistent with a given temperature, it is the *unique* distribution that contains no more information than is required by the constraint on mean energy. This is the deepest justification for using the Boltzmann distribution, and it anticipates the information-theoretic viewpoint (later developed by Jaynes) in which statistical mechanics is the application of maximum-entropy inference to physical systems.
