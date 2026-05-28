---
title: "Calculation of neutron and X-ray scattering data from molecular dynamics simulations through optimal use of computation resources"
collection: talks
type: "Poster"
permalink: /talks/2022-poster-SNI
venue: "SNI"
date: 2022-09-05
location: "Berlin, Germany"
excerpt: "Topic: Implementation of parallel computing in Sassena"
---

Topic: Implementation of parallel computing in Sassena.

Authors
======
Arnab Majumdar, Martin Müller, and Sebastian Busch

Abstract
======
We address the computation of X-Ray and neutron scattering data from molecular dynamics simulations. Optimization of computation time is particularly crucial for large or long simulations. There are multiple software solutions available; we have chosen sassena for our work. Sassena inherits distributed memory parallelization (MPI) from its previous version. This work further augments vectorization and sharedmemory parallelization (OpenMP) into it and bolsters the computing speed of sassena by up to an order of magnitude. Furthermore, the introduction of shared memory parallelization introduces the possibility of doing hybrid parallelization. As a long-term goal, we aim to use the benefit of this optimization to validate the simulation of hydrogen storage materials with neutron scattering data.

[Link to conference website](https://www.helmholtz-berlin.de/media/media/spezial/events/2022/sni/downloads/sni2022-conference-book.pdf)
