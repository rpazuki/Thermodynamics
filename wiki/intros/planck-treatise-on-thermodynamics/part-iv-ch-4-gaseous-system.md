---
title: "Part IV, Chapter IV — Gaseous Systems"
type: concept
tags: [gaseous-system, entropy-of-mixing, semipermeable-membrane, chemical-equilibrium, dissociation, mass-action, avogadro, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part IV, Chapter IV: Gaseous Systems (§§232–248)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This chapter provides the explicit computation of the characteristic function $\Psi$ for a mixture of perfect gases, as a function of temperature, pressure, and molecular composition. The central result is an expression for the **entropy of mixing** and from it the full equilibrium conditions for gaseous chemical reactions (the law of mass action in thermodynamic form). The chapter also establishes that diffusion of gases is an irreversible process and explains how to define a unique entropy for a chemically homogeneous gas.

---

## 1. The Entropy of a Gas Mixture (§§232–234)

For a mixture of perfect gases with $n_1, n_2, \ldots$ molecules of each kind, the volume obeys Dalton's law (§233):

$$V = \frac{R\theta}{p}(n_1 + n_2 + \cdots) = \frac{R\theta}{p}\sum n_i \tag{191}$$

The energy (§233) is a sum of individual contributions:

$$U = \sum_i n_i(c_{v_i}\theta + h_i) \tag{193}$$

where $c_{v_i}$ is the molecular heat at constant volume and $h_i$ is a constant for species $i$.

The entropy is calculated by integrating $d\Phi = (dU + p\,dV)/\theta$ at constant composition (§234):

$$\Phi = \sum_i n_i\left(c_{v_i}\log\theta + R\log\frac{\theta}{p}\right) + C(n_1, n_2, \ldots) \tag{194}$$

The constant of integration $C$ depends on the composition and can only be determined by analysing a reversible process that changes the composition. Diffusion (the obvious candidate) is irreversible (§238) and therefore cannot be used.

---

## 2. Semipermeable Membranes and Entropy of Mixing (§§235–237)

Semipermeable membranes — membranes permeable to only one gas species — provide the required reversible process. A membrane permeable to gas $i$ is in equilibrium when the **partial pressure** of gas $i$ is the same on both sides, independent of other gases present (§235 — an empirically established proposition, tested by Planck himself with a platinum membrane permeable to hydrogen).

Using a semipermeable membrane device (§236–237), the gases of a mixture can be reversibly separated. The process produces no net work and no net heat if the entropy is unchanged. By carefully tracking the entropy changes, Planck determines that the composition-dependent constant in equation (194) must be:

$$C = -R\sum_i n_i \log n_i + R\sum_i n_i \log(n_1 + n_2 + \cdots) + \sum_i n_i\sigma_i$$

where $\sigma_i$ is a constant for species $i$ that depends on its nature. The **entropy of mixing** — the entropy increase when gases at the same temperature and pressure are mixed — is:

$$\Delta\Phi_{\text{mix}} = -R\sum_i n_i \log x_i, \qquad x_i = \frac{n_i}{\sum_j n_j} \tag{entropy of mixing}$$

This is always positive (since $x_i < 1$), confirming that **mixing is irreversible** — the entropy increases and the process cannot be reversed without leaving changes in the surroundings.

---

## 3. Gibbs Paradox Region — Chemical Homogeneity Defined by Entropy (§238)

A subtle point arises: should two samples of the *same* gas that are mixed show an entropy of mixing? Planck's analysis says no: the entropy of mixing formula involves $\log x_i$ terms only when the gases are *different* (the membrane can separate them). If both samples are the same gas, no membrane can separate them (a membrane permeable to gas $A$ passes both samples equally) and the entropy of mixing is zero. This is the resolution of the **Gibbs paradox** without requiring quantum mechanics: **chemical homogeneity** is defined precisely as the property of not being separable by any semipermeable membrane — and therefore of having zero entropy of mixing. (§238)

---

## 4. The Characteristic Function $\Psi$ for a Gas Mixture (§§239–241)

Substituting the full entropy expression into $\Psi = \Phi - (U+pV)/\theta$:

$$\Psi = \sum_i n_i\left[\sigma_i + (c_{v_i} + R)\log\theta - R\log p - R\log n_i + R\log\sum_j n_j - \frac{h_i}{\theta}\right] \tag{200}$$

This is the complete thermodynamic potential for a perfect gas mixture at temperature $\theta$ and pressure $p$, as a function of the molecular counts $n_1, n_2, \ldots$.

---

## 5. Chemical Equilibrium in a Gas Mixture — Law of Mass Action (§§242–246)

For a chemical reaction in a gas phase:

$$\nu_1 A_1 + \nu_2 A_2 \rightleftharpoons \nu_3 A_3 + \nu_4 A_4$$

the equilibrium condition is $\sum_i \nu_i(\partial\Psi/\partial n_i) = 0$. Substituting from equation (200) and rearranging:

$$\frac{n_3^{\nu_3} n_4^{\nu_4}}{n_1^{\nu_1} n_2^{\nu_2}} = f(\theta) \cdot p^{\nu_1+\nu_2-\nu_3-\nu_4} \tag{law of mass action}$$

This is the **law of mass action** in thermodynamic form. The right-hand side depends only on temperature (through $f(\theta)$) and pressure (through the total molecule count). For reactions where the number of gas molecules is conserved ($\nu_1 + \nu_2 = \nu_3 + \nu_4$), the equilibrium constant is pressure-independent.

The temperature dependence of the equilibrium constant is given by the **van't Hoff equation**:

$$\frac{d\ln K}{d\theta} = \frac{\Delta H}{R\theta^2}$$

where $\Delta H$ is the heat of reaction — confirming the connection to thermochemistry established in Part II.

---

## 6. Dissociation Equilibria (§§247–248)

As a specific application, consider the thermal dissociation of a diatomic gas $A_2 \rightleftharpoons 2A$. At equilibrium:

$$\frac{n_A^2}{n_{A_2}} = f(\theta) \cdot p^{-1}$$

The degree of dissociation increases with temperature (if the dissociation is endothermal) and decreases with pressure (Le Chatelier's principle). Planck calculates the apparent molecular weight of partially dissociated nitrogen peroxide ($\mathrm{N_2O_4 \rightleftharpoons 2NO_2}$) and compares with experimental vapour density data — good agreement confirms the theory.

---

## Summary

| Concept | Expression |
|---------|-----------|
| Volume of gas mixture | $V = (R\theta/p)\sum n_i$ |
| Energy | $U = \sum_i n_i(c_{v_i}\theta + h_i)$ |
| Entropy of mixing | $\Delta\Phi = -R\sum_i n_i \log x_i \geq 0$ |
| $\Psi$ function | Equation (200) — explicit function of $\theta, p, n_i$ |
| Law of mass action | $\prod n_i^{\nu_i} = K(\theta, p)$ |
| Van't Hoff equation | $d\ln K/d\theta = \Delta H/(R\theta^2)$ |

Chapter IV is the high point of Planck's treatment of chemical equilibrium. By computing $\Psi$ explicitly for perfect gas mixtures, it makes the abstract equilibrium condition $\delta\Psi = 0$ fully quantitative and directly comparable with experiment.
