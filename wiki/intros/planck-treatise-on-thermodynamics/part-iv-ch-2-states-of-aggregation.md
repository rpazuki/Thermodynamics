---
title: "Part IV, Chapter II — Systems in Different States of Aggregation"
type: concept
tags: [phase-equilibrium, clausius-clapeyron, boiling-point, melting-point, critical-point, vapour-pressure, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part IV, Chapter II: Systems in Different States of Aggregation (§§165–196)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This is the largest chapter in Part IV. It treats the equilibrium of a single-component system that can exist in two or three coexisting phases (solid, liquid, gas). The central results are the conditions for phase coexistence (equality of temperature, pressure, and chemical potential), the Clausius–Clapeyron equation governing how equilibrium pressure changes with temperature, and the derivation of the saturation curve, fusion curve, and sublimation curve. The treatment is entirely general — valid for any pure substance — and uses the entropy maximum principle as its foundation.

---

## 1. Problem Setup and Entropy Maximum (§§165–167)

A pure substance of total mass $M$, volume $V$, and energy $U$ is enclosed in an adiabatic rigid container. The system is allowed to evolve freely. Because $M$, $V$, $U$ are fixed, the system reaches equilibrium at the maximum of its entropy $\Phi$.

In the most general case, the system consists of three phases: solid (subscript 1), liquid (2), gas (3), with masses $M_1, M_2, M_3$, specific volumes $v_1, v_2, v_3$, and specific entropies $\phi_1, \phi_2, \phi_3$. The constraints are:

$$M_1 + M_2 + M_3 = M, \quad M_1 v_1 + M_2 v_2 + M_3 v_3 = V, \quad M_1 u_1 + M_2 u_2 + M_3 u_3 = U$$

Setting $\delta\Phi = 0$ subject to these constraints (using Lagrange multipliers or direct substitution), six coefficients must vanish independently.

---

## 2. Conditions for Phase Equilibrium (§167)

The six vanishing coefficients yield the **conditions of equilibrium** (§167):

$$\boxed{\theta_1 = \theta_2 = \theta_3 = \theta \qquad \text{(thermal equilibrium)}} \tag{98a}$$
$$\boxed{p_1 = p_2 = p_3 = p \qquad \text{(mechanical equilibrium)}} \tag{98b}$$
$$\phi_i - \phi_j = \frac{(u_i - u_j) + p(v_i - v_j)}{\theta} \quad \text{for each pair } (i,j) \tag{98c}$$

Equations (98c) state that the **specific Gibbs potential** $g_i = u_i + pv_i - \theta\phi_i$ (Planck writes it as part of $\psi$) must be equal across all phases:

$$g_1 = g_2 = g_3$$

This is the **chemical potential equality** — the fundamental condition for phase equilibrium. Planck derives it as a variational condition without giving it that name explicitly.

Using the entropy definition $d\phi = (du + p\,dv)/\theta$, equation (98c) simplifies to an integral relation. For isothermal integration:

$$\phi_i - \phi_j = \frac{u_i - u_j}{\theta} + \frac{1}{\theta}\int_{v_j}^{v_i} p\,dv$$

These become (§168):

$$\int_{v_2}^{v_1} p\,dv = p(v_1 - v_2), \qquad \int_{v_3}^{v_2} p\,dv = p(v_2 - v_3), \qquad p_1 = p_2 = p_3 \tag{99}$$

These conditions state that the area under the isotherm between the two coexisting specific volumes equals $p\cdot\Delta v$ — the famous **Maxwell equal-area rule**: the areas of the two loops that the cubic isotherm makes above and below the horizontal line at pressure $p$ must be equal.

---

## 3. The Clausius–Clapeyron Equation (§§171–172)

How does the equilibrium pressure change with temperature along the coexistence curve? Differentiating the phase equilibrium conditions and using the entropy relations:

$$\frac{dp}{d\theta} = \frac{\phi_1 - \phi_2}{v_1 - v_2} = \frac{q}{\theta(v_1 - v_2)} \tag{Clausius–Clapeyron}$$

where $q = \theta(\phi_1 - \phi_2)$ is the **latent heat** of the phase transition (heat absorbed per unit mass on going from phase 2 to phase 1 at temperature $\theta$). This is the **Clausius–Clapeyron equation**, one of the most important equations in classical thermodynamics, here derived rigorously from the entropy principle.

**Vaporisation curve** (liquid ↔ vapour): $dp/d\theta = L/([\theta(v_g - v_l)])$ where $L$ is the heat of vaporisation and $v_g \gg v_l$. Using the perfect-gas approximation for the vapour: $v_g = R\theta/(mp)$, so:

$$\frac{d\ln p}{d\theta} = \frac{mL}{R\theta^2}$$

This gives the vapour-pressure curve as a function of temperature — a result verifiable from experiment.

**Fusion curve** (solid ↔ liquid): The volume change on melting is small, so $dp/d\theta$ is large. For ice, $v_{\text{liquid}} < v_{\text{solid}}$ (anomalous), so $dp/d\theta < 0$ — increasing pressure lowers the melting point. For most substances $v_{\text{liquid}} > v_{\text{solid}}$, so pressure raises the melting point.

---

## 4. Stable vs. Unstable Equilibrium; Supersaturation (§§173–180)

Not every solution to the equilibrium conditions corresponds to a *stable* state. The second variation $\delta^2\Phi$ must be negative (entropy maximum) for stability. Planck shows that phase coexistence corresponds to stable equilibrium when the states lie on the physically realised portions of the characteristic curve (saturation states $A$ and $C$ from §27).

The **unstable middle branch** of the isotherm corresponds to a saddle point (or maximum) of $F$, not a minimum. Systems prepared near these states are metastable: small perturbations cause nucleation of the stable phase. This explains **supersaturation** and **supercooling** phenomena:
- Supersaturated vapour: vapour compressed beyond the saturation point $C$ without condensation; it remains metastable until a nucleation event triggers collapse to the stable liquid state.
- Supercooled liquid: liquid cooled below the melting point without freezing; the stable phase (solid) nucleates on disturbance.

---

## 5. Triple Point (§§181–185)

When all three phases coexist simultaneously, the conditions are $p_1 = p_2 = p_3$ and three chemical potential equalities. These fix *both* temperature and pressure uniquely — there is no freedom. The **triple point** is a fixed point in the $p$–$\theta$ diagram characteristic of the substance.

For water: $\theta_{\text{triple}} = 273.16\,\mathrm{K}$, $p_{\text{triple}} = 4.58\,\mathrm{mmHg}$.

Below the triple-point pressure, liquid cannot exist at equilibrium — only solid and vapour. This explains **sublimation** (direct solid-to-vapour transition at low pressure) and the shape of the $p$–$T$ phase diagram.

---

## 6. Applications to Specific Phenomena (§§186–196)

**Effect of pressure on boiling point (§186):** From the Clausius–Clapeyron equation, $d\theta/dp = \theta(v_g - v_l)/L > 0$. Boiling point increases with pressure.

**Effect of dissolved substances on boiling and melting points (§§190–196):** Planck begins here the analysis of *solutions* that continues in Chapter V. The key insight: a dissolved substance lowers the chemical potential of the solvent in the liquid phase. This changes the temperature at which the liquid phase is in equilibrium with the vapour (boiling-point elevation) or solid (freezing-point depression). The magnitude is proportional to the concentration of dissolved molecules — a result that will be derived formally in Chapter V using dilute-solution theory.

---

## Summary

| Phenomenon | Driving equation | Key result |
|-----------|-----------------|-----------|
| Phase coexistence | $g_1 = g_2 = g_3$ | Temperature, pressure, chemical potential all equal |
| Maxwell equal-area | $\int p\,dv = p\Delta v$ | Picks out saturation states |
| Clausius–Clapeyron | $dp/d\theta = q/[\theta\Delta v]$ | Slope of coexistence curves |
| Vapour pressure | $d\ln p/d\theta = mL/(R\theta^2)$ | Exponential temperature dependence |
| Triple point | $\theta, p$ uniquely fixed | No freedom — single point |

Chapter II of Part IV is the thermodynamic core of phase equilibrium theory. Its results are universal — derived from the two laws alone — and apply equally to water, carbon dioxide, or any other pure substance.
