---
title: "Part II, Chapter III — First Law: Applications to Non-Homogeneous Systems (Thermochemistry)"
type: concept
tags: [thermochemistry, heat-of-formation, heat-of-combustion, hess-law, gibbs-heat-function, non-homogeneous-systems, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part II, Chapter III: First Law — Applications to Non-Homogeneous Systems (§§92–105)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This chapter extends the First Law to systems that are not homogeneous — in particular, systems undergoing chemical reactions and phase changes. The central result is **Hess's law** (path-independence of heat effects), which follows directly from the First Law. The chapter introduces Thomsen's thermochemical notation, the concept of Gibbs's heat function at constant pressure, and shows how to calculate heat effects in thermochemistry from first principles. It concludes with a formula relating how the heat of reaction changes with temperature (what we now call Kirchhoff's equation).

---

## 1. External Work in Chemical Processes (§§92–99)

Non-homogeneous systems are those containing boundaries between physically distinct portions — a liquid in contact with its vapour, a solid dissolving in a liquid, a reactant mixture transforming into products. Such processes are typically accompanied by large heat exchanges and, at constant pressure, by work due to volume changes.

For the First Law applied to a chemical process:

$$U_2 - U_1 = Q + W \tag{45}$$

In thermochemistry one typically works at **constant atmospheric pressure** $p_0$. Then the external work is (§99):

$$W = -\int_1^2 p_0\,dV = p_0(V_1 - V_2)$$

and equation (45) becomes:

$$U_2 - U_1 = Q + p_0(V_1 - V_2) \tag{47}$$

The work $p_0(V_1 - V_2)$ is generally negligible for reactions involving only solids and liquids (volume changes are tiny), but is significant when gases are produced or consumed. For a reaction converting $n_1$ gas molecules to $n_2$ gas molecules at temperature $\theta$:

$$\frac{W}{J} = \frac{R}{J}\theta(n_1 - n_2) \approx 1.97\,\theta\,(n_1 - n_2)\,\mathrm{cal}$$

(where $J$ is the mechanical equivalent of heat). This is the work correction between heat measured at constant pressure vs. constant volume.

---

## 2. Thomsen's Thermochemical Notation (§§93–97)

J. Thomsen's notation denotes the **internal energy** of a system in a given state by its chemical formula in brackets, e.g., $[\mathrm{Pb}]$, $[\mathrm{S}]$, $[\mathrm{PbS}]$. The heat effect of a reaction is then written as a difference of energy symbols. For lead sulphide formation:

$$[\mathrm{Pb}] + [\mathrm{S}] - [\mathrm{PbS}] = 18{,}400\,\mathrm{cal}$$

This notation makes thermochemical arithmetic look like algebra. Square brackets denote solids, parentheses denote liquids, braces denote gases. Aqueous solutions use the symbol (aq). The energy symbols can be added and subtracted like algebraic quantities, and Planck shows several examples of multi-step computations.

---

## 3. Gibbs's Heat Function at Constant Pressure (§100)

The key insight of §100 is that equation (47) can be rewritten as:

$$(U + p_0 V)_2 - (U + p_0 V)_1 = Q \tag{49}$$

So for **constant-pressure processes**, the heat effect equals the change in the quantity $(U + p_0 V)$, not just the change in $U$. This function is **Gibbs's heat function at constant pressure** (what we now call **enthalpy**, $H = U + pV$). When only constant-pressure processes are considered, the symbols [·], (·), {·} in Thomsen's notation are reinterpreted as the heat function rather than the bare energy. The advantage: the heat effect of any constant-pressure process is directly the difference of two heat-function values, with no further work correction needed.

---

## 4. Hess's Law — Path-Independence of Heat Effects (§§101–104)

The most important thermochemical consequence of the First Law is that the heat function $(U + p_0 V)$ is a **state function**. Therefore the heat effect of a process at constant pressure depends only on the initial and final states, not on the intermediate path. This is **Hess's law** (though Planck does not name it explicitly).

This principle enables calculation of heat effects for reactions that cannot be realised directly:

**Heat of neutralisation from indirect measurements (§101):** Thomsen measured:
$$(\mathrm{NaHCO_3\,aq}) + (\mathrm{NaOH\,aq}) - (\mathrm{Na_2CO_3\,aq}) = 9{,}200\,\mathrm{cal}$$
$$(\mathrm{CO_2\,aq}) + 2(\mathrm{NaOH\,aq}) - (\mathrm{Na_2CO_3\,aq}) = 20{,}200\,\mathrm{cal}$$
Subtracting gives the heat of CO₂ combining with NaOH to form NaHCO₃: $11{,}000\,\mathrm{cal}$, which Berthelot verified by direct measurement.

**Heat of formation of CO (§103):** Since carbon never burns exclusively to CO (always some CO₂), direct measurement is impossible. Favre and Silbermann measured the combustion of C to CO₂ and of CO to CO₂, and by subtraction obtained the heat of formation of CO from C and O₂: $29{,}000\,\mathrm{cal}$.

**Heat of formation of CS₂ (§104):** A beautiful four-step combination: burn S, burn C, burn CS₂ vapour to CO₂ and SO₂, and condense CS₂ vapour. Pure algebraic elimination gives:
$$[\mathrm{C}] + 2[\mathrm{S}] - (\mathrm{CS_2}) = -19{,}500\,\mathrm{cal}$$
The negative value means carbon bisulphide is *endothermal* — its formation from elements absorbs heat.

These examples illustrate the power of treating thermochemical equations as algebraic relations: unknown quantities are determined by linear combinations of measurable ones.

---

## 5. Effect of Temperature on Heat of Reaction (§105)

The heat function $(U + p_0 V)$ of each substance depends on temperature. Therefore the heat of reaction at temperature $\theta'$ differs from that at $\theta$ by the difference in heat capacities of products and reactants over that temperature range. Specifically:

$$Q_{\theta'} - Q_\theta = \left[(U_2 + p_0 V_2)_{\theta'} - (U_2 + p_0 V_2)_\theta\right] - \left[(U_1 + p_0 V_1)_{\theta'} - (U_1 + p_0 V_1)_\theta\right]$$

This is **Kirchhoff's equation**: $dQ/d\theta = C_{\text{products}} - C_{\text{reactants}}$, i.e., the rate of change of heat of reaction with temperature equals the difference in heat capacities between products and reactants.

**Example (§105):** For the combustion $\mathrm{H_2 + \tfrac{1}{2}O_2 \to H_2O(l)}$:
- Heat capacity of reactants ($\mathrm{H_2} + \tfrac{1}{2}\mathrm{O_2}$) = $6.82 + 3.47 = 10.29\,\mathrm{cal/K}$.
- Heat capacity of product ($\mathrm{H_2O}$, liquid) = $1 \times 18 = 18\,\mathrm{cal/K}$.
- Difference: $18 - 10.29 = 7.71$, but since products have *higher* capacity than reactants, the heat of combustion *decreases* by $7.7\,\mathrm{cal}$ per degree of temperature rise.

---

## Summary of Key Results

| Concept | Expression |
|---------|-----------|
| First Law at constant pressure | $(U+p_0V)_2 - (U+p_0V)_1 = Q$ |
| Heat function (enthalpy) | $H = U + p_0 V$ |
| Hess's law | Heat effect depends only on initial and final states |
| Work correction for gases | $\Delta W/J = 1.97\,\theta\,(n_1 - n_2)$ cal |
| Kirchhoff's equation | $dQ/d\theta = C_{\text{products}} - C_{\text{reactants}}$ |

The essential message of this chapter is that the First Law provides a **conservation law for the heat function at constant pressure**, enabling a complete algebraic treatment of thermochemistry by path-independence arguments. The Second Law will later add a *direction* to these heat effects — telling us which reactions are spontaneous — but the First Law already constrains the quantitative bookkeeping rigorously.

---

*[↑ Table of Contents](toc.md) · [← Back: Part II Ch.II — First Law (Homogeneous)](part-ii-ch-2-first-law-homogeneous.md) · [Next: Part III Ch.I — Second Law Introduction →](part-iii-ch-1-second-law-introduction.md)*
