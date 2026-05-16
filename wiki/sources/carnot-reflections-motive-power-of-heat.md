---
title: "Reflections on the Motive Power of Heat and on Machines Fitted to Develop That Power"
type: source
tags: [thermodynamics, carnot-cycle, reversibility, caloric-theory, heat-engines, efficiency, second-law, history-of-science]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Reflections on the Motive Power of Heat

## Citation

Carnot, N.-L.-S. (1824). *Réflexions sur la puissance motrice du feu et sur les machines propres à développer cette puissance*. Paris: Bachelier. English translation by R. H. Thurston (1897). *Reflections on the Motive Power of Heat and on Machines Fitted to Develop That Power*. New York: John Wiley & Sons. Accompanied by a biographical sketch by H. Carnot and an account of Carnot's theory by Sir William Thomson (Lord Kelvin). Project Gutenberg eBook #78610.

## Raw path

`raw/Thermodynamics/Carnot/pg78610.txt`

## Summary

Sadi Carnot's 1824 *Réflexions* is the founding document of [[thermodynamics]], published when its author was 23 or 24 years old. In 91 pages Carnot establishes that heat-engines operate by transferring [[caloric]] from a hot body to a cold body, and that the maximum [[motive-power]] producible from a given quantity of heat is determined solely by the temperatures of the two reservoirs — not by the nature of the working substance. He demonstrates this through a reductio ad absurdum: any engine that could exceed this maximum could be coupled in reverse to restore the initial conditions, yielding net work from no thermal change — a perpetual motion of the second kind, which he takes as inadmissible. The Carnot [[reversible-cycle]] — two isothermal and two adiabatic steps — is introduced as the ideal engine that attains this maximum. Although Carnot works within the caloric theory (heat as an indestructible fluid), his main conclusions survive the subsequent transition to the dynamical theory; his unpublished notes, excerpted in the appendix, reveal that by 1832 he had privately abandoned caloric and estimated the mechanical equivalent of heat to within 1.5% of the correct value. The volume also contains Lord Kelvin's 1849 paper "Account of Carnot's Theory," which places Carnot's results on a rigorous mathematical footing using Regnault's experimental data, introduces Carnot's coefficient $\mu$, and evaluates actual steam-engine efficiencies against the theoretical maximum.

## Key claims

1. **Universality of the maximum**: The motive power obtainable from a given quantity of heat passing between bodies at temperatures $T_H$ and $T_C$ is the same regardless of the working substance (steam, air, alcohol vapour, or any other elastic fluid), provided the cycle is reversible.

2. **Necessary condition for the maximum**: No temperature change in the working fluid may occur except as a result of a change in volume (i.e., there must be no direct caloric exchange between bodies of different temperatures). This is the condition that every stage be quasi-static and reversible.

3. **Waterfall analogy**: Motive power from heat is analogous to the work done by a waterfall — it depends on the "height of the fall" (the temperature difference) and the "quantity of the liquid" (the quantity of heat), not on the particular mechanism.

4. **Universality of specific-heat relations**: The difference between the specific heat of a gas at constant pressure and at constant volume is the same for all gases. Carnot computes the ratio $c_p/c_v$ for atmospheric air as $383/267 \approx 1.435$, yielding $c_v \approx 0.700$ (with $c_p = 1.000$ as the standard).

5. **Heat absorbed during isothermal expansion**: When a gas expands or contracts at constant temperature, the heat absorbed or released depends only on the ratio of volumes, not on the absolute volumes — i.e., heat $\propto \log(V_2/V_1)$, universal for all elastic fluids.

6. **Temperature dependence of efficiency**: Motive power per unit of caloric is greater at lower temperatures than at higher temperatures ("the fall of caloric produces more motive power at inferior than at superior temperatures"). The coefficient $\mu$ is a decreasing function of temperature.

7. **Practical corollary — high-pressure engines**: The superiority of high-pressure steam-engines lies essentially in their utilisation of a larger fall of caloric; full advantage requires adiabatic expansion to the cold-reservoir temperature.

8. **Conservation of motive power (in unpublished notes)**: Heat is motive power in disguise — "motive power is, in quantity, invariable in nature; it is never produced or destroyed." Carnot estimates the mechanical equivalent of heat as $\approx 2.70$ units of motive power (dynames) per unit of heat, equivalent to $\sim 370$ kilogram-metres per kilocalorie — close to Mayer's later value of 365 and within 15% of the correct value.

## Methods

Carnot's argument is entirely thought-experimental and deductive rather than mathematical. His chief tool is the *reductio ad absurdum*: assume a more efficient engine exists, couple it in reverse with the optimal engine, and show the combination produces work from nothing. The cycle for a perfect engine is described verbally and geometrically (with reference to a cylinder-piston apparatus) in six steps for steam and four steps for air, with the adiabatic legs connecting the two isothermals. Numerical estimates are made using then-current experimental data: Gay-Lussac's law of thermal expansion, Dalton's vapour-pressure tables, Delaroche and Bérard's specific-heat measurements, and the acoustic datum that air rises 1°C per $\frac{1}{116}$ compression. All calculations are approximate and Carnot explicitly acknowledges their limitations.

## Limitations

- The entire argument assumes the caloric theory: heat is an indestructible substance, so the same amount that enters the cycle must leave it. This assumption is wrong; it is the First Law that saves the main conclusions by requiring that after a complete cycle the working substance returns to its initial state.
- Carnot cannot specify the functional form of efficiency vs. temperature without knowing the mechanical equivalent of heat; he identifies $\mu(t)$ as an empirical function to be determined.
- Experimental data available in 1824 were highly inaccurate (Delaroche and Bérard, Dalton), leading to numerical estimates 10–30% off the true values.
- The analysis is limited to reversible processes; irreversibility and entropy are not defined (those concepts await Clausius).
- Solid and liquid working substances are correctly dismissed as impractical for heat engines, but without a clear thermodynamic reason (small $\Delta V$ on heating means the isothermal legs produce negligible work).

## Connections

- [[reversible-cycle]] — Carnot's central concept; the template for all subsequent thermodynamic idealisations.
- [[caloric-theory]] — The theoretical scaffolding Carnot uses; abandoned after Joule and Clausius.
- [[second-law-of-thermodynamics]] — Carnot's impossibility argument is the embryonic form of the Second Law; Clausius made it precise.
- [[carnot-efficiency]] — The ratio $\eta = 1 - T_C/T_H$ (in absolute temperature); Kelvin's paper derives the proportionality $M = H \int_T^S \mu\, dt$ and evaluates $\mu$ from Regnault's data.
- [[planck-treatise-on-thermodynamics]] — Planck's 1897 treatise builds systematically on the foundations Carnot established, rigorously deriving entropy and free energy.
- [[entropy]] — The quantity Clausius later defined to capture what Carnot's cycle conserves in the reversible limit.
- [[kelvin-account-of-carnots-theory]] — Kelvin's 1849 paper reprinted here is the paper that rescued Carnot from obscurity and placed his results in the modern framework.

## Quotes

> "The production of motive power is then due in steam-engines not to an actual consumption of caloric, but *to its transportation from a warm body to a cold body*, that is, to its re-establishment of equilibrium — an equilibrium considered as destroyed by any cause whatever, by chemical action such as combustion, or by any other."

> "The motive power of heat is independent of the agents employed to realize it; its quantity is fixed solely by the temperatures of the bodies between which is effected, finally, the transfer of the caloric."

> "Heat is simply motive power, or rather motion which has changed form. It is a movement among the particles of bodies. Wherever there is destruction of motive power there is, at the same time, production of heat in quantity exactly proportional to the quantity of motive power destroyed. Reciprocally, wherever there is destruction of heat, there is production of motive power. We can then establish the general proposition that motive power is, in quantity, invariable in nature; that it is, correctly speaking, never either produced or destroyed." *(from the unpublished notes, Appendix A)*
