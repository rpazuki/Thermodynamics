---
title: "Ch. XV — Systems Composed of Molecules"
type: concept
tags: [statistical-mechanics, grand-ensemble, chemical-potential, entropy-of-mixing, indistinguishable-particles, gibbs-paradox, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter XV: Systems Composed of Molecules

## Overview

Chapter XV is the final and most forward-looking chapter, extending the entire framework to systems where the number of particles can vary. It introduces the *grand ensemble*, the *chemical potential*, and — most famously — resolves the Gibbs paradox of entropy of mixing by carefully distinguishing between phases defined by *generic* (particle-indistinguishable) and *specific* (particle-distinguishable) criteria.

## Grand Ensembles

A *grand ensemble* is a collection of systems that differ not only in phase but also in particle numbers $\nu_1, \dots, \nu_h$ (for $h$ species). The canonically distributed grand ensemble has density-in-phase

$$\frac{N\, e^{(\Omega + \mu_1\nu_1 + \cdots + \mu_h\nu_h - \varepsilon)/\Theta}}{\nu_1! \cdots \nu_h!}\, dp_1 \cdots dq_n,$$

where $\Omega$ is a normalisation constant, $\mu_i$ are the *chemical potentials* of the $h$ species, and $\Theta$ is the common modulus. The denominator $\nu_1! \cdots \nu_h!$ is the number of specific phases corresponding to a single generic phase (i.e., the number of ways of permuting identical particles), and its presence implements particle indistinguishability.

The grand partition function is

$$e^{-\Omega/\Theta} = \sum_{\nu_1} \cdots \sum_{\nu_h} \frac{e^{(\mu_1\nu_1 + \cdots + \mu_h\nu_h - \psi)/\Theta}}{\nu_1! \cdots \nu_h!},$$

where $e^{-\psi/\Theta}$ is the petit-ensemble partition function for given $(\nu_1, \dots, \nu_h)$.

## Chemical Potentials and Equilibrium with Respect to Particle Exchange

The condition for equilibrium with respect to the number of particles of species $i$ (i.e., the condition that the grand ensemble is stationary with respect to particle exchange between sub-ensembles) is

$$\frac{d\psi_{\text{gen}}}{d\nu_i} = \mu_i,$$

which is the definition of the chemical potential — exactly as in macroscopic thermodynamics. The differential relation for the grand ensemble becomes

$$d\Omega = -\bar{\varepsilon}\, d(1/\Theta) - \sum_i \bar{\nu}_i\, d\mu_i - \cdots,$$

from which all thermodynamic quantities of the open system can be derived.

## Generic versus Specific Phases: The Gibbs Paradox

The chapter's most subtle and historically important contribution is the distinction between *generic phases* (where permutations of identical particles are not counted as distinct) and *specific phases* (where they are). Entropy must be computed from the average index of the *generic* phase distribution $\bar{\eta}_{\text{gen}}$, not the specific one.

The reason: if two identical fluid masses are separated by a partition and then the partition is removed, the entropy should not change (mixing two identical fluids is not a real mixing). But if specific phases are used, the entropy of mixing is $\log(\nu!)$ per species — a non-zero contribution that wrongly makes entropy non-extensive. Using generic phases, $\bar{\eta}_{\text{gen}} - \bar{\eta}_{\text{spec}} = \log(\nu_1! \cdots \nu_h!)$, which exactly cancels the spurious mixing entropy for identical particles. For distinguishable particle species, the same correction gives the correct (positive) entropy of mixing.

This resolution of what came to be called the Gibbs paradox — more than a century before quantum mechanics provided its ultimate resolution — is one of the most prescient contributions of the book.

## Fluctuations in Particle Number

In the grand ensemble, the probability distribution of $\nu_1, \dots, \nu_h$ follows a multivariate Gaussian for large mean values:

$$e^{-(\Delta\nu)^T \cdot D \cdot (\Delta\nu)/(2\Theta)} \quad \text{(schematically)},$$

where $D$ is the matrix of second derivatives of $\psi_{\text{gen}}$ with respect to the $\nu_i$. The relative fluctuations $\Delta\nu_i / \bar{\nu}_i$ are of order $1/\sqrt{\bar{\nu}_i}$ — negligible for macroscopic particle numbers.

## Significance

Chapter XV establishes the grand canonical ensemble, which became the standard framework for all open systems in statistical mechanics: ideal quantum gases, chemical reaction equilibria, phase transitions with variable composition, and the theory of solutions. The chemical potential $\mu_i = d\psi_{\text{gen}}/d\nu_i$ defined here is exactly the quantity that appears in Planck's treatment of chemical equilibrium (see [[planck-treatise-on-thermodynamics]], Part IV). The resolution of the Gibbs paradox through generic phases anticipates the need for quantum indistinguishability and is Gibbs's clearest statement that physical entropy requires treating identical particles as truly interchangeable.

---

*[↑ Table of Contents](toc.md) · [← Back: Ch. XIV — Thermodynamic Analogies](ch-14-discussion-of-thermodynamic-analogies.md) · [Next: Analysis — Four-Layer Structure →](analysis.md)*
