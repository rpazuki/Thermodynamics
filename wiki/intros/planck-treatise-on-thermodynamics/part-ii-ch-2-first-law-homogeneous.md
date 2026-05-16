---
title: "Part II, Chapter II — First Law: Applications to Homogeneous Systems"
type: concept
tags: [first-law, internal-energy, perfect-gas, joule-thomson, adiabatic, specific-heat, carnot-cycle, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part II, Chapter II: First Law — Applications to Homogeneous Systems (§§67–91)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This long and technically rich chapter applies the First Law to a single homogeneous substance (defined by mass $M$, temperature $\theta$, and volume $V$). It derives the internal energy of a perfect gas, develops the thermodynamics of adiabatic and isothermal processes, obtains expressions for specific heats and their ratio $\gamma$, and works through the Carnot cycle for a perfect gas — producing the efficiency formula and absolute thermometric scale as consequences of the First Law alone.

---

## 1. Internal Energy of a Perfect Gas (§§67–70)

The First Law for a homogeneous system is $U_2 - U_1 = Q + W$. To determine how internal energy $U$ depends on temperature $\theta$ and volume $V$, Planck analyses two key experiments:

**Joule's free-expansion experiment (§68–69):** A gas expands into a vacuum (rigid, non-conducting walls). No work is done ($W = 0$ since walls are rigid), no heat is exchanged ($Q = 0$ since walls are non-conducting), so $U_2 = U_1$. Joule found the temperature of the gas after free expansion to be unchanged: $\theta_2 = \theta_1$. Since volume increased ($V_2 > V_1$) while both $U$ and $\theta$ stayed constant, the internal energy of a perfect gas must depend only on temperature, not on volume:

$$\left(\frac{\partial U}{\partial V}\right)_\theta = 0 \tag{19}$$

**Thomson–Joule (porous-plug) experiment (§70):** A more precise version. Gas flows steadily from high pressure $p_1$ to low pressure $p_2$ through a porous plug. The work done *on* the gas by the upstream pressure is $p_1 V_1$; work done *by* the gas against downstream pressure is $p_2 V_2$. For a perfect gas, $p_1 V_1 = p_2 V_2$ (Boyle's law), so the net work is zero. No heat flows. Therefore $U_2 = U_1$ with unchanged temperature but different volume — confirming equation (19). For real gases (hydrogen, air), the small observed temperature changes directly measure $(\partial U/\partial V)_\theta \neq 0$.

---

## 2. Energy and Specific Heats of a Perfect Gas (§§80–88)

Since $(\partial U/\partial V)_\theta = 0$, the energy of a perfect gas depends only on temperature:

$$U = M \int c_v\,d\theta + \mathrm{const} \equiv M(c_v\theta + \mathrm{const}) \quad \text{(if $c_v$ is constant)}  \tag{35}$$

where $c_v$ is the **specific heat at constant volume**.

The heat absorbed in a reversible process at constant volume (isochoric) is simply $Q = dU = Mc_v\,d\theta$, giving $c_v = Q/(M\,d\theta)$ directly.

For a reversible process at constant pressure (isobaric), combining the First Law $Q = dU + p\,dV$ with the characteristic equation gives:

$$c_p - c_v = \frac{p}{M}\left(\frac{\partial V}{\partial \theta}\right)_p = \frac{R}{m} \tag{31}$$

The difference $c_p - c_v = R/m$ is the universal gas constant per unit molecular weight — a purely mechanical result from the characteristic equation. For air ($m \approx 29$), this equals about $0.068\,\mathrm{cal/(g\cdot K)}$.

The **ratio of specific heats** $\gamma = c_p/c_v$ plays a central role:
- Monatomic ideal gases: $\gamma = 5/3 \approx 1.667$ (measured for mercury vapour by Kundt and Warburg).
- Diatomic gases (H₂, O₂, N₂, air): $\gamma = 7/5 = 1.41$.

Planck tabulates $c_p$, $c_v$, and $\gamma$ for several gases (§87), noting that fewer atoms per molecule → larger $\gamma$ (a hint towards kinetic theory, but not used).

---

## 3. Isothermal and Adiabatic Processes (§§84–89)

**Isothermal process** ($d\theta = 0$): For a perfect gas at constant temperature, $dU = 0$ (since $U$ depends only on $\theta$), so $Q = p\,dV$: all heat absorbed is converted to work. The work done on the gas in isothermal compression from $V_1$ to $V_2$ is:

$$W = -\int_{V_1}^{V_2} p\,dV = -\frac{RM\theta}{m}\ln\frac{V_2}{V_1}$$

**Adiabatic process** ($Q = 0$): No heat exchange. The First Law gives $dU = W = -p\,dV$, so $Mc_v\,d\theta = -p\,dV$. Substituting the characteristic equation and integrating gives the **Poisson adiabatic relation**:

$$p V^\gamma = \mathrm{const}, \quad \text{or equivalently} \quad \theta V^{\gamma-1} = \mathrm{const} \tag{(88)}$$

This is purely a consequence of the First Law plus the perfect-gas equation of state.

---

## 4. The Carnot Cycle for a Perfect Gas (§90)

Planck presents the Carnot cycle consisting of four reversible steps for a perfect gas between heat reservoirs at $\theta_2$ (hot) and $\theta_1$ (cold), $\theta_2 > \theta_1$:

1. **Isothermal expansion at $\theta_2$:** gas absorbs heat $Q_2 > 0$ from hot reservoir and does work.
2. **Adiabatic expansion from $\theta_2$ to $\theta_1$:** no heat; temperature drops.
3. **Isothermal compression at $\theta_1$:** gas gives heat $Q_1' = |Q_1| > 0$ to cold reservoir.
4. **Adiabatic compression from $\theta_1$ back to $\theta_2$:** no heat; temperature rises.

Using the adiabatic relation and Boyle's law, Planck shows:

$$Q_1 : Q_2 : W = (-\theta_1) : \theta_2 : (\theta_1 - \theta_2) \tag{44}$$

where $W < 0$ is the work done on the gas (i.e., the gas does net work $W' = \theta_2 - \theta_1$ per unit heat $\theta_2$ absorbed). The **efficiency** is:

$$\eta = \frac{W'}{Q_2} = \frac{\theta_2 - \theta_1}{\theta_2} = 1 - \frac{\theta_1}{\theta_2}$$

This result — obtained here from the First Law alone for a perfect gas — will be proved in Part III (§137) to hold for **any** working substance in a reversible cycle, as a consequence of the Second Law.

---

## 5. Significance of the Carnot Result at the First-Law Level

At this stage (Part II), the Carnot efficiency formula has been derived for a *perfect gas* using only the First Law and empirical gas laws. Its generality (for any substance) requires the Second Law and will be established in §137. The structure is pedagogically important: Planck shows what can and cannot be concluded from the First Law alone.

The First Law alone does not determine:
- The direction of heat flow.
- Whether a given spontaneous process will occur.
- The maximum efficiency of any engine operating between two temperatures.

All of these require the Second Law.

---

## Summary of Key Results

| Result | Expression |
|--------|-----------|
| Internal energy of perfect gas | $U = M(c_v\theta + \mathrm{const})$ |
| Specific heat difference | $c_p - c_v = R/m$ |
| Adiabatic relation | $pV^\gamma = \mathrm{const}$, $\theta V^{\gamma-1} = \mathrm{const}$ |
| Carnot efficiency (perfect gas) | $\eta = 1 - \theta_1/\theta_2$ |
| Carnot heat ratios | $Q_1 : Q_2 = -\theta_1 : \theta_2$ |
| First Law (infinitesimal) | $Q = dU + p\,dV$ |

---

*[↑ Table of Contents](toc.md) · [← Back: Part II Ch.I — First Law (General)](part-ii-ch-1-first-law-general.md) · [Next: Part II Ch.III — Thermochemistry →](part-ii-ch-3-first-law-non-homogeneous.md)*
