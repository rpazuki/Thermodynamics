---
title: "The Mathematics of the Second Law of Thermodynamics"
type: source
tags: [second-law-of-thermodynamics, entropy, adiabatic-accessibility, axiomatic-thermodynamics, mathematical-physics, lieb-yngvason, comparison-hypothesis]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

## Citation

Lieb, Elliott H. and Yngvason, Jakob. "The Mathematics of the Second Law of Thermodynamics." In: *Visions in Mathematics: GAFA 2000 Special Volume, Part I*, eds. N. Alon, J. Bourgain, A. Connes, M. Gromov, V. Milman. Birkhäuser/Springer Basel, 2010 (reprint of 2000 edition), pp. 334–358. Originally published in *Geometric and Functional Analysis* (GAFA), Special Volume (2000), pp. 334–358. DOI: 10.1007/978-3-0346-0422-2.

## Raw path

`raw/Thermodynamics/Papers/978-3-0346-0422-2.pdf` (ch. "The Mathematics of the Second Law of Thermodynamics," pp. 334–358 of the volume, PDF pages 349–374)

## Summary

This chapter — an invited contribution to the GAFA 2000 "Visions in Mathematics" conference proceedings — is largely a reproduction of the authors' *AMS Notices* summary of their landmark 1999 paper "A Guide to Entropy and the Second Law of Thermodynamics" (Lieb and Yngvason, *J. Stat. Phys.* 98, 1999), with an added section on open problems. Lieb and Yngvason set out to derive the [[entropy]] principle of the [[second-law-of-thermodynamics]] — that there exists a real-valued function $S$ on equilibrium states such that an adiabatic process $X \to Y$ is possible if and only if $S(X) \leq S(Y)$ — from a minimal set of physically motivated axioms, without appealing to Carnot cycles, ideal gases, temperature, heat, or statistical mechanics. The key primitive relation is *adiabatic accessibility* ($X \prec Y$: state $Y$ is reachable from $X$ by an adiabatic process involving only a weight that may rise or fall), which defines a preorder on state spaces. The central mathematical achievement is deriving the "Comparison Hypothesis" (CH) — that any two states of the same system are comparable under $\prec$ — from more primitive axioms, rather than postulating it as in earlier axiomatic approaches. Once CH is established, the existence and essential uniqueness (up to affine transformation) of an additive, extensive entropy function follows by a construction reminiscent of the Laplace–Lavoisier ice-calorimetry definition of heat. Temperature emerges at the end, defined as $T = (\partial S / \partial U)^{-1}$, and is shown to be positive and to characterise thermal equilibrium.

## Key claims

- The second law is essentially a theorem about orderings on sets: the existence of an entropy function $S$ such that $X \prec Y \Leftrightarrow S(X) \leq S(Y)$ is equivalent to a set of six axioms (reflexivity, transitivity, consistency, scaling invariance, splitting/recombination, stability) together with the Comparison Hypothesis (source: 978-3-0346-0422-2.pdf, ch. Lieb-Yngvason).
- The definition of adiabatic accessibility deliberately avoids the concepts of "heat," "hot," "cold," and "temperature"; it requires only that $Y$ be reachable from $X$ by an interaction with an auxiliary device (which returns to its initial state) plus a weight that may rise or fall — a formulation in the spirit of Planck (source: 978-3-0346-0422-2.pdf).
- The Comparison Hypothesis (CH) — that all pairs of states in a state space are comparable — is *derived* rather than postulated; this distinguishes the Lieb–Yngvason approach from earlier axiomatic treatments by Giles and Buchdahl, which take CH as an axiom (source: 978-3-0346-0422-2.pdf).
- For simple systems (state spaces embeddable as open convex subsets of $\mathbb{R}^n$ with energy $U$ and work coordinates $V$), forward sectors $A(X) = \{Y : X \prec Y\}$ are convex and nested (Theorem on forward sectors), which immediately yields CH for simple systems (source: 978-3-0346-0422-2.pdf).
- CH for compound systems is derived using thermal contact (Zeroth Law) and five further axioms (thermal contact, thermal splitting, Zeroth Law transitivity, transversality, universal temperature range); no reference to temperature is needed until the very end (source: 978-3-0346-0422-2.pdf).
- The entropy function is explicitly constructed: fixing two reference states $X_0 \prec\!\prec X_1$, define $S(X) = \sup\{t \geq 0 : ((1-t)X_0, tX_1) \prec X\}$ — an analogue of the Laplace–Lavoisier calorimetry definition (source: 978-3-0346-0422-2.pdf).
- Additivity of entropy ($S(X,Y) = S(X) + S(Y)$) is a non-trivial theorem, not an assumption; it encodes the fact that compound systems can undergo adiabatic processes not possible for either subsystem alone (source: 978-3-0346-0422-2.pdf).
- Temperature is positive by convention (the energy increases in adiabatic processes at fixed work coordinates), and thermal equilibrium of two systems is characterised by equality of temperature as so defined (source: 978-3-0346-0422-2.pdf).
- The statistical-mechanical formula $S = -\sum p \ln p$ is explicitly declared *irrelevant* to the thermodynamic second law; the authors are concerned with thermodynamic entropy, not information-theoretic entropy (source: 978-3-0346-0422-2.pdf).

## Methods

The paper is a work of rigorous mathematical physics. The core methodology is axiomatic: a preorder relation (adiabatic accessibility) is given on abstract state spaces, six axioms are stated, and theorems are proved from them using real analysis, convex geometry, and order theory. The proof of CH uses Lipschitz continuity of tangent planes to forward sectors, connectedness arguments, and an analysis of thermal contact. The construction of the entropy function is explicit and elementary. The paper cites and engages critically with earlier axiomatic approaches: Carathéodory (1909), Giles (1964), Buchdahl (1966), Cooper (1967), Duistermaat (1968), and Roberts–Luce (1968).

## Limitations

- The framework is restricted to classical equilibrium thermodynamics; non-equilibrium processes, quantum thermodynamics, and systems with long-range interactions (e.g. gravity, stars) are excluded.
- The axioms for "simple systems" (convex state space, Lipschitz tangent planes, connected boundary of forward sectors) involve differentiability assumptions that may be restrictive for systems near phase transitions.
- Mixing and chemical reactions (the "mixing entropy" problem and Gibbs paradox) require additional axioms that are discussed briefly but not fully resolved; the authors acknowledge this as an open problem.
- The treatment of systems with multiple phases or with non-extensive behaviour (e.g. small systems, systems with surface effects) is not covered.
- The chapter is a summary; full proofs are in the companion paper Lieb & Yngvason, *J. Stat. Phys.* 98 (1999), and a shorter preprint also exists in the vault (`0003028v1.pdf`).

## Connections

- This is the definitive modern axiomatic treatment of [[second-law-of-thermodynamics]] and [[entropy]]; it supersedes and synthesises the Carathéodory tradition.
- The adiabatic-accessibility preorder relates directly to the classical [[reversible-cycle]] concept; the irreversible case ($X \prec\!\prec Y$, i.e. $S(X) < S(Y)$) is the strict second law.
- Compare with the historical derivations surveyed in [[brush-kinetic-theory-randomness-irreversibility]], which show that the probabilistic H-theorem approach is independent of (and complementary to) the axiomatic thermodynamic approach.
- The phenomenological [[entropy]] definition via $dS = \delta Q_{\rm rev}/T$ (as in [[devriendt-basics-of-thermodynamics]]) is a special case that follows from the Lieb–Yngvason framework once temperature is defined.
- [[planck-treatise-on-thermodynamics]] is cited as an antecedent for the definition of adiabatic accessibility avoiding heat/temperature.
- [[gibbs-elementary-principles-statistical-mechanics]] is explicitly distinguished: Gibbs's statistical entropy is a different quantity.

## Quotes

> "The essence of the second law is the 'entropy principle,' which states that adiabatic processes can be quantified by an entropy function on the space of all equilibrium states whose increase is a necessary and sufficient condition for such a process to occur. It is one of the few really fundamental physical laws (in the sense that no deviation, however tiny, is permitted) and its consequences are far reaching. Since the entropy principle is independent of models — statistical mechanical or otherwise — it ought to be derivable from a few logical principles without recourse to Carnot cycles, ideal gases, and other assumptions about such things as 'heat,' 'hot,' and 'cold,' 'temperature,' 'reversible processes,' etc." (source: 978-3-0346-0422-2.pdf, abstract)

> "The answer, as we perceive it, is that the law is really an interesting mathematical theorem about orderings on sets with profound physical implications. The axioms that constitute this ordering are somewhat peculiar from the mathematical point of view and might not arise in the ordinary ruminations of abstract thought. They are special but important, and they are driven by considerations about the world, which is what makes them so interesting." (source: 978-3-0346-0422-2.pdf, p. 351)

> "The additivity of entropy in compound systems is often just taken for granted, but it is one of the startling conclusions of thermodynamics. [...] The fact that the inequality $S(X) + S(X') \leq S(Y) + S(Y')$ tells us exactly which adiabatic processes are allowed in the compound system among comparable states, independent of any detailed knowledge of the manner in which the two systems interact, is astonishing and is at the heart of thermodynamics." (source: 978-3-0346-0422-2.pdf, p. 357)
