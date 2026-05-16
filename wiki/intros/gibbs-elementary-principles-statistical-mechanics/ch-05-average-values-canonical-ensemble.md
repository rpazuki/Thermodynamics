---
title: "Ch. V — Average Values in a Canonical Ensemble of Systems"
type: concept
tags: [statistical-mechanics, canonical-distribution, equipartition, average-energy, maxwell-distribution, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter V: Average Values in a Canonical Ensemble of Systems

## Overview

Chapter V is where the canonical distribution first makes contact with observable physics. Gibbs computes average kinetic and potential energies, derives the equipartition theorem, and shows that the velocity distribution in a canonical ensemble follows the Maxwell–Boltzmann law. The chapter also establishes crucial formulas for the dependence of average energies on the modulus $\Theta$ and the external coordinates.

## Average Kinetic Energy and Equipartition

For a system of $\nu$ material points with rectangular coordinates, the kinetic energy decomposes into $3\nu$ independent quadratic terms in the velocity components. Because the canonical distribution factorises over velocity components, the average of each term $\tfrac{1}{2}m_i \dot{x}_i^2$ can be evaluated by a Gaussian integral:

$$\int_{-\infty}^{\infty} \tfrac{1}{2} m\dot{x}^2 \, e^{-m\dot{x}^2/(2\Theta)}\, m\, d\dot{x} = \sqrt{\tfrac{1}{2}\pi m\Theta^3}, \qquad \int_{-\infty}^{\infty} e^{-m\dot{x}^2/(2\Theta)}\, m\, d\dot{x} = \sqrt{2\pi m\Theta}.$$

Dividing these gives the average kinetic energy per velocity component: $\tfrac{1}{2}\Theta$. For a system with $n = 3\nu$ degrees of freedom, the total average kinetic energy is

$$\bar{\varepsilon}_p = \tfrac{1}{2} n\Theta.$$

This is the **equipartition theorem**: every quadratic degree of freedom contributes $\tfrac{1}{2}\Theta$ to the average energy. The result is independent of the particular configuration and holds for any conservative system where the kinetic energy is a quadratic function of the momenta — a condition satisfied by any Lagrangian mechanical system.

In the more general case, for any system of $n$ degrees of freedom with kinetic energy quadratic in the momenta, integration by parts shows that the average of each term $\tfrac{1}{2} p_i (\partial \varepsilon / \partial p_i)$ equals $\tfrac{1}{2}\Theta$, confirming $\bar{\varepsilon}_p = \tfrac{1}{2}n\Theta$ generally.

## Maxwell–Boltzmann Velocity Distribution

The probability that a component velocity $\dot{x}_1$ lies between given limits is

$$\left(\frac{m_1}{2\pi\Theta}\right)^{1/2} \int e^{-m_1 \dot{x}_1^2 / (2\Theta)}\, d\dot{x}_1.$$

In the scaled variable $s = (m_1/2\Theta)^{1/2}\dot{x}_1$ — the ratio of the velocity to that which would give kinetic energy $\Theta$ — this becomes the standard Gaussian $\pi^{-1/2} e^{-s^2}\, ds$. This is the Maxwell speed distribution derived from first principles using ensemble theory, without Maxwell's original kinetic-theory argument.

## Distribution in Configuration

The probability that the configuration lies within given limits, irrespective of velocities, is proportional to $e^{(\psi - \varepsilon_q)/\Theta}$ (after integrating out all velocity degrees of freedom analytically). The potential energy $\varepsilon_q$ determines the spatial probability density, with low-energy configurations weighted exponentially more heavily.

## Derivatives of the Partition Function

Gibbs establishes the general formulas by differentiating $e^{-\psi/\Theta} = \int e^{-\varepsilon/\Theta} dp\, dq$ with respect to $\Theta$ and with respect to external coordinates $a_i$:

$$\bar{\varepsilon} = \psi - \Theta \frac{d\psi}{d\Theta}, \qquad \bar{A}_i = -\frac{d\psi}{da_i}.$$

These show that all thermodynamic averages (energy, forces) can be derived from the single function $\psi(\Theta, a_1, a_2, \dots)$ — the free energy. This is the prototype of what later became the central principle of equilibrium statistical mechanics: all thermodynamic information is encoded in the partition function.

## Significance

Chapter V demonstrates that the modulus $\Theta$ controls the energy scale of the system. When $\Theta$ is small, the ensemble is concentrated near low-energy configurations; as $\Theta$ increases, higher-energy states become accessible. The identification $\Theta = k_B T$ (Boltzmann's constant times temperature) is the bridge to macroscopic thermodynamics, a connection made fully explicit in Chapter XIV.

---

*[↑ Table of Contents](toc.md) · [← Back: Ch. IV — The Canonical Distribution](ch-04-canonical-distribution.md) · [Next: Ch. VI — Extension in Configuration and Velocity →](ch-06-extension-in-configuration-and-velocity.md)*
