---
title: "Ch. XIII — Effect of Various Processes on an Ensemble of Systems"
type: concept
tags: [statistical-mechanics, thermodynamic-processes, heat, work, carnot-cycle, entropy, irreversibility, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter XIII: Effect of Various Processes on an Ensemble of Systems

## Overview

Chapter XIII is the most directly physical chapter of the book. It analyses what happens to an ensemble when external parameters are varied (mechanical work) or when two ensembles interact (thermal contact), and it derives the mechanical analogues of the laws of thermodynamics: the non-decrease of entropy, the direction of heat flow, and the Carnot cycle.

## Two Types of External Influence

Gibbs distinguishes two ways the outside world can affect an ensemble:

1. **Variation of external coordinates** $a_i$: the parameters of the force field (e.g., volume) change. This corresponds to *mechanical work* — the bodies producing the forces are precisely defined (not distributed in phase). An abrupt change in external coordinates does not instantly change the phase of any system or alter $\bar{\eta}$, but it disturbs statistical equilibrium, allowing $\bar{\eta}$ to decrease subsequently.

2. **Interaction with another ensemble**: two ensembles are brought into dynamical contact. Both sets of systems are distributed in phase, so the interaction is inherently probabilistic. This corresponds to *thermal action* — heat transfer.

## Average Index Can Only Decrease or Stay the Same

For any variation of external coordinates, Gibbs shows that the average index $\bar{\eta}$ can only decrease or remain unchanged. If the variation is slow (quasi-static), the decrease is negligible (of second order in the magnitude of the change). For rapid changes, the decrease can be substantial. This is the mechanical analogue of the entropy-increase principle: mechanical manipulations alone cannot decrease entropy (increase $-\bar{\eta}$), and quasi-static reversible processes are the limiting case where entropy is conserved.

## Thermal Contact and Direction of Energy Flow

When two ensembles with different moduli $\Theta_1 > \Theta_2$ are brought into contact (allowed to exchange energy), the average result is a net transfer of energy from the ensemble of higher modulus to that of lower modulus. This is the mechanical derivation of the second law's direction: heat flows from hot to cold (higher modulus = higher temperature). At equal moduli, the combined system is already in statistical equilibrium with respect to energy exchange.

The sum of average indices $\bar{\eta}_1 + \bar{\eta}_2$ cannot increase in the interaction — another form of the entropy-increase law.

## The Carnot Cycle Analogue

Gibbs constructs a mechanical analogue of Carnot's cycle consisting of four steps:
1. Quasi-static variation of external coordinates on a canonical ensemble at modulus $\Theta_1$ (isothermal expansion analogue).
2. Adiabatic change: rapid (or careful quasi-static) variation of external coordinates that changes the modulus from $\Theta_1$ to $\Theta_2$.
3. Quasi-static variation at modulus $\Theta_2$ (isothermal compression analogue).
4. Return to original state.

The conclusion mirrors Carnot's: the maximum efficiency of the cycle depends only on the two moduli $\Theta_1$ and $\Theta_2$, not on the nature of the systems. This provides the mechanical justification for Carnot's result — which, in [[planck-treatise-on-thermodynamics]], Planck derives from the empirical impossibility of a perpetual motion machine of the second kind. Gibbs derives the same result from Hamiltonian mechanics and probability theory.

## Significance

Chapter XIII is where statistical mechanics becomes thermodynamics. The abstract ensemble machinery is shown to reproduce all the central thermodynamic phenomena: entropy increase, heat flow direction, and Carnot efficiency — all emerging from Liouville's theorem and the canonical distribution. The distinction between mechanical action (change of external coordinates) and thermal action (ensemble-ensemble interaction) maps precisely onto the thermodynamic distinction between work and heat.
