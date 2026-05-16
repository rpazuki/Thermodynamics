---
title: "Ch. XII — On the Motion of Systems and Ensembles through Long Periods of Time"
type: concept
tags: [statistical-mechanics, recurrence, ergodicity, statistical-equilibrium, irreversibility, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter XII: On the Motion of Systems and Ensembles of Systems through Long Periods of Time

## Overview

Chapter XII addresses the question of long-time dynamical behaviour: Will a system return to its initial phase? Will an ensemble approach statistical equilibrium over time? Gibbs proves a version of the Poincaré recurrence theorem and discusses, carefully and honestly, the *tendency* toward equilibrium — without claiming to have proved irreversibility from reversible mechanics.

## The Recurrence Theorem

Gibbs proves: if an ensemble of systems is initially distributed with uniform density over a finite extension-in-phase (between two energy limits $\varepsilon_1 < \varepsilon < \varepsilon_2$), then the number of systems that leave this extension and never return is less than any assignable fraction of the total. The proof uses conservation of extension-in-phase (Liouville's theorem). The "front" of the ensemble — the systems that first leave the region — sweeps out equal phase volumes in equal times. Since the accessible phase volume is finite, the front must eventually revisit regions it has previously passed through, implying return.

This is essentially the Poincaré recurrence theorem (1890), proved here within Gibbs's ensemble framework. Gibbs illustrates it with a rigid body under no forces, where three cases arise: periodic motion, quasi-periodic approach (never exactly returning but coming arbitrarily close), and non-return on a set of zero measure.

## Tendency Toward Statistical Equilibrium

Gibbs then addresses whether an ensemble that is *not* in statistical equilibrium will approach equilibrium over time. He is careful here. He notes that:

1. For certain simple systems (e.g., a harmonic oscillator with period independent of energy), there is no tendency toward equilibrium at all.
2. For more general systems, the *coarse-grained* density-in-phase (averaged over small but finite phase-space cells) tends to become more uniform, while the fine-grained density is exactly conserved by Liouville's theorem.

This distinction — fine-grained versus coarse-grained entropy — is Gibbs's framework for understanding irreversibility. The fine-grained entropy $-\int P \log P\, dp\, dq$ is invariant under Hamiltonian evolution; it is the coarse-grained version that increases. Gibbs does not resolve the tension but describes it with precision, acknowledging that a full explanation of irreversibility "presents a problem which is far from simple."

## Average Index and Approach to Equilibrium

For the canonical ensemble, any finite sub-ensemble will return to an arbitrary neighbourhood of its initial state infinitely often. Yet the ensemble as a whole, through the mixing of trajectories with different periods, develops finer and finer structure in phase space — appearing, at any coarse resolution, to approach uniformity. This is the mechanism of *mixing* in the modern sense of ergodic theory.

## Significance

Chapter XII is Gibbs's most careful engagement with the foundations of the second law. He refuses to assert a derivation of irreversibility from reversible mechanics (a refusal that was philosophically honest but ultimately prescient: no classical derivation exists without additional assumptions). Instead he identifies the coarse-grained/fine-grained distinction as the conceptual key — an insight that was not fully formalised until the development of ergodic theory and information theory in the mid-twentieth century. Boltzmann faced similar foundational difficulties; Gibbs's ensemble approach sidesteps some of them by working with populations of systems rather than individual trajectories.

---

*[↑ Table of Contents](toc.md) · [← Back: Ch. XI — Maximum and Minimum Properties](ch-11-maximum-minimum-properties.md) · [Next: Ch. XIII — Effect of Various Processes →](ch-13-effect-of-various-processes-on-ensemble.md)*
