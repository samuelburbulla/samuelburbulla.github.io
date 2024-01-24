---
title: "A finite-volume moving-mesh method for two-phase flow in dynamically fracturing porous media"
collection: publications
permalink: /publication/2022a-a-finite-volume-moving-mesh-method
date: 2022-06-01
venue: 'Journal of Computational Physics'
paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0021999122000936'
citation: 'Samuel Burbulla, Christian Rohde (2022) A finite-volume moving-mesh method for two-phase flow in dynamically fracturing porous media.
Journal of Computational Physics, Volume 458, 2022, 111031.'
---
Multiphase flow in fractured porous media can be described by discrete fracture
matrix models that represent the fractures as dimensionally reduced manifolds
embedded in the bulk porous medium. Generalizing earlier work on this approach
we focus on immiscible two-phase flow in time-dependent fracture geometries,
i.e., the fracture itself and the aperture of the fractures might evolve in
time. For dynamic fracture geometries of that kind, neglecting capillary forces,
we deduce by transversal averaging of a full dimensional description a
dimensionally reduced model that governs the geometric evolution and the flow
dynamics. The core computational contribution is a mixed-dimensional
finite-volume discretization based on a conforming moving-mesh ansatz. This
finite-volume moving-mesh (FVMM) algorithm is tracking the fractures' motions as
a family of unions of facets of the mesh. Notably, the method permits arbitrary
movement of facets of the triangulation while keeping the mass conservation
constraint. In a series of numerical examples we investigate the modeling error
of the reduced model as it compares to the original full dimensional model.
Moreover, we show the performance of the finite-volume moving-mesh algorithm for
the complex wave pattern that is induced by the interaction of saturation fronts
and evolving fractures.