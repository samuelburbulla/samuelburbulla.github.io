---
title: "Physics-informed neural networks for transformed geometries and manifolds"
collection: publications
permalink: /publication/2023c-physics-informed-neural-networks-for
excerpt: 'We propose physics-informed neural networks for transformed geometries and manifolds.'
date: 2023-11-27
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2311.15940'
citation: 'Samuel Burbulla (2023) Physics-informed neural networks for transformed geometries and manifolds. arXiv:2311.15940'
---
Physics-informed neural networks (PINNs) effectively embed physical principles
into machine learning, but often struggle with complex or alternating
geometries. We propose a novel method for integrating geometric transformations
within PINNs to robustly accommodate geometric variations. Our method
incorporates a diffeomorphism as a mapping of a reference domain and adapts the
derivative computation of the physics-informed loss function. This generalizes
the applicability of PINNs not only to smoothly deformed domains, but also to
lower-dimensional manifolds and allows for direct shape optimization while
training the network. We demonstrate the effectivity of our approach on several
problems: (i) Eikonal equation on Archimedean spiral, (ii) Poisson problem on
surface manifold, (iii) Incompressible Stokes flow in deformed tube, and (iv)
Shape optimization with Laplace operator. Through these examples, we demonstrate
the enhanced flexibility over traditional PINNs, especially under geometric
variations. The proposed framework presents an outlook for training deep neural
operators over parametrized geometries, paving the way for advanced modeling
with PDEs on complex geometries in science and engineering.