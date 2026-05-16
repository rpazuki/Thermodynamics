---
title: "Carnot — The Reversible Cycle and the Proof of Universality"
type: concept
tags: [carnot-cycle, reversibility, perpetual-motion, universality, isothermal, adiabatic, heat-engines, second-law]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Section 2: The Reversible Cycle and the Proof of Universality

## The first proof: by steam

Carnot's first demonstration of universality uses steam as the working substance. He describes a four-stage cycle operating between a furnace (body $A$ at high temperature) and a refrigerator (body $B$ at low temperature):

1. **Isothermal expansion at $T_A$**: Contact with $A$; steam absorbs caloric and expands at constant temperature.
2. **Adiabatic expansion**: $A$ removed; steam expands without caloric exchange, cooling until it reaches $T_B$.
3. **Isothermal compression at $T_B$**: Contact with $B$; steam releases caloric and is compressed at constant temperature.
4. **Adiabatic compression**: $B$ removed; steam compressed without caloric exchange, heating back to $T_A$.

The piston does more work during expansion (steps 1–2, higher temperature, higher pressure) than is consumed during compression (steps 3–4, lower temperature, lower pressure). The excess is the net motive power produced.

### The reversibility argument

Carnot then observes that every one of these operations can be run in the *opposite* order and direction. The inverse cycle uses up exactly the net motive power produced by the direct cycle, and returns exactly the same quantity of caloric from $B$ back to $A$. The system is perfectly reversible.

Now comes the key logical move. Suppose there existed a second engine $E'$ — using a different working substance — that could produce more motive power from the same caloric fall from $A$ to $B$. Then:

- Run $E'$ forward: extra motive power produced.
- Use part of this motive power to run the original engine $E$ *backwards*.
- The reverse cycle of $E$ returns all the caloric from $B$ to $A$, restoring initial conditions.
- Net result: the system (furnace + refrigerator + combined engine) has produced work from nothing, with no net transfer of caloric and no change in any body.

This is perpetual motion of the second kind — a **continuous creation of motive power without consumption of caloric or any other agent**. Carnot takes this as "entirely contrary to ideas now accepted, to the laws of mechanics and of sound physics" and declares it **inadmissible**.

Therefore:

> **The maximum of motive power resulting from the employment of steam is also the maximum of motive power realizable by any means whatever.**

## The condition for maximum: no irreversible heat exchange

Carnot identifies the precise condition the engine must satisfy to attain this maximum:

> **In the bodies employed to realise the motive power of heat, there should not occur any change of temperature which may not be due to a change of volume.**

In other words, no direct heat exchange between bodies of different temperatures is permitted. Any such exchange — for example, letting hot steam touch a cooler metal — represents caloric re-establishing equilibrium *without producing work*, which is a pure loss. The isothermal and adiabatic steps of the ideal cycle are designed precisely to avoid this: during isothermals, the working substance is in contact only with a reservoir at exactly the same temperature; during adiabatics, there is no contact at all.

He notes that in practice, some irreversibility is unavoidable (a finite temperature difference is needed to drive any heat flow), but it "may be supposed as slight as we please" and treated as negligible in theory.

## The second proof: by air

Carnot gives a second, more rigorous demonstration using atmospheric air as the working substance. The four-step cycle is the same in structure:

1. Air in contact with $A$ (temperature $T_A$); piston rises (isothermal expansion), $A$ supplies caloric.
2. $A$ removed; piston continues to rise (adiabatic expansion); temperature falls from $T_A$ to $T_B$.
3. Air in contact with $B$ (temperature $T_B$); piston descends (isothermal compression), $B$ absorbs caloric.
4. $B$ removed; piston compressed (adiabatic compression); temperature rises from $T_B$ back to $T_A$.

The advantage of the air engine over steam for this demonstration is that after a complete cycle the air is *exactly* restored to its initial state (pressure, volume, temperature) with no residual phase change — making the reversibility argument watertight.

Carnot explicitly notes: "We have chosen atmospheric air as the instrument which should develop the motive power of heat, but it is evident that the reasoning would have been the same for all other gaseous substances, and even for all other bodies."

## The general proposition

After both proofs, Carnot states the central theorem of the book in italics:

> **The motive power of heat is independent of the agents employed to realise it; its quantity is fixed solely by the temperatures of the bodies between which is effected, finally, the transfer of the caloric.**

This is the [[carnot-efficiency]] theorem in its pre-absolute-temperature form. It has two immediate corollaries:

1. When two gases undergo the same cycle between the same two reservoirs, they produce equal motive power and exchange equal quantities of caloric. (This is how Carnot derives universal gas properties.)
2. The question of the best working substance for a heat-engine is answered: all perfect engines are equally efficient; the choice of working substance is a matter of engineering practicality, not thermodynamic principle.

## The waterfall analogy formalised

The motive power of heat is "like a waterfall": it depends on the "height of the fall" (temperature difference) and the "quantity of the liquid" (quantity of caloric). For a waterfall, power is exactly proportional to height. For heat, Carnot suspects (but cannot prove with available data) that power is *not* simply proportional to temperature difference — the function $\mu(t)$ relating motive power to temperature requires experimental determination.

This is the point where the theoretical framework reaches its limit without empirical input. Carnot has established the *existence* and *universality* of a maximum efficiency function of temperature alone; determining its functional form is left to experiment. Lord Kelvin's paper later determines $\mu(t)$ from Regnault's steam data and shows it decreases with increasing temperature — more work per unit of heat at low temperatures than at high.
