---
title: "Ch. I — General Notions: The Principle of Conservation of Extension-in-Phase"
type: concept
tags: [statistical-mechanics, phase-space, liouville-theorem, hamiltonian-mechanics, ensemble, density-in-phase, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter I: General Notions — The Principle of Conservation of Extension-in-Phase

## Overview

Chapter I lays the entire mathematical foundation of the book. Gibbs begins with Hamilton's equations of motion and then introduces the central conceptual innovation of the treatise: the *ensemble* — a vast, imagined collection of independent mechanical systems that are identical in nature but differ in their initial conditions (phases). Statistical mechanics is, for Gibbs, the study of such ensembles.

## Hamiltonian Mechanics and Phase Space

Gibbs works with a system of $n$ degrees of freedom described by generalised coordinates $q_1, \dots, q_n$ and their conjugate momenta $p_1, \dots, p_n$, where each momentum is defined from the kinetic energy $\varepsilon_p$ by

$$p_i = \frac{\partial \varepsilon_p}{\partial \dot{q}_i}.$$

Hamilton's equations take the form

$$\dot{q}_i = \frac{\partial \varepsilon}{\partial p_i}, \qquad \dot{p}_i = -\frac{\partial \varepsilon}{\partial q_i},$$

where $\varepsilon = \varepsilon_p + \varepsilon_q$ is the total energy. The key advantage of using momenta rather than velocities as independent variables is that the equations acquire their remarkable symmetry and simplicity — a point Gibbs emphasises at the outset.

The *phase* of a system is its complete specification by all $2n$ values $(p_1, \dots, p_n, q_1, \dots, q_n)$. The space of all possible phases — a $2n$-dimensional continuum — is called *phase space*.

## The Ensemble and Density-in-Phase

Rather than tracking a single system's trajectory through phase space, Gibbs imagines a *great number of independent systems* distributed continuously across phase space. If the number of systems whose phase falls in an infinitesimal $2n$-dimensional volume element $dp_1 \cdots dq_n$ is

$$D\, dp_1 \cdots dp_n\, dq_1 \cdots dq_n,$$

then $D$ is the *density-in-phase*. The product $dp_1 \cdots dq_n$ is called an *element of extension-in-phase*. When the density $D$ does not change with time, Gibbs calls the ensemble in *statistical equilibrium*.

## The Principle of Conservation of Extension-in-Phase (Liouville's Theorem)

The centrepiece of Chapter I is what Gibbs calls the *conservation of extension-in-phase*. He proves that as the ensemble of systems evolves under Hamilton's equations, the total phase-space volume occupied by any group of systems is invariant in time:

$$\int dp_1 \cdots dq_n = \text{constant},$$

where the integral is over the same group of systems at different times. Equivalently, the Jacobian determinant of the transformation mapping an initial phase to the phase at time $t$ equals unity:

$$\frac{d(p_1, \dots, q_n)}{d(p_1', \dots, q_n')} = 1.$$

The proof proceeds by showing that the time derivative of this Jacobian is zero — a consequence of Hamilton's equations implying $\sum_i (\partial \dot{p}_i/\partial p_i + \partial \dot{q}_i/\partial q_i) = 0$.

A key corollary is that the density-in-phase $D$ is conserved along any trajectory of the ensemble:

$$\frac{dD}{dt} = 0 \quad \text{(following the motion)}.$$

This is now universally known as Liouville's theorem.

## Statistical Equilibrium and the Index of Probability

Gibbs rewrites the density in terms of the *index of probability* $\eta = \log(D/N)$ where $N$ is the total number of systems. The coefficient of probability is $P = D/N = e^\eta$. The conservation law becomes

$$\frac{d\eta}{dt} = 0$$

along trajectories, meaning that the index of probability of any moving system does not change. Statistical equilibrium — the time-independence of the ensemble's phase distribution — is achieved when $\eta$ (equivalently $D$) is a function only of conserved quantities, most importantly the energy $\varepsilon$.

## Physical Significance

Chapter I establishes that the framework of [[ensemble]] averages is not merely a calculational convenience but is dictated by the structure of Hamiltonian mechanics itself. Liouville's theorem ensures that phase-space volume is an invariant measure, which makes probability in phase space a well-defined and consistent concept. All subsequent chapters build on this: the canonical and microcanonical distributions (Chapters IV and X) are specific choices of the function $D = D(\varepsilon)$, justified by their special properties.

The extension-in-phase has the dimensions of $(action)^n$, a fact that foreshadows the later quantum-mechanical insight (Planck's constant $h$ as the natural unit of phase-space volume, though Gibbs does not reach this conclusion).
