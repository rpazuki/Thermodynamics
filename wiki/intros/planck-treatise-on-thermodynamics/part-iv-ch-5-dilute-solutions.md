---
title: "Part IV, Chapter V — Dilute Solutions"
type: concept
tags: [dilute-solutions, osmotic-pressure, boiling-point-elevation, freezing-point-depression, van-t-hoff, solubility, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part IV, Chapter V: Dilute Solutions (§§249–265)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

The final chapter extends the framework of Chapter IV (gaseous systems) to the thermodynamics of dilute solutions. The central insight is that the thermodynamic behaviour of dissolved molecules in a dilute solution is formally identical to that of molecules of a perfect gas — the dissolved molecules obey the same entropy expression, from which follows osmotic pressure, boiling-point elevation, freezing-point depression, solubility curves, and the law of mass action in solution, all as consequences of the two laws of thermodynamics.

---

## 1. Definition of Dilute Solutions (§249)

A **dilute solution** is a phase in which one molecular species (the *solvent*, with $n_0$ molecules) far outnumbers all others (the *dissolved substances*, with $n_1, n_2, \ldots$ molecules):

$$n_0 \gg n_1, n_2, \ldots$$

The state of aggregation (solid, liquid, gaseous) is irrelevant — the theory applies equally to all.

---

## 2. Energy and Volume of a Dilute Solution (§§250–253)

The mathematical simplification of diluteness (§250) rests on **Taylor expansion**: since $n_1/n_0, n_2/n_0, \ldots$ are small, any finite continuous function of these ratios is approximately linear in them. This gives (§253):

$$U = n_0 u_0 + n_1 u_1 + n_2 u_2 + \cdots \tag{209a}$$
$$V = n_0 v_0 + n_1 v_1 + n_2 v_2 + \cdots \tag{209b}$$

where $u_i, v_i$ are functions of $\theta$ and $p$ only (not of $n$). These are the energy and volume per molecule of species $i$ *in the presence of the solvent* — they account for solvent–solute interactions. Crucially, there are **no solute–solute interaction terms**: in a dilute solution, dissolved molecules are so dilute that they do not interact with each other.

Consequence (§253): further dilution produces neither change of volume nor heat effect (if no chemical changes occur). Any volume change or heat of dilution must therefore be attributed to chemical transformations among the dissolved molecules.

---

## 3. Entropy of a Dilute Solution (§§254–256)

Integrating $d\Phi = (dU + p\,dV)/\theta$ at constant composition and comparing with the known entropy of a gas mixture, Planck shows that the entropy of a dilute solution has exactly the **same logarithmic form** as a gas mixture (§255):

$$\Phi = n_0\phi_0 + \sum_i n_i\left(\phi_i - R\log\frac{n_i}{n_0}\right) + \text{(small corrections)} \tag{entropy of dilute solution}$$

The term $-R\log(n_i/n_0)$ is the **entropy of dilution** — it is the same expression as the entropy of mixing of an ideal gas! This is the key analogy: dissolved molecules in a dilute solution have the same entropy expression as gas molecules in a mixture.

The $\Psi$ function for the solution is then:

$$\Psi = n_0\psi_0 + \sum_i n_i\left(\psi_i + R\log\frac{n_i}{n_0}\right) \tag{$\Psi$ for dilute solution}$$

where $\psi_i$ depends on $\theta, p$ and the nature of species $i$ (including solvent–solute interactions).

---

## 4. Osmotic Pressure (§§257–260)

A semipermeable membrane separates a dilute solution from pure solvent. The chemical potential of the solvent must be equal on both sides at equilibrium. In the pure solvent there is no mixing entropy; in the solution there is. The difference in chemical potential at the same pressure would favour the solvent passing into the solution. To stop this flow, a pressure $\Pi$ (the **osmotic pressure**) must be applied to the solution side.

The equilibrium condition gives (§258):

$$\Pi = \frac{R\theta}{v_0}\sum_i \frac{n_i}{n_0} = \frac{R\theta}{V_0}\sum_i n_i$$

where $V_0 = n_0 v_0$ is the volume of the solvent. This is **van't Hoff's law**:

$$\boxed{\Pi V = (n_1 + n_2 + \cdots)R\theta} \tag{osmotic pressure}$$

This is formally identical to the perfect-gas law $pV = nR\theta$, with the total number of dissolved molecules playing the role of gas molecules and osmotic pressure playing the role of gas pressure. The analogy is not accidental — it arises from the identical entropy expressions.

This result was van't Hoff's hypothesis (1886), confirmed by Pfeffer's experiments. Here it is derived rigorously from thermodynamic first principles.

---

## 5. Boiling-Point Elevation and Freezing-Point Depression (§§261–262)

When a non-volatile solute is dissolved in a liquid solvent, the chemical potential of the solvent in the liquid phase is lowered by the entropy of mixing. The vapour pressure of the solution is therefore lower than that of the pure solvent. By the Clausius–Clapeyron equation (from Part IV, Ch. II), this shifts the boiling point upward:

$$\Delta\theta_{\text{bp}} = \frac{R\theta_0^2 v_0}{\lambda}\sum_i\frac{n_i}{n_0} \tag{boiling-point elevation}$$

where $\theta_0$ is the normal boiling point and $\lambda$ is the molar heat of vaporisation.

Similarly, the solute lowers the freezing point of the solution (the liquid phase now has lower chemical potential, so it is more stable relative to ice):

$$\Delta\theta_{\text{fp}} = -\frac{R\theta_0^2 v_0}{q}\sum_i\frac{n_i}{n_0} \tag{freezing-point depression}$$

where $q$ is the molar heat of fusion. Both formulas show that the effect is proportional to the total **number of dissolved molecules**, not to the mass or chemical nature of the solute. This is the origin of the concept of **colligative properties**.

These results provide a direct method to measure molecular weights: the boiling-point elevation or freezing-point depression of a known solvent with a known mass of solute gives the molar mass of the solute.

---

## 6. Solubility and Chemical Equilibrium in Solution (§§263–265)

The law of mass action applies in solution just as in the gas phase. For a reaction among dissolved species:

$$\frac{n_3^{\nu_3} n_4^{\nu_4}}{n_1^{\nu_1} n_2^{\nu_2}} = K(\theta, p) \cdot n_0^{\nu_1+\nu_2-\nu_3-\nu_4} \tag{mass action in solution}$$

The equilibrium constant depends on temperature through the van't Hoff equation — the heat of reaction in solution now plays the role of $\Delta H$. Pressure dependence is generally negligible for condensed-phase reactions (since volume changes are small).

**Solubility (§264):** The equilibrium between a dissolved substance and its solid phase (the pure solid is a separate phase) gives the solubility as a function of temperature. Planck derives:

$$\frac{d\ln s}{d\theta} = \frac{q_{\text{sol}}}{R\theta^2}$$

where $s$ is the molar solubility and $q_{\text{sol}}$ is the molar heat of dissolution. This is the thermodynamic basis for the observation that endothermal substances become more soluble at higher temperatures and exothermal ones become less soluble.

---

## Summary

| Property | Formula | Analogy |
|----------|---------|---------|
| Osmotic pressure | $\Pi V = nR\theta$ | Perfect gas law |
| Boiling-point elevation | $\Delta\theta \propto \sum n_i/n_0$ | Entropy of mixing |
| Freezing-point depression | $\Delta\theta \propto \sum n_i/n_0$ | Entropy of mixing |
| Mass action in solution | $\prod n_i^{\nu_i} = K(\theta) n_0^{\Delta\nu}$ | Same as gas phase |
| Solubility | $d\ln s/d\theta = q_{\text{sol}}/(R\theta^2)$ | Van't Hoff analogy |

Chapter V completes the book's programme by showing that the dilute solution is the condensed-matter analogue of the perfect gas — the same entropy of mixing drives all colligative phenomena, and the two laws of thermodynamics, applied to this entropy expression, reproduce all the key results of physical chemistry of solutions.

---

*[↑ Table of Contents](toc.md) · [← Back: Part IV Ch.IV — Gaseous Systems](part-iv-ch-4-gaseous-system.md) · [Next: Analysis — Conceptual Architecture →](analysis.md)*
