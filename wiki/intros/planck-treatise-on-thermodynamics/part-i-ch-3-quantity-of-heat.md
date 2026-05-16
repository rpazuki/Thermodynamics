---
title: "Part I, Chapter III — Quantity of Heat"
type: concept
tags: [heat, specific-heat, calorie, latent-heat, heat-effect, carnot-theory, mechanical-equivalent, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part I, Chapter III: Quantity of Heat (§§44–54)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This brief but foundational chapter distinguishes *temperature* from *quantity of heat*, introduces the calorie and specific heat, examines the Dulong–Petit and Neumann laws for atomic/molecular heats, and critiques the older (Carnot) caloric theory of heat. It concludes by defining the heat effect of chemical reactions. Together with Chapters I and II, it completes the empirical groundwork for the First Law.

---

## 1. Temperature vs. Quantity of Heat (§44)

A simple experiment motivates the distinction. A piece of iron and a piece of lead, both at 100°C and equal mass, are immersed in equal quantities of water at 0°C. The water in contact with iron rises to a much higher temperature than that in contact with lead. Conversely, equal masses of each metal at 0°C cool a given hot-water sample by very different amounts. This shows that **two bodies at the same temperature do not necessarily contain the same *amount* of heat in any operationally meaningful sense**.

**Quantity of heat** is defined indirectly: the heat given out or received by a body is measured by the temperature change it produces in a **normal substance** (water) under controlled conditions, with all other causes of temperature change excluded. Heat transferred to the body is equal in magnitude to heat received by the water standard.

---

## 2. The Calorie and Its Variants (§45)

The standard **unit of heat** is the *calorie*:
- **Zero calorie:** heat needed to raise 1 g of water from 0°C to 1°C.
- **Laboratory calorie:** heat to raise 1 g of water at 15–20°C by 1°C; approximately $\tfrac{1}{1.006}$ of the zero calorie.
- **Mean calorie:** $\tfrac{1}{100}$ of the heat needed to raise 1 g of water from 0°C to 100°C; approximately equal to the zero calorie.
- **Kilocalorie (large calorie):** 1000 small calories.

These distinctions matter for precision calorimetry. Planck notes that for most of the book's calculations, the conversion will be to **ergs** (absolute C.G.S. units) to avoid the ambiguity.

---

## 3. Specific Heat (§§46–47)

The **mean specific heat** of 1 g of a substance over temperature interval $\Delta\theta$ is:

$$c_m = \frac{Q}{\Delta\theta}$$

and the **specific heat at temperature $\theta$** is the differential limit:

$$c = \frac{Q}{d\theta}$$

For solids and liquids, $c$ is nearly independent of pressure, so no further qualification is needed. For **gases**, however, specific heat depends strongly on the conditions: at constant pressure ($c_p$) versus constant volume ($c_v$). Without further specification, the specific heat of a gas usually refers to $c_p$.

---

## 4. Atomic and Molecular Heats; Dulong–Petit and Neumann Laws (§§48–50)

It is physically more meaningful to compare heat capacities referred to **molecular or atomic masses** rather than unit mass. Define:
- **Molecular heat:** specific heat × molecular weight.
- **Atomic heat:** specific heat × atomic weight.

**Dulong and Petit's law (§49):** Elements of high atomic weight have approximately constant atomic heat $\approx 6.4$ cal/(mol·K). This regularity is imperfect (carbon, boron, silicon deviate substantially, especially at low temperatures), but suggests a deep general law. Planck notes it "is founded on some more general law of nature, which has not yet been formulated" — an allusion to what Einstein and Debye would explain via quantum mechanics in the next decade.

**Neumann's law (§50):** Compounds of similar chemical constitution in the solid state have equal molecular heats. Joule and Woestyn further showed that the molecular heat of a compound is approximately the **sum of the atomic heats of its constituent elements** — each element preserves its atomic heat regardless of combination. Again this is approximate, and Planck acknowledges the numerous exceptions.

---

## 5. The Total Heat of a Body — Why It Cannot Be Defined (§51)

This is a conceptually crucial section. Planck argues it is **meaningless to define the total heat *contained in* a body** as the sum of calories absorbed to bring it to its present state from some normal state. The reason: the total heat absorbed depends on the *path* by which the change was effected. A gas can be brought from state (0°C, 1 atm) to state (100°C, 10 atm) by:
1. Heating at constant pressure then compressing isothermally.
2. Compressing isothermally then heating.
3. Simultaneous or alternating combinations of the two.

Each path absorbs a **different total number of calories** (as will be proved in §77). Therefore, there is no such thing as a definite "amount of heat" stored in a body at a given state — heat is a *process quantity*, not a state function. (Energy, by contrast, is a state function — the whole point of the First Law.)

---

## 6. Critique of the Caloric (Carnot) Theory (§52)

The older theory of Carnot assumed heat to be an **indestructible substance** (caloric), implying that the "total heat" of a body is a fixed state function. On this view, friction and compression change the temperature not by adding heat but by reducing the heat *capacity*, so the same amount of caloric produces a higher temperature. This is refuted by:
- **Rumford and Davy:** friction generates heat indefinitely in materials that show no change in heat capacity.
- **Regnault:** the heat capacity of gases is nearly independent of volume and cannot decrease by compression as the caloric theory requires.
- **Thomson and Joule (porous-plug experiment):** a perfect gas expands through a porous plug without change of temperature, showing that temperature change on expansion is due to *work done*, not to a change in stored caloric.

Each of these experiments independently disproves the caloric hypothesis.

---

## 7. Latent Heat and Heat Effects of Reactions (§§53–54)

At **singular temperatures** (melting point, boiling point) under a given pressure, the specific heat is discontinuous: heat added no longer raises the temperature but changes the **state of aggregation**. This is **latent heat** — heat of fusion, vaporisation, or sublimation. It depends on external conditions (pressure) and is best expressed per mole rather than per gram.

More generally, **all mixing, dissolution, and chemical reactions** are accompanied by a **heat effect** (Wärmetonung), defined as:
- **Positive** (exothermal): heat evolved, given out by the body ($Q < 0$ in Planck's sign convention where $Q$ is heat absorbed).
- **Negative** (endothermal): heat absorbed by the body ($Q > 0$).

This sets up the thermochemistry of Part II, Chapter III.

---

## Summary of Key Concepts

| Concept | Definition |
|---------|-----------|
| Specific heat | $c = Q/d\theta$ |
| Atomic heat (Dulong–Petit) | $\approx 6.4$ cal/(g-atom·K) for heavy elements |
| Latent heat | Heat exchanged at constant $T$ during phase change |
| Caloric theory | Refuted; heat is a process quantity, not a substance |
| Heat effect of reaction | $Q > 0$ (endothermal) or $Q < 0$ (exothermal) |

The key lesson of the chapter is the conceptual separation between **temperature** (a state quantity, intensive), **quantity of heat** (a process quantity), and **energy** (a state quantity, extensive, to be introduced in Part II).
