---
title: "Ch. III — Application of Conservation of Extension-in-Phase to Integration of Equations of Motion"
type: concept
tags: [statistical-mechanics, hamiltonian-mechanics, integration, phase-space, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter III: Application of Conservation of Extension-in-Phase to the Integration of the Differential Equations of Motion

## Overview

Chapter III is the most technically specialised of the early chapters, credited explicitly to Boltzmann's 1871 work on the Jacobi last-multiplier. It shows how the conservation of extension-in-phase provides a systematic method for integrating Hamilton's equations of motion — reducing the problem progressively until only quadratures remain.

## The Integration Programme

Gibbs uses unified notation: write $r_1, \dots, r_{2n}$ for all coordinates and momenta together, and $a, \dots, h$ for the $2n$ arbitrary constants of the integral equations of motion. From Chapter I, the Jacobian determinant satisfies

$$\frac{d(r_1, \dots, r_{2n})}{d(a, \dots, h)} = \text{function of } (a, \dots, h) \text{ alone}.$$

This is the Liouville invariant rewritten as a constraint on the relationship between phase-space positions and constants of integration.

## Reduction by Quadratures

When forces depend only on coordinates (not on time), one can eliminate $dt$ from the equations of motion to obtain $2n-1$ equations in $r_1, \dots, r_{2n}$ alone. These introduce $2n-1$ constants $b, \dots, h$. The final constant $a$ enters as an additive time-translation constant.

The conservation of extension-in-phase provides a "last multiplier" for the remaining integration. Specifically, once $2n-2$ first integrals $c, \dots, h$ are known, the next integral $b$ can be found by

$$db' = \frac{\dot{r}_2}{\dfrac{d(c, \dots, h)}{d(r_3, \dots, r_{2n})}}\, dr_1 - \frac{\dot{r}_1}{\dfrac{d(c, \dots, h)}{d(r_3, \dots, r_{2n})}}\, dr_2,$$

which is guaranteed to be an exact differential by the conservation law, and is therefore integrable by quadrature. The final integration to find $a$ (time) is likewise a quadrature.

## Significance

The practical utility of this chapter is that it turns the conservation of phase-space volume from a mathematical identity into an algorithmic tool. Knowing the Liouville invariant tells you that certain combinations of the remaining unknowns must be exact differentials — which dramatically reduces the work of integration.

Gibbs acknowledges that the result is closely related to Jacobi's principle of the last multiplier, and that Boltzmann had recognised its connection to the behaviour of multi-atomic gas molecules. The chapter is largely self-contained; readers primarily interested in thermodynamic applications can proceed directly to Chapter IV without loss of continuity. Its importance lies in establishing that the [[ensemble]] framework has deep roots in classical analytic mechanics, not just statistical reasoning.
