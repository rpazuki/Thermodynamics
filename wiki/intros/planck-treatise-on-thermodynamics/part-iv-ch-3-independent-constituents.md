---
title: "Part IV, Chapter III — System of Any Number of Independent Constituents"
type: concept
tags: [phase-rule, gibbs, independent-constituents, chemical-potential, psi-function, equilibrium, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part IV, Chapter III: System of Any Number of Independent Constituents (§§197–231)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This is the most abstract and general chapter of Part IV. It extends the equilibrium theory from one-component systems (Chapter II) to systems with any number of **independent constituents** $\alpha$ distributed among any number of **phases** $\beta$. The principal result is Gibbs's **phase rule**: $f = \alpha - \beta + 2$. The characteristic function $\Psi$ and the chemical potentials $\mu_i$ are the key mathematical tools. This chapter represents classical thermodynamics at its most general, and forms the theoretical foundation for physical chemistry and chemical engineering.

---

## 1. Phases and Independent Constituents (§§197–198)

Planck adopts Gibbs's vocabulary:

**Phase:** a physically homogeneous portion of the system — any region of uniform temperature, density, and composition. A system can have many coexisting solid and liquid phases but only one gaseous phase (two different gases in contact are never in equilibrium — they mix by diffusion until uniform).

**Independent constituents ($\alpha$):** the minimum number of chemically distinct species needed to specify the composition of each phase. The key rule: find all elements in the system; subtract those whose quantity is determined by others in each phase. The remainder is $\alpha$.

Examples (§198):
- Pure water (any number of phases, any degree of dissociation): $\alpha = 1$ (the mass ratio of O to H is fixed throughout).
- Aqueous sulphuric acid: $\alpha = 2$ (S and H are independent; O is determined by them).
- A mixture where a chemical reaction proceeds to equilibrium: $\alpha$ = (number of species) − (number of independent reaction equations).

---

## 2. The Equilibrium Condition: $\delta\Psi = 0$ (§§200–202)

For constant temperature and pressure, the equilibrium condition (§200) is:

$$\delta\Psi = 0 \tag{141}$$

where the characteristic function is:

$$\Psi = \Phi - \frac{U + pV}{\theta} = -\frac{G}{\theta}$$

and $G$ is the Gibbs free energy. Since $\Psi$ is a sum over all phases (§201):

$$\Psi = \Psi' + \Psi'' + \cdots + \Psi^{(\beta)}$$

and each $\Psi^{(k)}$ is a homogeneous function of the first degree in the masses $M_1^{(k)}, \ldots, M_\alpha^{(k)}$ of the constituents in phase $k$ (Euler's theorem), Planck writes each as a linear combination:

$$\Psi^{(k)} = \sum_{i=1}^\alpha M_i^{(k)} \frac{\partial \Psi^{(k)}}{\partial M_i^{(k)}} \tag{144}$$

---

## 3. Chemical Potentials and the General Equilibrium Condition (§§203–210)

Define the **chemical potential** of constituent $i$ in phase $k$ (§203):

$$\mu_i^{(k)} \equiv -\theta \frac{\partial \Psi^{(k)}}{\partial M_i^{(k)}}$$

(Planck uses $\partial\Psi/\partial M_i$ directly, but the identification with $-\mu/\theta$ is clear.) Setting $\delta\Psi = 0$ subject to the constraint that total masses $M_i = \sum_k M_i^{(k)}$ are conserved gives:

$$\mu_i^{(1)} = \mu_i^{(2)} = \cdots = \mu_i^{(\beta)} \qquad \text{for each } i = 1, \ldots, \alpha \tag{(equilibrium)}$$

**Temperature and pressure are also equal across phases** (from the first-order conditions, as in Chapter II). This gives the complete set of equilibrium conditions:

- 1 equation for temperature equality.
- 1 equation for pressure equality.
- $(\beta - 1) \times \alpha$ equations from chemical potential equality.

Total: $\alpha(\beta - 1) + 2$ equations.

---

## 4. The Gibbs Phase Rule (§§213–214)

The state of each phase is determined by temperature, pressure, and $\alpha - 1$ independent composition ratios (one composition is fixed by normalisation). Total variables: $2 + \beta(\alpha - 1)$.

The number of equations that must be satisfied: $\alpha(\beta - 1) + 2$ (from §203, corrected for temperature and pressure equality already being two equations).

Wait — Planck derives it cleanly: the **degrees of freedom** $f$ (number of independently variable quantities that can be changed without altering the number of phases) is:

$$f = \alpha - \beta + 2 \tag{Gibbs phase rule}$$

Planck calls this the **variance** of the system. Special cases:
- $\beta = 1$ (single phase): $f = \alpha + 1$ — highly variant; composition, temperature, and pressure can all vary.
- $\alpha = 1, \beta = 2$ (e.g., water ↔ ice): $f = 1$ — pressure fixes temperature (or vice versa); the system traces a coexistence curve.
- $\alpha = 1, \beta = 3$ (e.g., ice, water, vapour): $f = 0$ — fixed at the triple point.
- $\alpha = 2, \beta = 2$ (e.g., salt solution): $f = 2$ — both temperature and pressure can vary independently.

---

## 5. Applications of the Phase Rule (§§215–231)

**Eutectic points (§215–218):** For a two-component system ($\alpha = 2$) with four phases (e.g., two solid forms + liquid + vapour), $f = 0$: temperature, pressure, and compositions are all fixed — this is the **eutectic point**. Planck discusses several binary alloy and salt systems.

**Chemical equilibrium in a single phase (§§219–226):** If a chemical reaction can proceed within a phase, the amounts of constituents are no longer all independent — the reaction introduces a constraint (the law of mass action). Planck shows that the equilibrium constant is determined by the equality of chemical potentials of reactants and products. For a reaction $\nu_1 A_1 + \nu_2 A_2 \rightleftharpoons \nu_3 A_3 + \nu_4 A_4$:

$$\sum_i \nu_i \mu_i = 0 \tag{equilibrium constant}$$

**Semipermeable membranes and osmotic pressure (§§227–231):** A membrane permeable to solvent but impermeable to solute allows the chemical potential of the solvent to be equalised across the membrane by a pressure difference — **osmotic pressure**. Planck derives the osmotic pressure formula and connects it to the van't Hoff result (derived fully in Chapter V).

---

## Summary

| Concept | Formula |
|---------|---------|
| Phase rule | $f = \alpha - \beta + 2$ |
| Equilibrium | $\mu_i^{(k)} = \mu_i^{(k')}$ for all $i, k, k'$ |
| Characteristic function | $\Psi = \Phi - (U+pV)/\theta$ |
| Euler property | $\Psi = \sum_i M_i (\partial\Psi/\partial M_i)$ |

Chapter III provides the theoretical skeleton for all of chemical equilibrium and phase thermodynamics. The phase rule is one of the most powerful results of classical thermodynamics, derived here in full generality from the two laws and requiring no molecular assumptions whatsoever.
