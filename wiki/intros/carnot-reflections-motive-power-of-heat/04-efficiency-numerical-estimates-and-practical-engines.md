---
title: "Carnot — Efficiency: Numerical Estimates, Temperature Dependence, and Practical Steam Engines"
type: concept
tags: [carnot-efficiency, steam-engine, motive-power, temperature-dependence, high-pressure, cornish-engine, numerical-estimates]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Section 4: Efficiency — Numerical Estimates, Temperature Dependence, and Practical Steam Engines

## Temperature dependence of efficiency

Carnot cannot assume that equal temperature drops produce equal motive power — this would require $\mu(t) = $ constant. He tests this assumption through careful reasoning. Consider two identical cycles of air, one operating between 100° and 100°−$h$ degrees, the other between 1° and 1°−$h$. The *motive power* produced in each cycle is the same (same volume changes, same pressure differences). But the *heat supplied* differs:

- At higher temperature, more heat is needed to maintain isothermal expansion (because the specific heat at higher density is different, and the thermal equation of state changes).
- Specifically, the heat absorbed during expansion at 100° is greater than at 1° (because the gas is denser at lower temperature and thus needs less heat per unit volume expansion — actually, Carnot shows it the other way: the heat per expansion at higher $T$ is greater).

He deduces: **equal motive power from larger heat at higher temperatures means the motive power per unit of heat is less at high temperatures than at low temperatures.** In Carnot's words:

> **The fall of caloric produces more motive power at inferior than at superior temperatures.**

This is his formulation of what we now know as $\mu(t)$ being a decreasing function of $t$ — confirmed numerically by Kelvin from Regnault's data, where $\mu$ falls from 4.960 at 1°C to 3.134 at 231°C.

## Numerical estimates: the motive power coefficient

Carnot performs three numerical calculations to verify that the motive power is independent of the working substance (at the same temperature range), despite the quantitative imprecision of his data.

### Air at 0° and 1°C

Using:
- Expansion coefficient $\frac{1}{267}$ per degree (Gay-Lussac)
- Acoustic datum: $\frac{1}{116}$ compression raises air 1°C
- Atmospheric pressure equivalent: 10.40 m head of water
- Specific heat of air: $c_p = 0.267$ (relative to water)

He computes the motive power for 1 kg of air expanded by $\frac{1}{116} + \frac{1}{267}$ of its volume at a temperature difference of $\frac{1}{1000}$°, then scales to 1 degree and 1000 units of heat:

$$W = 1.395 \text{ units of motive power per 1000 units of heat}$$

where one unit of motive power = 1 cubic metre of water raised 1 metre, and one unit of heat = heat to raise 1 kg water by 1°C.

### Steam at 100°C and 99°C

Using Dalton's vapour-pressure table (tension at 100° minus tension at 99° = 26 mm Hg = 0.36 m head of water) and the latent heat of steam at 100° ($\approx 550$ units):

$$W = \frac{1.700 \times 0.36}{550} \times 1000 \approx 1.112$$

where 1.700 m³ is the volume of 1 kg of steam at 100°C. This is 0.611 units of motive power from 550 units of heat.

### Steam at 0°C and 1°C

Applying the Clément–Desormes law (the constituent heat of steam is the same at any temperature), the latent heat at 0° is $550 + 100 = 650$ units. Repeating the calculation:

$$W \approx 1.290$$

### Alcohol vapour at 78.7°C and 77.7°C

Using Delaroche–Bérard's latent heat (207 units/kg) and Bétancour's tension data ($\frac{1}{25}$ decrease per degree below boiling):

$$W \approx 1.230$$

All four estimates — 1.395, 1.112, 1.290, 1.230 — agree to within the uncertainty of the experimental data (mostly within $\frac{1}{10}$–$\frac{1}{13}$), constituting a verification of the universality principle.

## Practical implications: principles for optimal engines

From the efficiency theorem, Carnot derives three engineering principles:

1. **Raise the hot reservoir temperature as high as possible** — to maximise the temperature fall exploited.
2. **Lower the cold reservoir temperature as low as possible** — for the same reason.
3. **All temperature change in the working fluid must be due to volume change** — i.e., expansion must be adiabatic between the two isothermals.

He articulates the implication for high-pressure steam: a boiler at 160°C and condenser at 40°C uses a fall of 120°C, while coal combustion could in principle supply a fall of 1000°C. Only $\frac{120}{1000}$ of the available fall is utilised. He estimates:

- 1 kg of carbon yields 7000 units of heat.
- If all that heat fell from 1000° to 0°, the theoretical maximum motive power would be roughly $7 \times 560 = 3920$ units.
- The best Cornish engines (Wheal Abraham) achieved about 195 units per kilogram of coal.
- This is only $\frac{1}{20}$ of the theoretical maximum.
- The old Chaillot engine achieved 22 units/kg — about $\frac{1}{180}$ of maximum.

## The case for compound and high-pressure engines

Carnot explains Watt's cutoff principle: admit steam for only the first quarter of the stroke, then let it expand adiabatically for the remainder. Watt computed (by Mariotte's law, though Carnot notes this is approximate) a mean pressure of 0.579 times the initial pressure, producing more than half the effect from only a quarter of the steam. Carnot sees the double-cylinder (compound) engine of Hornblower and Woolf as an extension of this idea, and even suggests a *triple-expansion* engine — which became standard practice half a century later.

He argues the essential advantage of high-pressure engines lies not in the pressure per se but in the *larger temperature fall* they permit: steam at 6 atm operates at 160°C instead of 100°C, increasing the exploitable fall from 60° to 120°.

## The closing paragraph: practical wisdom

Carnot ends the main text with a famous passage on engineering judgment — the same paragraph quoted by Thurston in the editor's preface. It says that full utilisation of combustible is rarely the primary objective; safety, durability, size, and cost often take precedence. The art of the engineer is to balance these considerations correctly, a statement as valid today as in 1824.

---

*[↑ Table of Contents](toc.md) · [← Back: Gas Theory, Specific Heats, and Heat of Expansion](03-gas-theory-specific-heats-and-heat-of-expansion.md) · [Next: Kelvin's Account of Carnot's Theory →](05-kelvin-account-of-carnots-theory.md)*
