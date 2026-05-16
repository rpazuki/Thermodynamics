---
title: "Ch. VIII — On Certain Important Functions of the Energies of a System"
type: concept
tags: [statistical-mechanics, density-of-states, phase-volume, partition-function, microcanonical, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter VIII: On Certain Important Functions of the Energies of a System

## Overview

Chapter VIII develops the mathematical machinery for integrating over energy rather than over all phase variables simultaneously. It introduces the *density of states* $e^\phi$ — arguably the most important function in statistical mechanics after the partition function — and establishes exact relations between it and the phase-space volume functions $V$, $V_q$, $V_p$.

## The Phase Volume Function $V$ and the Density of States $e^\phi$

Gibbs defines $V(\varepsilon)$ as the total extension-in-phase (phase-space volume) below energy $\varepsilon$:

$$V = \int_{\varepsilon' < \varepsilon} dp_1 \cdots dq_n.$$

He then introduces

$$\phi = \log \frac{dV}{d\varepsilon},$$

so that $e^\phi = dV/d\varepsilon$ is the *density of states* — the amount of phase space per unit energy interval. The extension-in-phase between energies $\varepsilon'$ and $\varepsilon''$ is $\int_{\varepsilon'}^{\varepsilon''} e^\phi\, d\varepsilon$, and any $2n$-fold integral can be reduced to a simple integral over energy when the integrand depends only on $\varepsilon$.

The probability that the energy of a system in a canonical ensemble lies between $\varepsilon$ and $\varepsilon + d\varepsilon$ is

$$e^{(\psi - \varepsilon)/\Theta + \phi}\, d\varepsilon,$$

and the partition function becomes

$$e^{-\psi/\Theta} = \int_0^\infty e^{-\varepsilon/\Theta + \phi}\, d\varepsilon.$$

## Configurational and Velocity Analogues

The analogous functions $V_q$ (extension-in-configuration below potential energy $\varepsilon_q$) and $V_p$ (extension-in-velocity below kinetic energy $\varepsilon_p$) are defined similarly, with $\phi_q = \log(dV_q/d\varepsilon_q)$ and $\phi_p = \log(dV_p/d\varepsilon_p)$.

For the velocity part, since the kinetic energy is a positive-definite quadratic form in $n$ momenta, the volume of the momentum-space $n$-ball of kinetic energy less than $\varepsilon_p$ is

$$V_p = c_n\, \Delta_p^{-1/2}\, \varepsilon_p^{n/2},$$

where $c_n$ is a known constant (related to the volume of an $n$-ball). Therefore

$$\phi_p = \log \frac{dV_p}{d\varepsilon_p} = \log\left(\frac{n}{2} c_n \Delta_p^{-1/2}\right) + \left(\frac{n}{2} - 1\right)\log \varepsilon_p.$$

This explicit formula shows that $e^{\phi_p}$ is proportional to $\varepsilon_p^{n/2 - 1}$ — the familiar power-law density of states for a classical ideal gas.

## Relation Between $V$, $V_q$, $V_p$

The full phase volume is a convolution of configurational and velocity volumes:

$$V = \int_0^\varepsilon V_q(\varepsilon - \varepsilon_p)\, dV_p(\varepsilon_p) = \int_0^\varepsilon e^{\phi_p(\varepsilon_p)} V_q(\varepsilon - \varepsilon_p)\, d\varepsilon_p.$$

This allows $V$ and $\phi$ for the whole system to be computed from $V_q$ (determined by the potential energy landscape) and $V_p$ (determined by the mass distribution and number of degrees of freedom).

## Large-$n$ Approximations

For large $n$, $\phi_0$ (the value of $\phi$ at the most probable energy) is approximately equal to $-\bar{\eta}$ (the negative average index in the canonical ensemble), up to corrections of order $\log n / n$ that are negligible for macroscopic systems. This establishes the functional equivalence of the canonical-ensemble entropy and the microcanonical density-of-states entropy — a crucial consistency check.

## Significance

The function $\phi = \log(dV/d\varepsilon)$ is Gibbs's version of the microcanonical entropy: $S_{\text{micro}} \propto \phi(\varepsilon)$. The equality $d\phi/d\varepsilon = 1/\Theta$ (proved in Chapter IX) says that the derivative of the microcanonical entropy with respect to energy equals the inverse temperature — this is the fundamental thermodynamic relation $\partial S/\partial E = 1/T$ derived from first principles. Chapter VIII provides the technical infrastructure for this central result.

---

*[↑ Table of Contents](toc.md) · [← Back: Ch. VII — Further Discussion of Averages](ch-07-further-discussion-of-averages.md) · [Next: Ch. IX — The Function φ →](ch-09-function-phi-and-canonical-distribution.md)*
