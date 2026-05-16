---
title: "Part II, Chapter I — First Law: General Exposition"
type: concept
tags: [first-law, energy, conservation-of-energy, joule, mechanical-equivalent, perpetual-motion, reversible-process, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part II, Chapter I: The First Law — General Exposition (§§55–66)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This chapter states and proves the First Law of Thermodynamics as the **principle of conservation of energy applied to processes involving heat**. Planck bases it on the empirical impossibility of perpetual motion of the first kind (obtaining work from nothing), defines energy and its change rigorously, and introduces the key equation $U_2 - U_1 = Q + W$. The chapter also defines reversible processes and the concept of a perfect system.

---

## 1. Statement of the First Law (§55)

Planck states the First Law clearly: it "is nothing more than the principle of the conservation of energy applied to phenomena involving the production or absorption of heat." Two routes to this principle exist:
1. **Mechanical reductionism:** assuming all phenomena are reducible to motions of particles with definite potentials, the First Law follows from the mechanical theorem of kinetic energy.
2. **Planck's chosen route (empirical):** start from the well-tested fact that **perpetual motion of the first kind is impossible** — no engine working in a cycle can produce continuous work from nothing.

Planck deliberately chooses the second route, avoiding mechanical hypotheses. He notes that the First Law is no longer seriously disputed as of 1897, but the Second Law still is — which is why the Second Law will receive far more careful treatment in Part III.

---

## 2. Energy: Definition and Properties (§§56–58)

The **energy of a system** in a given state (relative to an arbitrarily chosen normal state) is:

> *The algebraic sum of the mechanical equivalents of all effects produced outside the system when it passes in any way from the given state to the normal state.*

This definition is remarkable for what it does *not* assume: it does not presuppose that energy is a well-defined state function. The **Principle of Conservation of Energy** (§58) then asserts precisely that this sum is independent of the manner of transition — energy is a genuine state function.

**Mechanical equivalent of external effects:**
- If the effect is mechanical (lifting a weight, pushing against atmospheric pressure): its equivalent is the mechanical work done, positive if in the direction of the system's force.
- If the effect is thermal (heating surrounding bodies): its equivalent is the heat produced (in calories) multiplied by the **mechanical equivalent of heat** — a fundamental constant relating calories to ergs.

---

## 3. Joule's Experiments and the Mechanical Equivalent of Heat (§§60–61)

Joule's famous friction experiments (§60) demonstrated the conservation of energy across mechanical and thermal effects: the mechanical work done by falling weights equals the heat generated in the surrounding liquid by friction. By equating the two, Joule found:

> *The mechanical equivalent of a gram-calorie is the work done in lifting 1 g through 423.55 metres.*

Planck refines this for the gas thermometer and absolute units (§61):
- For the **zero calorie** (referred to gas thermometer): $1\,\mathrm{cal} \approx 430\,\mathrm{m\cdot g}$ or $4.22 \times 10^7\,\mathrm{ergs}$.
- For the **laboratory calorie**: $\approx 419 \times 10^5\,\mathrm{ergs}$ (= $4.19\,\mathrm{J}$ in SI).

Planck then takes the decisive step (§62): for all subsequent equations, **quantities of heat will be expressed directly in ergs** (mechanical units), making $Q$ directly equal to its mechanical equivalent. This simplifies all energy equations. Conversion back to calories requires division by $419 \times 10^5$.

---

## 4. The Fundamental Equation of the First Law (§63)

The **change in energy** when the system passes from state 1 to state 2 is:

$$U_2 - U_1 = Q + W \tag{17}$$

where:
- $Q$ = mechanical equivalent of heat absorbed by the system (positive if absorbed).
- $W$ = work done *on* the system by external forces (positive if the displacement is in the direction of the force).
- The right-hand side is path-independent (by the principle of conservation of energy), even though $Q$ and $W$ individually are not.

This is the First Law in its complete generality. Only their sum $Q + W$ has a definite value for given initial and final states.

---

## 5. Cycle of Operations and Perpetual Motion (§65)

If the system returns to its initial state (cyclic process), $U_2 = U_1$, so:

$$Q + W = 0 \tag{18}$$

The heat absorbed equals the work done by the system (with sign change). This immediately shows the **impossibility of a perpetual motion machine of the first kind**: in a complete cycle, no net energy can be created. Any machine that produces net work must absorb a corresponding amount of heat from some source; it cannot run on nothing.

---

## 6. Perfect Systems and Conservation (§66)

A **perfect system** is one with no external effects ($Q = 0$, $W = 0$). For such a system, $U = \mathrm{const}$ — energy is conserved. No truly perfect system exists in nature (all bodies interact), but by choosing a sufficiently large system that includes all interacting bodies, any external effect can be internalized. This is the justification for treating, e.g., the gas plus the atmosphere plus the lifting weight as a single system with constant total energy.

---

## 7. Reversible Processes (§§71–73)

Planck introduces the concept of an **infinitely slow process** — one consisting of a succession of states of equilibrium. Key properties:
- The process can be approximated to any desired accuracy by making it slow enough.
- For reversible compression, the external pressure equals the gas pressure at every instant, so $W = -\int p\,dV$ exactly.
- Crucially, every infinitely slow process can be **run in reverse**: a small perturbation suffices to reverse direction, and in the limiting case the perturbation vanishes.

**Heat exchange** in a reversible process is treated similarly (§72): heat is transferred between bodies whose temperatures differ by an infinitesimal amount. A single reservoir can drive an isothermal process; a set of reservoirs of varying temperature can drive a process with changing temperature. This prepares the ground for the Carnot cycle.

---

## 8. The First Law for Infinitesimal Reversible Changes (§§74–79)

For an infinitesimal change of a homogeneous system with independent variables $V$ (volume) and $\theta$ (temperature), the First Law gives (§79):

$$Q = dU + p\,dV \tag{22 (per unit mass)}$$

The work term is $-p\,dV$ (the only form of external work for a simple homogeneous body without surface or electrical effects). This is the elementary form of the First Law that drives all subsequent calculations.

Note Planck's deliberate notation choice: he does *not* write $dQ$ (which would falsely imply $Q$ is the differential of some function $Q$), but simply $Q$ for the infinitesimal heat element. This avoids the notorious misconception that heat is a state function.

---

## Summary

| Concept | Mathematical form |
|---------|-----------------|
| First Law | $U_2 - U_1 = Q + W$ |
| Cyclic process | $Q + W = 0$ |
| External work (reversible) | $W = -\int_1^2 p\,dV$ |
| Infinitesimal First Law | $Q = dU + p\,dV$ |
| Mechanical equivalent | $1\,\mathrm{cal(lab)} = 4.19 \times 10^7\,\mathrm{erg}$ |

The First Law establishes **energy as a state function** and **heat as a process quantity**. With the characteristic equation from Part I, Chapter I, all thermodynamic properties of a substance can in principle be computed from $p = f(v,\theta)$ plus the energy function $U$.
