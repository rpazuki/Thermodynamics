---
title: "Ch. IX — The Function φ and the Canonical Distribution"
type: concept
tags: [statistical-mechanics, density-of-states, canonical-distribution, most-probable-energy, entropy, gibbs]
created: 2026-05-16
updated: 2026-05-16
sources: 1
---

# Chapter IX: The Function $\phi$ and the Canonical Distribution

## Overview

Chapter IX investigates the relationship between the density-of-states function $\phi$ (introduced in Chapter VIII) and the canonical distribution, especially for systems with many degrees of freedom. The central result is that for $n > 2$, both the most probable energy and the average value of $d\phi/d\varepsilon$ in a canonical ensemble equal $1/\Theta$ — establishing the connection between the microcanonical temperature and the canonical modulus.

## The Most Probable Energy

In a canonical ensemble the density-in-energy (number of systems per unit energy interval) is proportional to

$$e^{(\psi - \varepsilon)/\Theta + \phi}.$$

This must vanish at $\varepsilon = 0$ (when $e^\phi = 0$ for $n > 2$) and at $\varepsilon = \infty$. Since it is positive in between, it must have a maximum, the *most probable energy* $\varepsilon_0$, determined by

$$\frac{d\phi}{d\varepsilon}\bigg|_{\varepsilon_0} = \frac{1}{\Theta}.$$

This equation is the microcanonical temperature definition: the inverse of the density-of-states derivative equals the modulus. It means the most probable energy in a canonical ensemble coincides with the energy at which the microcanonical system has the same temperature $\Theta$.

## Average of $d\phi/d\varepsilon$ Equals $1/\Theta$

For $n > 2$, Gibbs proves (by integration by parts) that the ensemble average

$$\overline{\frac{d\phi}{d\varepsilon}} = \frac{1}{\Theta}.$$

Combined with the result about the most probable energy, this shows that the most probable value and the average value of $d\phi/d\varepsilon$ coincide — both equal $1/\Theta$. This is a strong form of the equivalence between canonical and microcanonical ensembles for large systems.

## Variation of $\psi$ with External Coordinates

When the external coordinates $a_i$ vary, differentiating the partition function gives

$$\frac{\overline{d\phi}}{da_i} = \frac{\bar{A}_i}{\Theta},$$

where $\bar{A}_i$ is the average generalised force. This allows the differential of $\bar{\eta}$ to be written as

$$-d\bar{\eta} = \frac{d\phi}{d\varepsilon}\, d\bar{\varepsilon} + \sum_i \frac{d\phi}{da_i}\, da_i + \cdots,$$

which mirrors the exact identity $d\phi = (d\phi/d\varepsilon)\, d\varepsilon + \sum_i (d\phi/da_i)\, da_i$ but with averages. For large $n$ the fluctuations of $d\phi/d\varepsilon$ and $d\phi/da_i$ around their mean values become negligible, so the two expressions become interchangeable — canonical averages and microcanonical values approach each other.

## Gaussian Distribution of Energy for Large $n$

For large $n$, the density-in-energy $e^{(\psi - \varepsilon)/\Theta + \phi}$ becomes sharply peaked around $\varepsilon_0$. Expanding $\phi$ to second order around $\varepsilon_0$ shows that the energy distribution is approximately Gaussian with variance $\Theta^2/(d^2\phi/d\varepsilon^2)_0 \sim \Theta^2 \cdot 2/n$ — confirming the fluctuation formula of Chapter VII and showing that the width of the energy distribution grows as $\sqrt{n}$ while the mean grows as $n$, making the relative width shrink as $1/\sqrt{n}$.

## Significance

Chapter IX is the bridge between the canonical ensemble (controlled by $\Theta$) and the microcanonical ensemble (controlled by $\varepsilon$). It proves they are equivalent for large $n$ and provides the precise sense in which the density-of-states function $\phi$ encodes the microcanonical entropy and temperature. The equation $d\phi/d\varepsilon = 1/\Theta$ at the most probable energy is the statistical-mechanical derivation of $\partial S / \partial E = 1/T$ from first principles.
