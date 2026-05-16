---
title: "Carnot — Gas Theory: Specific Heats, Isothermal Heat, and the Universality of Gas Properties"
type: concept
tags: [specific-heat, ideal-gas, isothermal-expansion, caloric, carnot, thermodynamics, cp-cv, adiabatic]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Section 3: Gas Theory — Specific Heats, Isothermal Heat, and the Universality of Gas Properties

## Deriving universal gas properties from the cycle theorem

Having established that all perfect engines operating between the same two temperatures produce equal motive power, Carnot turns to a productive application: since two different gases operating in the same cycle must exchange the same quantity of caloric (to produce the same motive power), their thermodynamic properties must be related by universal laws. This is the first example in the history of physics of using a cycle argument to derive material properties from first principles.

### Proposition 1: Universal isothermal heat

Consider two gases operated through the simplified two-reservoir cycle (two isothermals only, with infinitesimally small adiabatic steps). Since both gases are at the same temperature and pressure initially, they expand by the same volume ratio (Gay-Lussac's law), produce the same motive power, and therefore must exchange the same quantity of caloric with the reservoirs. Hence:

> **When a gas passes without change of temperature from one definite volume and pressure to another, the quantity of caloric absorbed or relinquished is always the same, whatever the nature of the gas.**

Carnot's example: 1 litre of air, carbonic acid, nitrogen, hydrogen, alcohol vapour, or water vapour, all at 100°C and atmospheric pressure — if the volume is doubled at constant temperature, each absorbs *exactly the same* quantity of heat. This is a profound universality result that would be re-derived (without Carnot's framework) only much later by Clausius. It follows from the ideal-gas equation of state combined with the cycle theorem.

## Estimating the isothermal heat: the acoustic datum

At this point Carnot needs a numerical value for the heat absorbed per unit volume change. He extracts it from the velocity of sound. Laplace had shown that sound velocity calculations require the assumption that rapid compressions are adiabatic; the experimental velocity of sound in air implies:

$$\text{Atmospheric air rises } 1°\text{C when suddenly compressed by } \tfrac{1}{116} \text{ of its volume.}$$

From this single datum and Gay-Lussac's expansion coefficient ($\frac{1}{267}$ per degree), Carnot constructs the ratio:

$$\frac{c_p}{c_v} = \frac{\frac{1}{116} + \frac{1}{267}}{\frac{1}{116}} = \frac{267 + 116}{267} = \frac{383}{267} \approx 1.435$$

So $c_v \approx 0.700$ when $c_p = 1.000$ (both measured relative to air at constant pressure). The difference $c_p - c_v = 0.300$ represents the fraction of heat per degree that goes into expansion work.

### The table of specific heats

Carnot produces a table of $c_p$ and $c_v$ for eight gases, using Delaroche and Bérard's measured values of $c_p$ and subtracting the universal constant 0.300:

| Gas | $c_p$ | $c_v$ |
|-----|-------|-------|
| Atmospheric Air | 1.000 | 0.700 |
| Hydrogen | 0.903 | 0.603 |
| Carbonic Acid | 1.258 | 0.958 |
| Oxygen | 0.976 | 0.676 |
| Nitrogen | 1.000 | 0.700 |
| Nitrous Oxide | 1.350 | 1.050 |
| Olefiant Gas (ethylene) | 1.553 | 1.253 |
| Carbon Monoxide | 1.034 | 0.734 |

### Proposition 2: Universal difference $c_p - c_v$

From the universality of isothermal heat and Gay-Lussac's law (all gases expand equally per degree), Carnot deduces:

> **The difference between specific heat under constant pressure and specific heat under constant volume is the same for all gases.**

This is expressed as: $c_p - c_v = 0.300$ (in Carnot's units, relative to $c_p$ of air). This result — known today as a consequence of the ideal-gas equation of state $PV = nRT$, from which $c_p - c_v = R$ per mole — was one of the most contested propositions in early thermodynamics. Clausius would later confirm it rigorously using Regnault's superior data.

## Proposition 3: Heat absorbed during expansion depends only on the volume ratio

Carnot next demonstrates that for a given mass of gas at a given temperature, the heat absorbed during isothermal expansion depends only on the *ratio* $V_f/V_i$, not on the absolute values. He states it in terms of geometric and arithmetic progressions:

> **When a gas increases in volume in geometrical progression, its specific heat increases in arithmetical progression.**

Equivalently: $Q = A + B \log v$, where $v$ is the volume. This anticipates the result from the ideal-gas cycle: $Q = nRT \ln(V_f/V_i)$. Carnot gives a physical example: 1 litre of air at 10°C compressed to ½ litre releases a fixed quantity of heat; compressing further from ½ to ¼ litre releases the *same* quantity again.

He also applies this to explain adiabatic compression heating quantitatively — when air is compressed $\frac{1}{14}$-fold its volume, the temperature should rise by about 300°C, sufficient to ignite tinder (which is observed experimentally in the air-gun).

## Variation of specific heat with density

Carnot also deduces that $c_v$ increases as the gas expands (decreases in density). This follows from the consistency condition on the cycle: if $c_v$ were independent of density, one could derive $c_v$ changes from the cycle theorem. He concludes that specific heat increases logarithmically with volume. He constructs a table of $c_p$ for air at pressures ranging from $\frac{1}{1024}$ to $1024$ atmospheres, showing $c_p$ varying from 1.840 to 0.160 — a striking extrapolation far beyond any experimental data of the time.

## Significance

This section of the *Réflexions* demonstrates that the cycle theorem is not merely a statement about engines: it is a machine for generating thermodynamic identities among material properties. Carnot extracts from a single thought-experiment constraints on $c_p$, $c_v$, their difference, their variation with volume, and the heat of expansion. Many of these results were later re-derived by Clausius, who was unaware of Carnot's priority. The approach anticipates [[Maxwell relations]] and the method of deriving material properties from fundamental thermodynamic potentials.

---

*[↑ Table of Contents](toc.md) · [← Back: The Carnot Cycle and Universality Proof](02-the-carnot-cycle-and-universality-proof.md) · [Next: Efficiency, Numerical Estimates, and Practical Engines →](04-efficiency-numerical-estimates-and-practical-engines.md)*
