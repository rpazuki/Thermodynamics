---
title: "Part III, Chapter III — Second Law: General Deductions"
type: concept
tags: [second-law, carnot-efficiency, free-energy, helmholtz, berthelot-principle, spontaneity, absolute-temperature, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part III, Chapter III: The Second Law — General Deductions (§§137–152)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

With the entropy principle established, this chapter harvests its consequences. The main results are: the universal Carnot efficiency for *any* substance, conditions for the direction of spontaneous physical and chemical processes, the definition of Helmholtz free energy, Berthelot's principle and its limits, and the characteristic function $\Psi$ that unifies all equilibrium conditions. The chapter culminates in the general condition of thermodynamic equilibrium for isothermal and isobaric systems.

---

## 1. The Carnot Cycle for Any Substance (§137)

The entropy principle immediately generalises the Carnot efficiency from perfect gases (Part II, §90) to **any** working substance. For a reversible Carnot cycle between reservoirs at $\theta_1$ (cold) and $\theta_2$ (hot):

- **First Law:** $Q_1 + Q_2 + W = 0$, where $Q_2 > 0$ (absorbed from hot), $Q_1 < 0$ (rejected to cold), $W < 0$ (work done by the system).
- **Second Law (reversible process):** Entropy of the reservoirs changes by $-Q_1/\theta_1 - Q_2/\theta_2 = 0$, giving:

$$\frac{Q_1}{\theta_1} + \frac{Q_2}{\theta_2} = 0 \tag{65}$$

Combining with the First Law:

$$Q_1 : Q_2 : W = (-\theta_1) : \theta_2 : (\theta_1 - \theta_2) \tag{cf. 44}$$

The **Carnot efficiency** for any reversible engine is therefore:

$$\eta = \frac{W'}{Q_2} = \frac{\theta_2 - \theta_1}{\theta_2} = 1 - \frac{\theta_1}{\theta_2}$$

**For irreversible cycles** (§138): the entropy inequality $Q_1/\theta_1 + Q_2/\theta_2 < 0$ implies:

$$W' < \frac{\theta_2 - \theta_1}{\theta_1} Q_1'$$

The work obtained is *less* than in the reversible case. The reversible Carnot cycle delivers the **maximum work** for any cyclic process between two given temperatures. This is the fundamental limitation on heat engine efficiency.

---

## 2. Heat Conduction as an Irreversible Process (§138, end)

A special case: if no work is done ($W' = 0$), the heat flows spontaneously from the hotter to the colder reservoir. The entropy calculation gives $Q_2(1/\theta_2 - 1/\theta_1) < 0$, confirming heat flows from hot to cold — not the reverse. This shows that **heat conduction is irreversible**, consistent with the general entropy principle.

---

## 3. Direction of Natural Processes — The General Condition (§§139–140)

For any system at common temperature $\theta$ undergoing any infinitesimal physical or chemical change, the First and Second Laws give (§140):

$$dU - \theta\,d\Phi \leq W \tag{70}$$

where $W$ is external work done *on* the system. The equality holds for reversible processes.

This is the master inequality from which all subsequent equilibrium conditions are derived. It cannot be integrated in general, because the left side is not a perfect differential. To obtain integrated conditions, specific external constraints must be imposed.

---

## 4. Case I: Adiabatic Process (§141)

With $Q = 0$ (no heat exchange), equation (70) gives simply $d\Phi \geq 0$: entropy increases or remains constant. Already established; this is just the entropy principle restated.

---

## 5. Case II: Isothermal Processes and Helmholtz Free Energy (§§142–146)

At constant temperature $\theta$, equation (70) becomes:

$$d(U - \theta\Phi) \leq W$$

Define the **Helmholtz free energy**:

$$F \equiv U - \theta\Phi \tag{71}$$

For **reversible isothermal processes**: $dF = W$, and integrating: $F_2 - F_1 = \sum W$. The work extracted equals the *decrease* in free energy. The free energy is therefore the maximum work obtainable from an isothermal process, whether mechanical, electrical, or chemical.

For **irreversible isothermal processes**: $F_2 - F_1 < \sum W$ (less work gained, or more work required). The difference between maximum work and actual work is called the **lost work**.

When **no external work is done** ($W = 0$), as in most chemical reactions at constant temperature:

$$F_2 - F_1 \leq 0$$

Spontaneous processes at constant $T$ and $V$ decrease the free energy. Equilibrium is reached when $F$ is minimum.

**Berthelot's principle and its limits (§144):** Many thermochemists used the *heat effect* (decrease of $U$) rather than the decrease of $F$ as the driving force of reactions. This is Berthelot's principle: reactions occur so as to maximise the heat released. It is an approximation valid when the $\theta\Phi$ term is small compared to $U$ — i.e., at low temperatures and for condensed phases. But at high temperatures, or for gases and dilute solutions where entropy contributions are large, Berthelot's principle can fail: reactions with negative heat effects (endothermal) can still be spontaneous because the entropy gain ($d\Phi > 0$) outweighs the energy cost.

**Free energy of a perfect gas (§146):** Using $U = M(c_v\theta + \mathrm{const})$ and $\Phi = M(c_v\log\theta + \tfrac{R}{m}\log v + \mathrm{const})$:

$$F = M\left\{c_v\theta(\mathrm{const} - \log\theta) - \frac{R\theta}{m}\log v + \mathrm{const}\right\} \tag{74}$$

For an isothermal change: $dF = -p\,dV \leq W$, confirming the maximum-work result.

---

## 6. Case III: Isothermal and Isobaric Processes — The $\Psi$ Function (§§147–152)

For **constant temperature and pressure** (the most important case in chemistry and nature), Planck introduces the characteristic function:

$$\Psi \equiv \Phi - \frac{U + pV}{\theta} = -\frac{G}{\theta} \tag{75}$$

where $G = U + pV - \theta\Phi = H - \theta S$ is the **Gibbs free energy** (though Planck calls $-\theta\Psi$ the "Planckian potential"). The equilibrium condition (§148) for constant $T, p$ is:

$$\delta\Psi = 0 \tag{79}$$

and for irreversible spontaneous processes: $d\Psi > 0$ (equivalently, $G$ decreases spontaneously). This provides the most practically useful equilibrium condition, applicable to chemical reactions, phase equilibria, and dissolution.

A useful special case: the Gibbs–Helmholtz equation (§150), relating the temperature dependence of $G$ to $H$:

$$\frac{\partial (G/\theta)}{\partial \theta}\bigg|_p = -\frac{H}{\theta^2} \quad \Leftrightarrow \quad G = H + \theta\frac{\partial G}{\partial \theta}\bigg|_p$$

This relation is fundamental to the thermodynamics of chemical equilibrium (van't Hoff equation, to be derived in Part IV).

---

## Summary of Key Results

| Condition | Criterion | Physical meaning |
|-----------|-----------|-----------------|
| Isolated system | $d\Phi \geq 0$ | Entropy never decreases |
| Constant $T, V$ | $dF \leq 0$ | Free energy minimised at equilibrium |
| Constant $T, p$ | $d\Psi = 0$ (equiv. $dG \leq 0$) | Gibbs energy minimised at equilibrium |
| Reversible Carnot | $\eta = 1 - \theta_1/\theta_2$ | Maximum efficiency for any engine |
| Maximum work | $W'_{\max} = -(F_2 - F_1)$ | At constant $T$ |

The chapter transforms the abstract entropy principle into concrete, computable criteria for equilibrium and spontaneous change. These criteria — especially $\delta\Psi = 0$ — will drive the entire analysis of Part IV.

---

*[↑ Table of Contents](toc.md) · [← Back: Part III Ch.II — Second Law Proof](part-iii-ch-2-second-law-proof.md) · [Next: Part IV Ch.I — Homogeneous Systems →](part-iv-ch-1-homogeneous-systems.md)*
