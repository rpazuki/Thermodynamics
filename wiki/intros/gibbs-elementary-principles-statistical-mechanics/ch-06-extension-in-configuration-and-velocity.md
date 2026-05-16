---
title: "Ch. VI — Extension in Configuration and Extension in Velocity"
type: concept
tags: [statistical-mechanics, phase-space, configuration-space, velocity-space, coordinate-invariance, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter VI: Extension in Configuration and Extension in Velocity

## Overview

Chapter VI introduces a finer decomposition of phase-space concepts that will be essential in subsequent chapters. Gibbs separates the $2n$-dimensional phase space into an $n$-dimensional *configuration space* (the $q_i$) and the fibres of *velocity space* (the $\dot{q}_i$ or equivalently $p_i$) above each configuration, defining coordinate-invariant measures on each.

## Decomposition of Phase Space

The full phase volume element can be written as a product:

$$dp_1 \cdots dp_n\, dq_1 \cdots dq_n = \Delta_{\dot{q}}\, d\dot{q}_1 \cdots d\dot{q}_n\, dq_1 \cdots dq_n,$$

where $\Delta_{\dot{q}} = \det(\partial p_i / \partial \dot{q}_j)$ is the determinant relating momenta to velocities (essentially the kinetic-energy metric). This suggests defining:

- **Extension-in-configuration**: the integral $\int \Delta_{\dot{q}}^{1/2}\, dq_1 \cdots dq_n$ — a measure on configuration space that is independent of the coordinate system chosen.
- **Extension-in-velocity**: the integral $\int \Delta_p^{1/2}\, dp_1 \cdots dp_n$ (or equivalently $\int \Delta_{\dot{q}}^{1/2}\, d\dot{q}_1 \cdots d\dot{q}_n$) — a measure on the velocity fibre above each configuration.

## Coordinate Invariance

Gibbs proves that these extensions are genuine invariants: changing the generalised coordinates from $(q_1, \dots, q_n)$ to $(Q_1, \dots, Q_n)$ leaves the numerical values unchanged, just as the full phase-volume extension is coordinate-invariant (from Chapter I). The proof uses the identity

$$\frac{d(P_1, \dots, P_n)}{d(p_1, \dots, p_n)} = \frac{d(q_1, \dots, q_n)}{d(Q_1, \dots, Q_n)},$$

which follows from the bilinear structure of the kinetic energy.

## Density-in-Configuration and Density-in-Velocity

Analogously to the density-in-phase $D$, Gibbs defines a *density-in-configuration* $D_q$ and an *index of probability of configuration* $\eta_q = \log(D_q/N)$. For a canonical ensemble:

$$\eta_q = \frac{\psi_q - \varepsilon_q}{\Theta},$$

where $\psi_q$ is determined by $e^{-\psi_q/\Theta} = \int e^{-\varepsilon_q/\Theta}\, \Delta_{\dot{q}}^{1/2}\, dq_1 \cdots dq_n$ — a "configurational partition function." Similarly, the density-in-velocity at a given configuration has index $\eta_p = (\psi_p - \varepsilon_p)/\Theta$.

The factorisation $\eta = \eta_q + \eta_p$ and $\psi = \psi_q + \psi_p$ holds for the canonical distribution, reflecting the independence of configuration and velocity statistics.

## Dimensional Analysis

An extension-in-velocity has dimensions of $(\text{energy})^{n/2}$; an extension-in-configuration has dimensions of $(\text{time})^n (\text{energy})^{n/2}$. Their product is the extension-in-phase with dimensions of $(\text{action})^n$, consistent with Chapter I.

## Significance

The separation of phase space into configuration and velocity spaces has two practical uses: (1) it allows the Gaussian velocity integrals of Chapter V to be separated cleanly from the configurational averages, and (2) it introduces the configurational partition function $e^{-\psi_q/\Theta}$, which is more directly connected to potential-energy landscapes (such as the Boltzmann factor for potential-energy distributions). These notions underlie much of modern computational statistical mechanics, including Monte Carlo sampling in configuration space.
