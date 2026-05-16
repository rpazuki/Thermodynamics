---
title: "Part I, Chapter I — Temperature"
type: concept
tags: [temperature, thermometry, characteristic-equation, van-der-waals, real-gases, critical-point, thermal-equilibrium, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part I, Chapter I: Temperature (§§1–32)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This first chapter lays the entire empirical and mathematical foundation for the book. It moves from the primitive sensation of warmth through operational definitions of temperature, to the characteristic equation of state $p = f(v,t)$, to a detailed treatment of perfect and real gases, the critical point, and gas mixtures. The chapter is effectively a mini-course in classical thermometry and equation-of-state physics.

---

## 1. Thermal Equilibrium and the Zeroth Law (§§1–3)

Planck begins phenomenologically: *heat* arises from the direct sensation of warmth or coldness, but this sensation is qualitative and instrument-dependent. The first quantitative foothold is the **change of volume** that bodies undergo when heated under constant pressure.

The key empirical observation is that when any number of differently heated bodies are brought into mutual contact, **a state of thermal equilibrium is eventually reached** in which all change ceases. From this comes the fundamental transitivity property: if body $A$ is in thermal equilibrium with $B$, and $A$ is in thermal equilibrium with $C$, then $B$ and $C$ are in thermal equilibrium with each other. This is the content of what we now call the **Zeroth Law of Thermodynamics**, though Planck does not name it as such.

This transitivity allows comparison of heat states without direct contact: use a standard body $A$ (e.g., a mercury thermometer) as an intermediary.

---

## 2. Definition of Temperature (§§3–5)

**Temperature** is defined operationally as the volumetric reading of the standard body $A$ (the thermometric substance) calibrated so that:
- Temperature $= 0°$ when $A$ is in equilibrium with melting ice at atmospheric pressure.
- Temperature $= 100°$ when $A$ is in equilibrium with steam at atmospheric pressure.

This defines the **Centigrade scale** relative to $A$. The problem is that different thermometric substances give different intermediate readings — mercury, alcohol, air, etc., all disagree except at 0° and 100°. This arbitrariness motivates the choice of **permanent gases** (H₂, O₂, N₂, CO) as preferred thermometric substances (§4), because:
- They agree with each other almost perfectly over a wide range.
- Their coefficient of expansion under constant pressure is the same for all of them: $\alpha \approx \tfrac{1}{273}$ per degree Celsius.

A truly absolute, substance-independent definition of temperature requires the **Second Law** and is deferred to §160.

---

## 3. The Perfect Gas and Its Characteristic Equation (§§6–15)

For a homogeneous body, the **characteristic equation** (equation of state) is:

$$p = f(v, t)$$

where $p$ is pressure, $v = V/M$ is specific volume (volume per unit mass), and $t$ is temperature. All other thermodynamic properties of the substance follow from this function.

For a **perfect gas**, three empirical laws combine:
- **Boyle–Mariotte:** $pv = T(\theta)$ at constant temperature.
- **Gay-Lussac:** volume increases linearly with temperature at constant pressure, with coefficient $\alpha = \tfrac{1}{273}$.
- **Universality:** $\alpha$ is the same for all permanent gases.

Combining these and shifting the temperature zero by $\tfrac{1}{\alpha} \approx 273°$ degrees, Planck introduces **absolute temperature** $\theta = t + 273$, giving the remarkably simple characteristic equation:

$$p = \frac{C}{v}\,\theta = \frac{CM}{V}\,\theta \tag{5}$$

where $C$ is a substance-specific constant. This is equivalent to measuring temperature by the volume of the gas (at constant pressure) rather than by a volume *change*. The result is that $\theta = 0$ corresponds to a hypothetical state of zero volume — absolute zero.

Planck then derives the three standard coefficients:
- **Coefficient of expansion** (isobaric): $\tfrac{1}{\theta_0} \cdot (\partial v/\partial \theta)_p = \alpha = \tfrac{1}{273}$.
- **Pressure coefficient** (isochoric): $\tfrac{1}{p_0} \cdot (\partial p/\partial \theta)_v = \alpha$.
- **Coefficient of compressibility** (isothermal): $-\tfrac{1}{v} \cdot (\partial v/\partial p)_\theta = \tfrac{1}{p}$.

These are not independent: equation (6) shows that any one can be computed from the other two via the triple-product rule:

$$\left(\frac{\partial v}{\partial \theta}\right)_p = -\frac{(\partial p/\partial \theta)_v}{(\partial p/\partial v)_\theta}$$

---

## 4. Mixtures of Perfect Gases and Dalton's Law (§§16–20)

When different perfect gases mix at constant temperature and pressure, the total volume equals the sum of the pre-diffusion volumes. After diffusion, each gas occupies the full total volume but exerts only a **partial pressure**. Planck shows (§17–18) that the second view — partial pressures with shared volume — is the only physically consistent one. The partial pressure of gas $i$ is:

$$p_i = \frac{C_i M_i \theta}{V} = \frac{V_i}{V} p$$

and their sum equals the total pressure (Dalton's law):

$$p_1 + p_2 + \cdots = p \tag{8}$$

The characteristic constant of the mixture is the mass-weighted average of the individual constants (§19), meaning the mixture behaves as a single perfect gas with an **apparent molecular weight** (§41).

---

## 5. Real Gases, Van der Waals, and Clausius Equations (§§21–31)

Permanent gases obey the perfect-gas equation only approximately; condensable vapours deviate substantially. Planck presents two empirical equations for real substances:

**Van der Waals equation** (§24):

$$p = \frac{R\theta}{v - b} - \frac{a}{v^2}$$

where $a$ accounts for intermolecular attraction and $b$ for molecular volume. For large $v$ it reduces to the perfect-gas law. However, Planck treats this *purely as an empirical formula*, without endorsing the kinetic-theory interpretation.

**Clausius equation** (§25), more accurate for CO₂:

$$p = \frac{R\theta}{v - a} - \frac{c}{\theta(v+b)^2}$$

Both equations predict **three real roots** of $v$ for a given $p$ at low temperatures (the isotherm is a cubic), corresponding to gaseous, liquid, and an unphysical middle branch. Graphically, the system of isotherms in the $p$–$v$ plane shows:

- A family of curves approaching hyperbolae at high $T$.
- A **critical point** $K$ where three roots coalesce into one (§28), characterised by:
$$\left(\frac{\partial p}{\partial v}\right)_\theta = 0, \qquad \left(\frac{\partial^2 p}{\partial v^2}\right)_\theta = 0$$

For CO₂ using Clausius's equation: $\theta_c = 304\,\mathrm{K}$, $p_c = 77\,\mathrm{atm}$, $v_c = 2.27\,\mathrm{cm^3/g}$ — values well verified by Andrews's experiments (§29–30).

Above the critical temperature, **condensation does not occur**; below it, isothermal compression leads to phase separation. Planck notes that there is no sharp boundary between gas and liquid: one can circumnavigate the critical point on a path that passes continuously from purely gaseous to purely liquid states, so the classical distinction between gas, vapour, and liquid is not fundamental (§29).

The same logic applies tentatively to the liquid–solid transition (§31): Planck conjectures a solid–liquid critical point, though experiments at the time were insufficient to confirm it. Some substances (pitch, glass) indeed show a continuous solid-to-liquid transition, supporting the analogy.

---

## 6. Key Equations Summary

| Quantity | Expression |
|----------|-----------|
| Perfect gas characteristic equation | $p = \frac{C}{v}\theta$ |
| Universal gas constant form | $p = \frac{R}{m}\frac{\theta}{v}$, with $R = 82{,}600{,}000$ (abs. units) |
| Dalton's law | $p = \sum_i p_i$ |
| Van der Waals | $p = \frac{R\theta}{v-b} - \frac{a}{v^2}$ |
| Critical point conditions | $(\partial p/\partial v)_\theta = 0$ and $(\partial^2 p/\partial v^2)_\theta = 0$ |

---

## Conceptual Significance

Chapter I accomplishes two things simultaneously: it grounds thermodynamics in operational measurement (the thermometer), and it establishes the mathematical language (characteristic equations, partial derivatives, isothermal/isobaric/isochoric changes) that will be applied throughout. The treatment of the critical point and the continuity between phases is especially forward-looking. By refusing to explain *why* the gas laws hold in terms of molecules, Planck keeps the discussion general — the same equations will later appear as limits of more general results derived from the two laws.
