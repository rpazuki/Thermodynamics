---
title: "Ch. IV — On the Distribution in Phase Called Canonical"
type: concept
tags: [statistical-mechanics, canonical-distribution, partition-function, ensemble, temperature, gibbs, free-energy]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter IV: On the Distribution in Phase Called Canonical, in which the Index of Probability is a Linear Function of the Energy

## Overview

Chapter IV introduces the most important single concept in the book: the *canonical distribution*. This is the probability distribution over phase space that governs statistical equilibrium when a system can exchange energy with a thermal reservoir. It is the direct ancestor of what is today called the Boltzmann distribution or the Gibbs canonical ensemble, and it provides the microscopic basis for temperature and free energy.

## Statistical Equilibrium

The condition of statistical equilibrium is

$$\sum_i \left(\frac{\partial P}{\partial p_i}\dot{p}_i + \frac{\partial P}{\partial q_i}\dot{q}_i\right) = 0,$$

where $P$ is the probability coefficient. This is satisfied if $P$ is any function of conserved quantities, and for conservative systems the energy $\varepsilon$ is conserved. Hence $P = f(\varepsilon)$ is the general form of an equilibrium distribution.

## The Canonical Distribution

Among all possible choices of $f(\varepsilon)$, Gibbs singles out the one where the *index of probability* $\eta = \log P$ is a linear function of the energy:

$$\eta = \frac{\psi - \varepsilon}{\Theta}, \qquad \text{i.e.} \qquad P = e^{(\psi - \varepsilon)/\Theta}.$$

Here $\Theta > 0$ is the *modulus of distribution* (a quantity with the dimensions of energy) and $\psi$ is a constant determined by normalisation:

$$e^{-\psi/\Theta} = \int e^{-\varepsilon/\Theta}\, dp_1 \cdots dq_n.$$

This integral is precisely the *partition function* in modern notation (though Gibbs does not use that term). The constant $\psi$ has the dimensions of energy and is a function of $\Theta$ and the external coordinates $a_1, a_2, \dots$

## Why This Distribution?

Gibbs justifies the canonical form on two grounds:

1. **Factorisation property**: If a system consists of two non-interacting subsystems $A$ (with energy $\varepsilon_A$) and $B$ (with energy $\varepsilon_B$) having the *same* modulus $\Theta$, the joint distribution factorises:

$$P_{AB} = e^{(\psi_A + \psi_B - \varepsilon_A - \varepsilon_B)/\Theta} = P_A \cdot P_B.$$

No other distribution has this property of compositional consistency. This makes $\Theta$ an intensive quantity — the analogue of temperature.

2. **Simplicity**: The distribution is the most natural one satisfying all normalisation and non-negativity requirements, and it has the highest information-theoretic significance (minimum average index, proved rigorously in Chapter XI).

## The Differential Equation — Thermodynamic Analogy

Differentiating the partition function with respect to $\Theta$ and the external coordinates $a_i$ yields

$$d\psi = \bar{\eta}\, d\Theta - \bar{A}_1\, da_1 - \bar{A}_2\, da_2 - \cdots,$$

and since $\psi = \bar{\varepsilon} + \Theta\bar{\eta}$, this can be rewritten as

$$d\bar{\varepsilon} = -\Theta\, d\bar{\eta} - \bar{A}_1\, da_1 - \bar{A}_2\, da_2 - \cdots.$$

This is structurally identical to the thermodynamic fundamental relation $dU = T\, dS - \delta W$. The modulus $\Theta$ corresponds to absolute temperature $T$, and $-\bar{\eta}$ (the average index with sign reversed) corresponds to entropy $S$. The quantity $\psi$ (which equals $\bar{\varepsilon} + \Theta\bar{\eta}$) corresponds to the Helmholtz free energy. The external forces $\bar{A}_i$ are the average generalised forces exerted by the system on external bodies.

## Zero-th Law Analogue

Two systems $A$ and $B$ at the same modulus $\Theta$ are in statistical equilibrium when combined — no net energy flows on average. Different moduli drive energy transfer. This is the mechanical analogue of the zeroth law of thermodynamics and of Carnot's principle that heat flows from hot to cold.

## Relation to [[planck-treatise-on-thermodynamics]]

Planck's treatise (1897) defines temperature operationally and derives entropy as a state function from the two laws. Gibbs's Chapter IV derives the differential relation containing both temperature and entropy from pure mechanics, without any empirical input — showing that these thermodynamic quantities are natural features of the probability distribution over microstates.

---

*[↑ Table of Contents](toc.md) · [← Back: Ch. III — Integration of Equations of Motion](ch-03-conservation-applied-to-integration-of-equations-of-motion.md) · [Next: Ch. V — Average Values →](ch-05-average-values-canonical-ensemble.md)*
