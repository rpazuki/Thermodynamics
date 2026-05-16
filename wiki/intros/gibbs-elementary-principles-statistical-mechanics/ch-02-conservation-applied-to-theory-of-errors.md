---
title: "Ch. II — Application of Conservation of Extension-in-Phase to the Theory of Errors"
type: concept
tags: [statistical-mechanics, phase-space, probability, error-theory, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter II: Application of Conservation of Extension-in-Phase to the Theory of Errors

## Overview

Chapter II is a brief but elegant application of Chapter I's Liouville theorem to the classical "theory of errors" — the Gaussian treatment of uncertainties in initial conditions. It shows that the conservation of phase-space volume constrains how uncertainty propagates in time, and that the maximum probability coefficient is an absolute invariant of the motion.

## Setup: Uncertainty in Initial Conditions

Gibbs supposes that the differential equations of motion are known exactly, but the initial conditions (the constants of integration) are only approximately determined. The probability that the phase at time $t'$ lies within an infinitesimal element is written as

$$e^{\eta'}\, dp_1' \cdots dq_n',$$

where $\eta'$ is the *index of probability* — a function of all momenta and coordinates.

## Gaussian Approximation

Let $(P_1', Q_1', \dots)$ be the phase of maximum probability at time $t'$. Expanding $\eta'$ to second order around this maximum:

$$\eta' = c - F',$$

where $c$ is the value at the maximum and $F'$ is a positive-definite quadratic form in the deviations $p_i' - P_i'$, $q_i' - Q_i'$. Writing $C = e^c$ for the maximum coefficient of probability, the probability within any phase element is approximately

$$C\, e^{-F'}\, dp_1' \cdots dq_n'.$$

## Conservation of Maximum Probability

By the conservation of probability of phase (a direct corollary of Liouville's theorem), the maximum probability coefficient $C$ is an absolute invariant: it does not change as the system evolves from time $t'$ to time $t''$. Moreover, the most probable phase at $t''$ is precisely the phase that evolved (via Hamilton's equations) from the most probable phase at $t'$.

At time $t''$ the distribution is likewise Gaussian:

$$C\, e^{-F''}\, dp_1'' \cdots dq_n'',$$

where $F''$ is a new quadratic form in the deviations at $t''$. The normalisation condition

$$\int C\, e^{-F'}\, dp' \cdots dq' = 1 \implies \frac{C\pi^n}{\sqrt{f'}} = 1,$$

where $f'$ is the discriminant of $F'$, shows that this discriminant is also a constant of the motion — another corollary of Liouville's theorem.

## Physical Significance

This chapter demonstrates that the shape of an uncertainty ellipsoid in phase space changes over time (it can shear and distort), but its $2n$-dimensional volume is preserved. The maximum probability density $C$ cannot decrease or increase: whatever we do not know at the initial moment, we cannot know more (or less) later. This is a mechanical expression of what thermodynamics would call the impossibility of decreasing entropy by waiting — though Gibbs does not yet use the word entropy here.

The chapter is largely a pedagogical demonstration that the theory-of-errors treatment and the ensemble framework are mutually consistent, preparing the reader for the more general canonical distribution introduced in Chapter IV.

---

*[↑ Table of Contents](toc.md) · [← Back: Ch. I — General Notions](ch-01-general-notions-conservation-extension-in-phase.md) · [Next: Ch. III — Integration of Equations of Motion →](ch-03-conservation-applied-to-integration-of-equations-of-motion.md)*
