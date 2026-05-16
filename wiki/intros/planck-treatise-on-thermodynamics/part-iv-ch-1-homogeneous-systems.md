---
title: "Part IV, Chapter I — Applications: Homogeneous Systems"
type: concept
tags: [second-law, homogeneous-systems, specific-heat, clausius-clapeyron, joule-thomson, stability, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part IV, Chapter I: Applications to Special States of Equilibrium — Homogeneous Systems (§§153–164)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This chapter applies the general thermodynamic relations (derived from both laws) to a single homogeneous system, deriving quantitative relations between measurable properties: relationships between $c_p$ and $c_v$, the influence of pressure on specific heat, the Joule–Thomson cooling effect for real gases, and conditions for thermodynamic stability.

---

## 1. Entropy Differentials for a Homogeneous Body (§153)

For a homogeneous body with specific entropy $\phi = \Phi/M$ as a function of $\theta$ and $v$, the definition $d\phi = (du + p\,dv)/\theta$ gives:

$$\left(\frac{\partial \phi}{\partial \theta}\right)_v = \frac{c_v}{\theta}, \qquad \left(\frac{\partial \phi}{\partial v}\right)_\theta = \left(\frac{\partial p}{\partial \theta}\right)_v \tag{81}$$

The second relation is the key thermodynamic identity derived from the consistency of cross-derivatives. It connects the pressure variation with temperature (at fixed volume) to the entropy variation with volume (at fixed temperature). Combined with the First Law result for $(\partial u/\partial v)_\theta$, it gives:

$$\left(\frac{\partial u}{\partial v}\right)_\theta = \theta\left(\frac{\partial p}{\partial \theta}\right)_v - p \tag{80}$$

This is the fundamental equation relating internal pressure to measurable $p$–$V$–$T$ properties — a direct test of the Second Law.

---

## 2. Difference of Specific Heats: $c_p - c_v$ (§§154–156)

Combining equations (80) and (81) with the First Law:

$$c_p - c_v = -\theta\left(\frac{\partial p}{\partial v}\right)_\theta \left(\frac{\partial v}{\partial \theta}\right)_p^2 \tag{83}$$

This is entirely in terms of measurable quantities. Since $(\partial p/\partial v)_\theta < 0$ always (increasing volume at constant $T$ decreases pressure), $c_p - c_v \geq 0$ always — except when the thermal expansion coefficient $(\partial v/\partial \theta)_p = 0$ (as in water at 4°C, where $c_p = c_v$).

**Example — Mercury at 0°C (§154):** Using the coefficient of thermal expansion and compressibility, $c_p - c_v \approx 0.0054\,\mathrm{cal/(g\cdot K)}$, giving $c_v = 0.0279\,\mathrm{cal/(g\cdot K)}$.

**For perfect gases:** $c_p - c_v = R/m$ (from Part II), which is consistent with equation (83) using $pv = R\theta/m$.

**Ratio $\gamma = c_p/c_v$ (§156):**
- Solids and liquids: $\gamma$ slightly greater than 1 (energy depends much more on $T$ than on $V$).
- Gases: $\gamma$ significantly greater than 1; smaller number of atoms per molecule → larger $\gamma$.
- Mercury vapour (monatomic): $\gamma = 1.666$ (Kundt and Warburg) — the maximum measured.

---

## 3. Influence of Pressure on Specific Heat (§157)

Using $p$ instead of $v$ as the independent variable, the cross-derivative consistency gives:

$$\left(\frac{\partial c_p}{\partial p}\right)_\theta = -\theta\left(\frac{\partial^2 v}{\partial \theta^2}\right)_p \tag{85}$$

This connects the rate of change of specific heat with pressure to the deviation from Gay-Lussac's law (curvature of the $V$–$T$ relation at constant $p$). For perfect gases, $(\partial^2 v/\partial \theta^2)_p = 0$, so $c_p$ is independent of pressure — consistent with the known result.

---

## 4. The Joule–Thomson Effect for Real Gases (§158)

The porous-plug experiment (§70) is revisited with the full power of the Second Law. For a real gas:

$$\left(\frac{\partial \theta}{\partial p}\right)_{H} = \frac{v}{c_p}\left(\theta\frac{\partial \ln v}{\partial \theta}\bigg|_p - 1\right) \tag{Joule-Thomson coefficient}$$

For a perfect gas, $v = R\theta/(mp)$, so $\theta(\partial \ln v/\partial \theta)_p = 1$, and the Joule–Thomson coefficient is zero — no temperature change. For real gases the coefficient can be positive (cooling on expansion, useful for liquefaction of gases) or negative (hydrogen and helium at room temperature, which heat on expansion until cooled below their **inversion temperature**).

---

## 5. Stability of Homogeneous States (§§159–164)

Thermodynamic stability requires that any spontaneous fluctuation away from equilibrium leads to a state of higher free energy (or lower entropy for an isolated system). For a homogeneous body, the condition of **stable equilibrium** at constant $T$ and $V$ requires that $F$ is a minimum, which translates to (§163):

- $(\partial p/\partial v)_\theta < 0$: pressure decreases with increasing volume (mechanical stability).
- $c_v > 0$: specific heat at constant volume is positive (thermal stability).

If either condition fails, the homogeneous state is unstable and the system spontaneously separates into two coexisting phases. This connects directly to the discussion of the critical point in Part I (§28): on the theoretical isotherm between the saturation points, $(\partial p/\partial v)_\theta > 0$ — the unstable middle branch. The loss of mechanical stability triggers phase separation.

The stability conditions provide the physical meaning of the van der Waals and Clausius equations: the three-valued region in the $p$–$v$ diagram corresponds to the region of instability, and the Maxwell equal-area rule (derived in §172 from the Second Law) picks out the physically realised saturation states.

---

## Summary of Key Relations

| Relation | Formula | Condition |
|----------|---------|-----------|
| Entropy–$p$ connection | $(\partial \phi/\partial v)_\theta = (\partial p/\partial \theta)_v$ | Always |
| Internal energy–pressure | $(\partial u/\partial v)_\theta = \theta(\partial p/\partial \theta)_v - p$ | Always |
| Specific heat difference | $c_p - c_v = -\theta(\partial p/\partial v)_\theta(\partial v/\partial \theta)_p^2$ | Always $\geq 0$ |
| $c_p$ pressure dependence | $(\partial c_p/\partial p)_\theta = -\theta(\partial^2 v/\partial \theta^2)_p$ | Always |
| Mechanical stability | $(\partial p/\partial v)_\theta < 0$ | Required for stable phase |

Chapter I of Part IV demonstrates how the entropy relations, once derived abstractly, translate into powerful quantitative constraints on measurable properties of any substance. The same framework extends to multi-phase and multi-component systems in the subsequent chapters.
