---
title: "Part III, Chapter II — Second Law: Proof"
type: concept
tags: [second-law, entropy, proof, perfect-gas, irreversibility, perpetual-motion, clausius, planck]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Part III, Chapter II: The Second Law — Proof (§§116–136)

*Source: [[planck-treatise-on-thermodynamics]]*

---

## Overview

This is the mathematical heart of the book. Planck derives the **entropy theorem** — that the entropy of an isolated system of perfect gases never decreases — from a single empirical axiom: the impossibility of perpetual motion of the second kind. The proof is constructive and logically tight, proceeding step by step from the axiom through specific irreversible processes to the general principle, and then generalising beyond perfect gases via the Carnot cycle.

---

## 1. The Fundamental Axiom (§116)

Planck's chosen starting point for the proof of the Second Law is:

> *It is impossible to construct an engine which will work in a complete cycle, and produce no effect except the raising of a weight and the cooling of a heat-reservoir.*

Such an engine — called **perpetual motion of the second kind** (§116, following Ostwald's terminology) — would not violate the First Law (it draws energy from the heat reservoir), but it would allow unlimited work to be extracted from any heat source (the sea, the atmosphere) at no cost. Planck notes that this axiom "coincides fundamentally" with the starting points used by Clausius, Thomson (Kelvin), and Maxwell, each expressed in a different form.

---

## 2. From the Axiom to Specific Irreversibilities (§§117–118)

Two important irreversibilities follow directly:

**Irreversibility of frictional heat generation (§117):** If friction heat generation *could* be reversed, the reversal process would produce work from a heat reservoir — perpetual motion of the second kind. Hence friction heat generation is irreversible.

**Irreversibility of free gas expansion (§118):** If free expansion (constant energy, no work or heat) could be reversed, one could: let the gas expand doing work while absorbing heat from a reservoir, then reverse the expansion for free — again perpetual motion of the second kind. Hence free expansion is irreversible.

This second result is the key that unlocks the entropy proof for perfect gases.

---

## 3. Definition of Entropy for a Perfect Gas (§§119–120)

For an infinitesimal reversible change of a perfect gas per unit mass:

$$q = c_v\,d\theta + \frac{R}{m}\cdot\frac{\theta}{v}\,dv$$

Divide by $\theta$:

$$\frac{q}{\theta} = c_v\,\frac{d\theta}{\theta} + \frac{R}{m}\,\frac{dv}{v} = d\phi$$

The right side is a perfect differential. Integrating, the **specific entropy** of the gas is defined (§119):

$$\phi = c_v\log\theta + \frac{R}{m}\log v + \mathrm{const} \tag{51}$$

and the total entropy of mass $M$ is $\Phi = M\phi$. Key properties:
- In a **reversible adiabatic** process ($q = 0$): $d\phi = 0$, so $\Phi$ is constant.
- In **any reversible process** where heat $Q$ is absorbed at temperature $\theta$: $d\Phi = Q/\theta$ (§120).
- $d\Phi = (dU + p\,dV)/\theta$ holds as an identity (it is just the definition of $\Phi$), regardless of how the state change is brought about.

---

## 4. Entropy Conservation in Reversible Processes of Two Gases (§§121–123)

Consider two gases that exchange heat reversibly while isolated from the outside world. At each instant, $d\Phi_1 = Q_1/\theta$ and $d\Phi_2 = Q_2/\theta$, with $Q_1 + Q_2 = 0$ (heat from one goes to the other). Therefore:

$$d\Phi_1 + d\Phi_2 = 0 \implies \Phi_1 + \Phi_2 = \mathrm{const} \tag{54}$$

The total entropy is conserved in any reversible process with no external effects. This is extended to $n$ gases in §123, giving the proposition:

> *If a system of $n$ gases has the same entropy in two states, it can be transformed from one to the other by a reversible process, without leaving changes in other bodies.*

This is the sufficient condition for reversibility. The entropy is equal in both states if and only if:

$$\sum_{i=1}^n \Phi_i = \sum_{i=1}^n \Phi_i' \tag{56}$$

---

## 5. Entropy Increase in Irreversible Processes (§§124–126)

The irreversibility of free gas expansion (§118) now provides the crucial step. In free expansion, $\Phi$ increases (volume increases at constant temperature → $\log v$ increases in equation (51)). Therefore:

> *There exists in nature no means of diminishing the entropy of a system of perfect gases, without leaving changes in bodies outside the system.* (§125)

The proof is by contradiction: if one could decrease the total entropy of a gas system without external changes, one could use that method to completely reverse the free expansion, which has been proved impossible.

Combining the results of §§123–125, Planck arrives at the **general entropy principle** (§126):

$$\boxed{d\Phi_{\mathrm{total}} \geq 0}$$

> *If a system of perfect gases passes in any way from one state to another, with no changes remaining in surrounding bodies, the entropy of the system is not smaller, but equal to or greater than that of the initial state.*

- **Equality** holds for **reversible** processes.
- **Inequality** holds for **irreversible** processes.
- **Equality is both necessary and sufficient** for complete reversibility with no external changes.

---

## 6. Generalisation Beyond Perfect Gases (§§128–136)

The proof so far applies only to perfect gases. Planck generalises it in two steps:

**Step 1 — Reversible processes with any substance:** For a substance that undergoes any reversible process (not necessarily a perfect gas), the entropy can be defined as the integral $\int Q/\theta$ along any reversible path between the two states (§128):

$$\Phi_2 - \Phi_1 = \int_1^2 \frac{Q_{\mathrm{rev}}}{\theta} \tag{62}$$

This integral is path-independent (a consequence of the Second Law and the perfect-gas entropy theorem applied to auxiliary gas systems).

**Step 2 — Any irreversible process:** If a system undergoes an irreversible process resulting in a change of entropy $d\Phi_{\mathrm{system}}$, then the total entropy change of system plus surroundings satisfies:

$$d\Phi_{\mathrm{system}} + d\Phi_{\mathrm{surroundings}} \geq 0$$

Since $d\Phi_{\mathrm{surroundings}} = -Q/\theta$ (heat given to surroundings), this becomes:

$$d\Phi_{\mathrm{system}} \geq \frac{Q}{\theta}$$

with equality for reversible processes. This is the **Clausius inequality** in its general form.

---

## 7. Summary of the Proof Structure

```
Axiom: Perpetual motion of the 2nd kind is impossible
  ↓
Friction heat generation is irreversible (§117)
Free gas expansion is irreversible (§118)
  ↓
Entropy defined for perfect gas: Φ = M(cv log θ + R/m log v + const)
  ↓
Reversible processes conserve total entropy (§§121-123)
Free expansion increases entropy (§124)
Entropy cannot decrease without external changes (§125)
  ↓
General principle: dΦ ≥ 0 for isolated systems (§126)
  ↓
Generalization to any substance via reversible Carnot analysis (§§128-136)
```

---

## Conceptual Significance

Planck's proof is one of the most rigorous presentations of the Second Law in classical thermodynamics literature. The essential logical move is to tie the general entropy theorem to *one specific irreversible process* (free gas expansion, whose irreversibility follows from the axiom), prove the entropy theorem for that process, and then show by a general argument that the entropy of any gas system cannot decrease. The extension to non-gas substances uses the established perfect-gas result plus the consistency of thermodynamic temperature across substances (an independent proof using the Carnot cycle). No molecular hypotheses are needed anywhere.

---

*[↑ Table of Contents](toc.md) · [← Back: Part III Ch.I — Second Law Introduction](part-iii-ch-1-second-law-introduction.md) · [Next: Part III Ch.III — Second Law Deductions →](part-iii-ch-3-second-law-deductions.md)*
