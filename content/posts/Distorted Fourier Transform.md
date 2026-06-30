---
title: "Distorted Fourier Transform"
date: 2026-06-29T16:30:00+08:00
draft: false
---

We want to talk about distorted Fourier Transform (dFT) in this post. This somehow can be considered as a review of the tools which are paricularly useful nowadays in PDEs, especially in the zero-energy resonance phenomenon of some Schordinger equations. 

The results mainly come from "On th 1d Cubic NLS with a Non-generic Potential" by Gong Chen and Fabio Pusateri. 

The basis of dFT includes Jost functions and basic spectral theory. The Jost functions $\psi_+\left(x,k\right)$ and $\psi_-\left(x,k\right)$ are defined as solutions to $$H\psi_{\pm}\left(x,k\right)=\left(-\partial_{xx}+V\right)\psi_{\pm}\left(x,k\right)=k^2\psi_{\pm}\left(x,k\right)$$ such that $$\lim_{x\rightarrow +\infty}\left|\text{e}^{-\text{i}kx}\psi_{+}\left(x,k\right)-1\right|=0, \quad \lim_{x\rightarrow -\infty}\left|\text{e}^{\text{i}kx}\psi_{-}\left(x,k\right)-1\right|=0. $$

We let $m_{\pm}\left(x,k\right)=\text{e}^{\mp\text{i}kx}\psi_{\pm}\left(x,k\right)$. It is well known that for fixed $x$, $m_{\pm}$ is analytic in $k$ for $\mathscr{I}k>0$ and is continuous up to $\mathscr{I}k\ge0$. 

We define $$\mathscr{W}^{s}_{+}\left(x\right)=\int^{\infty}_{x}\left<y\right>^s\left|V(y)\right|\text{d}y, \quad \mathscr{W}^{s}_{-}\left(x\right)=\int^x_{-\infty}\left<y\right>^s\left|V(y)\right|\text{d}y. $$ If we know that $V$ decays fast enough, $\mathscr{W}^{s}_{\pm}$ also decays as $x\rightarrow \pm \infty$ respectively. 