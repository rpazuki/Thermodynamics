---
title: "Part I, Chapter II — Molecular Weight"
type: concept
tags: [molecular-weight, avogadro, equivalent-weight, gas-constant, dissociation, semipermeable-membrane, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part I, Chapter II: Molecular Weight (§§33–43)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This short chapter introduces the concept of **molecular weight** as a precise, physically well-defined quantity, at least for perfect gases. It is the bridge between the macroscopic gas laws of Chapter I and the atomistic language that will be needed for thermochemistry (Part II, Ch. III) and multi-component equilibria (Part IV). Planck is notably careful about the limitations of the concept: molecular weight is well-defined only for perfect gases and dilute solutions. For everything else, the question is left open.

---

## 1. The Problem: Physical vs. Chemical Changes (§33)

Planck opens by distinguishing **physical changes** (temperature, pressure, density variations with chemical constitution unchanged) from **chemical changes** (alterations in the molecular constitution of the substance). He concedes that drawing a sharp boundary is difficult in practice: dissociation can be gradual and continuous, and many chemical reactions look superficially like physical changes. He remarks that this distinction is one of the great open problems of physical chemistry, noting parenthetically that physical changes are typically continuous, chemical ones discontinuous (involving whole or simple rational numbers in stoichiometry).

---

## 2. Equivalent Weights (§§34–35)

Experience shows that chemical reactions occur in definite proportions by weight — the law of definite proportions. The **equivalent weight** of an element or compound is defined relative to hydrogen ($= 1\,\mathrm{g}$): it is the mass that reacts with $1\,\mathrm{g}$ of hydrogen. The **number of equivalents** in a body is its total mass divided by its equivalent weight.

An ambiguity arises because two elements can combine in multiple ratios (e.g., the five oxides of nitrogen). Different choices of equivalent weight for nitrogen give numbers in simple integer ratios:
$$28 : 14 : 9\tfrac{1}{3} : 7 : 5\tfrac{3}{5} = 60 : 30 : 20 : 15 : 12$$

This ambiguity motivates the introduction of a more fundamental unit.

---

## 3. Molecular Weight and Avogadro's Law (§§36–38)

The ambiguity in equivalent weight is resolved by Gay-Lussac's law: gases combine not only in simple weight ratios but also in **simple volume ratios** at constant temperature and pressure. This means the number of equivalents in equal volumes of different gases must be in simple ratios. The ambiguity is removed by convention: one **chooses the ratios all equal to 1**, i.e., one requires that equal volumes of different perfect gases at the same $T$ and $p$ contain the same number of equivalents. This fixes a unique equivalent weight for each gas, called its **molecular weight**, and the number of such units in a quantity of gas is the **number of molecules**.

This is Avogadro's law (§36):
> *Equal volumes of perfect gases at the same temperature and pressure contain an equal number of molecules.*

The molecular weight of hydrogen is $m_0 = 2$ (since the hydrogen atom has weight 1 and the hydrogen molecule is H₂). The **atom** is defined as the smallest weight of an element occurring in any molecular compound (§38):
- H atom $= 1$, H molecule = H₂ $= 2$
- O atom $= 16$, O molecule = O₂ $= 32$
- N atom $= 14$, N molecule = N₂ $= 28$
- Water molecule = H₂O $= 18$

---

## 4. The Absolute Gas Constant and Characteristic Equation (§§39–40)

Given molecular weight $m$, the specific density relative to hydrogen is $m/m_0 = m/2$. Using the characteristic equation $p = (C/v)\theta$ and the known density of hydrogen, one finds:

$$C = \frac{m_0 C_0}{m}$$

Setting $R \equiv m_0 C_0 = 82{,}600{,}000$ (in C.G.S. units), the characteristic equation of any perfect gas with molecular weight $m$ becomes:

$$p = \frac{R}{m} \cdot \frac{\theta}{v} \tag{14}$$

where $R$ is the **universal gas constant**, independent of the gas species. The molecular weight can always be recovered as $m = R/C$ (§39). The volume of $n = M/m$ molecules of any perfect gas at temperature $\theta$ and pressure $p$ is:

$$V = \frac{R\theta}{p} n$$

This is one of the great unifying results of classical thermodynamics: **at fixed $T$ and $p$, the volume depends only on the number of molecules, not their chemical nature.**

For a mixture, the partial pressures obey $p_1 : p_2 : \cdots = n_1 : n_2 : \cdots$ (§40), and the total volume is determined by the total molecule count $n = n_1 + n_2 + \cdots$. The **apparent molecular weight** of a mixture is defined (§41) as:

$$m_{\mathrm{app}} = \frac{M_1 + M_2 + \cdots}{\dfrac{M_1}{m_1} + \dfrac{M_2}{m_2} + \cdots}$$

For air (23.1% O₂ and 76.9% N₂ by mass): $m_{\mathrm{app}} \approx 28.8$.

---

## 5. Limitations and the Problem of Dissociation (§§42–43)

The molecular weight as defined above is **exact only for perfect gases** and for dilute solutions (deferred to Part IV, Ch. V). For substances that deviate from perfect-gas behaviour, two interpretations compete:

**Physical interpretation:** The molecules are intact; deviations arise from intermolecular forces (van der Waals, Clausius equations). Molecular weight is constant.

**Chemical interpretation (dissociation hypothesis):** The deviations are due to ongoing chemical reactions between molecules, continuously changing the mixture composition and hence the total molecule count. For example, nitrogen peroxide (N₂O₄) dissociates into NO₂, so the apparent molecular weight changes with temperature and pressure.

The dissociation hypothesis is especially compelling when vapour densities show large anomalies that disappear at extreme temperatures (e.g., amylene hydrobromide doubles its molecular count above 360°C via decomposition $\mathrm{C_5H_{11}Br} \rightarrow \mathrm{C_5H_{10} + HBr}$). Planck notes that distinguishing the two interpretations is one of the open problems of the day — in the absence of a fundamental chemical definition of molecular weight for non-ideal systems, **both remain viable** and the question should be left open.

A deeper definition of chemical homogeneity (and hence of molecular weight) that resolves this ambiguity is deferred to §237, where it emerges from the concept of entropy.

---

## Key Points

- Molecular weight is defined by Avogadro's law for perfect gases: equal volumes at equal $T, p$ contain equal molecule counts.
- The universal gas constant $R = 82{,}600{,}000$ (abs.) unifies all perfect gases through $pV = (R/m)\,M\theta$.
- The concept extends immediately to gas mixtures via apparent molecular weight.
- For real gases and condensable vapours, molecular weight is operationally ambiguous; the book returns to this only in §237 via the entropy concept.
- Semipermeable membranes (§42) are identified as one of the few tools that can distinguish chemically different components of a mixture — a hint at their crucial role in Part IV.

---

*[↑ Table of Contents](toc.md) · [← Back: Part I Ch.I — Temperature](part-i-ch-1-temperature.md) · [Next: Part I Ch.III — Quantity of Heat →](part-i-ch-3-quantity-of-heat.md)*
