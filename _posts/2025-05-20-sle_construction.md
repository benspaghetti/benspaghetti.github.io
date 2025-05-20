---
layout: post
title: "Construction of the Schramm-Loewner Evolution: A Review"
date: 2025-05-20
categories: maths
tags: probability, sle
math: true
---

I first learned about the theory of Schramm-Loewner Evolutions (SLE) after learning about the conjectured conformal invariance of two-dimensional critical percolation through the article [Percolation: Slipping through the Cracks](https://www.ams.org/publicoutreach/feature-column/fcarc-percolation). This phenomenon on the triangular lattice has been proven by Stanislav Smirnov, which won him the Fields Medal. Now, more than a year later, I am finally learning the rudiments of $\mathsf{SLE}$ theory.

Classical Loewner theory was developed purely for geometric function theoretic purposes: to resolve the Bieberbach Conjecture (now de Branges' Theorem). The chordal Loewner theory on the upper half-plane was a very general one. Essentially any type of model which scales to a curve of local growth (in particular, this requires it to be continuous and non-self-crossing) can be described by Loewner theory. This observation is slightly disappointing, as SLE turned out to be a less special object than I had imagined. The conformal invariance part? This direct from definition! These were my initial thoughts. But as I thought a bit more, I realised that this is not entirely correct: the $\mathsf{SLE}$ is quite special, but perhaps still not as special as I thought.

First, the non-self-crossing property is quite strong, which is why the simple random walk does not scale to a $\mathsf{SLE}$ but models of non-self-intersecting paths potentially do. For example, the loop-erased random walk ($\mathsf{SLE}_2$) and the self avoiding walk ($\mathsf{SLE}_{\frac{8}{3}}$) are two such models. 

Another special feature of $\mathsf{SLE}$ stems from using the Brownian motion as its driving function. From my understanding of Loewner theory (which is miniscule), driving functions are not really supposed to look like a particle oscillating on the real line. Perhaps geometric function theorists think this is an abomination. I have no idea. But although some of these models are clearly related to the simple random walk, as far as I know, there was no obvious way to precisely state their relationships to the Brownian motion. Well, the $\mathsf{SLE}$ did provide that. The phase transitions caused by adjusting the diffusivity $\kappa$ are also indeed a sight to behold.

It is also nice that all the $\kappa$'s are so neat, although I don't have any understanding of this since this is related to the specific proofs of the models scaling to the $\mathsf{SLE}$.

Still, the $\mathsf{SLE}$ is not an all powerful object. The theory's largest limitation is in its adoption of the Loewner theory to describe curves, which is restricted to two dimensions. But then I am not sure how possible a generalise to higher dimensions, especially in view of the implications to conformal field theory (which I know nothing about, but isn't two dimensions the most well-studied?).

An additional issue lies in the extreme difficulty to prove convergence of these models to the $\mathsf{SLE}$. For example, Smirnov's proof relies on special properties of the triangular lattice (I didn't look at the proof myself, but I heard this personally from a very well respected researcher), and universality suggests that conformal invariance does still hold for other lattices, but I don't see any progress on that front. 

Anyway full disclosure I haven't actually read Schramm's original paper titled 'Scaling limits of loop-erased random walks and uniform spanning trees'. So this whole post is hot garbage. Whatever.