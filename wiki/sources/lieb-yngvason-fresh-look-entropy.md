---
title: "A Fresh Look at Entropy and the Second Law of Thermodynamics"
type: source
tags: [thermodynamics, entropy, second-law, axiomatic-thermodynamics, adiabatic-accessibility, statistical-mechanics, mathematical-physics]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

## Citation

Lieb, Elliott H., and Jakob Yngvason. "A Fresh Look at Entropy and the Second Law of Thermodynamics." arXiv:math-ph/0003028v1 (24 March 2000). Published in *Physics Today*, April 2000. Full technical treatment in: Lieb and Yngvason, *Physics Reports* 310, 1 (1999).

## Raw path

`raw/Thermodynamics/Papers/0003028v1.pdf`

## Summary

This accessible Physics Today-style article by Elliott Lieb and Jakob Yngvason presents their axiomatic derivation of [[entropy]] and the [[second-law-of-thermodynamics]] without recourse to statistical mechanics, heat engines, or the Carnot cycle. The central claim is that [[entropy]] exists and is unique (up to scale) as a consequence of a small number of simple properties of the relation of *adiabatic accessibility* between equilibrium states — the relation $X \prec Y$ meaning that state $Y$ can be reached from state $X$ by an adiabatic process (the gorilla and machinery may do anything, the only net external change being the raising or lowering of a weight) (source: 0003028v1.pdf). The authors show that $X \prec Y$ if and only if $S(X) \leq S(Y)$, and that [[entropy]] is additive over compound systems: $S(X, X') = S(X) + S(X')$. The result elevates the [[second-law-of-thermodynamics]] to a pillar of physics in its own right, independent of any microscopic model, responding to the sentiment expressed by Gibbs and Boltzmann that the second law is "merely" an expression of statistical mechanics.

## Key claims

- The second law can be formulated as the existence of an additive, unique [[entropy]] function $S$ on equilibrium states such that $X \prec Y \iff S(X) \leq S(Y)$; no appeal to heat engines, temperature, or atoms is needed (source: 0003028v1.pdf).
- Adiabatic accessibility satisfies simple axioms: reflexivity ($X \prec X$), transitivity, consistency with composition of states, consistency with scaling, the possibility of adiabatically splitting and recombining systems, and stability (small perturbations do not create new accessible states) (source: 0003028v1.pdf).
- The *comparison hypothesis* — that any two states $X$ and $Y$ of the same chemical composition are related by $X \prec Y$ or $Y \prec X$ — is the crucial extra ingredient; without it, an additive entropy may not exist, as shown by the counterexample of two incompressible solid bodies where neither $X \prec Y$ nor $Y \prec X$ (source: 0003028v1.pdf).
- Comparison can be *derived* (not merely postulated) for simple systems from: (i) the possibility of forming convex combinations of states (concavity of entropy), (ii) the existence of at least one irreversible adiabatic process from any state, and (iii) the zeroth law of thermodynamics, which underpins the additivity of entropy across systems (source: 0003028v1.pdf).
- Once the comparison hypothesis is established, entropy is constructively defined as $S(X) = \lambda_{\max}$ units, where $\lambda_{\max}$ is the maximal fraction of a reference high-entropy state $X_1$ that can be transformed adiabatically into $X$ with the aid of a complementary fraction of a reference low-entropy state $X_0$ (source: 0003028v1.pdf).
- Entropy is additive ($S(X, X') = S(X) + S(X')$) and extensive ($S(\lambda X) = \lambda S(X)$); these are non-trivial consequences of the axioms, not assumptions (source: 0003028v1.pdf).
- Temperature is not a primitive concept in this framework; it emerges as a derived quantity $1/T = (\partial S / \partial U)_V$, whose consistent definition depends on the prior existence of [[entropy]] (source: 0003028v1.pdf).
- The uniqueness of entropy implies that all methods of measuring or computing it — whether from quasistatic processes ($\Delta S = \int (dU + P\,dV)/T$) or from the axiomatic construction — must agree; entropy defined via slow reversible processes is therefore not a separate, weaker notion (source: 0003028v1.pdf).
- For mixing processes and chemical reactions, comparability cannot be guaranteed purely from first principles; however, empirical evidence supports the comparability of states with the same chemical composition in the real world (source: 0003028v1.pdf).

## Methods

The paper is a conceptual and mathematical exposition, intended as an accessible summary of the full technical treatment in Lieb and Yngvason, *Physics Reports* 310 (1999). The method is axiomatic: a preorder relation $\prec$ (adiabatic accessibility) is defined on the set of equilibrium states; necessary and sufficient conditions on $\prec$ for an additive entropy representation are identified and proved (in the companion paper). Key mathematical structures include order theory, convexity arguments, and entropy construction via a reference-state scaling formula analogous to the Laplace–Lavoisier measurement of heat by ice melting. No probability theory, statistical mechanics, or heat-engine efficiency arguments are employed.

## Limitations

- The framework is restricted to *equilibrium states*; non-equilibrium entropy and its increase are explicitly set aside as a separate (and unsatisfying) problem.
- The paper acknowledges that comparability for mixing and chemical reactions relies on empirical evidence rather than a priori derivation, leaving a gap in the full axiomatic programme.
- Figures from the *Physics Today* version are not available in the arXiv preprint (the authors note this explicitly).
- As a Physics Today summary, the article omits many proofs and technical details, which are only found in the *Physics Reports* companion paper; some claims in the summary paper are therefore not self-contained.
- The framework does not address the relationship between adiabatic accessibility and continuum mechanics or transport phenomena; this is the central objection raised in [[rudnyi-clausius-inequality-history]].

## Connections

- Provides a rigorous axiomatic foundation for [[entropy]] and the [[second-law-of-thermodynamics]], complementing and contrasting with the historical derivations discussed in [[planck-treatise-on-thermodynamics]], [[carnot-reflections-motive-power-of-heat]], and [[gibbs-elementary-principles-statistical-mechanics]].
- The derivation of temperature as a consequence of entropy, rather than a precondition, is a notable inversion of the usual textbook logic.
- The comparison hypothesis and the counterexample of incompressible solids clarify why [[reversible-cycle]]-based proofs require care about the existence of comparison.
- The zeroth law plays a structural role in ensuring consistent entropy units across systems; relevant to the zeroth-law discussion in [[rudnyi-clausius-inequality-history]].
- Critiqued by Rudnyi ([[rudnyi-clausius-inequality-history]]) on the grounds that the framework omits temperature fields and continuum mechanics, making it physically incomplete.
- The approach recovers the classical formulas ($\Delta S = \int dQ/T$) as consequences rather than definitions, consistent with but independent of the Clausius tradition.
- Einstein's endorsement of classical thermodynamics — "within the framework of the applicability of its basic concepts, it will never be overthrown" — is quoted as motivation (source: 0003028v1.pdf).

## Quotes

> "The question that the second law answers is this: What distinguishes those states $Y$ that can be reached from $X$ in this manner from those that cannot? The answer: There is a function of the equilibrium states, called entropy and denoted by $S$, that characterizes the possible pairs of equilibrium states $X$ and $Y$ by the inequality $S(X) \leq S(Y)$." (source: 0003028v1.pdf)

> "Temperature is eliminated as an a priori concept and appears in its natural place as a quantity derived from entropy and whose consistent definition really depends on the existence of entropy, rather than the other way around." (source: 0003028v1.pdf)

> "If the second law can be demystified, so much the better. If it can be seen to be a consequence of simple, plausible notions then, as Einstein said, it cannot be overthrown." (source: 0003028v1.pdf)
