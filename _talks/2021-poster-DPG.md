---
title: "Conversion of Molecular Dynamics (MD) simulations to Neutronand X-Ray Scattering Data using High Performance Computing"
collection: talks
type: "Poster"
permalink: /talks/2022-poster-DPG
venue: "Deutsche Physikalische Gesellschaft (DPG)"
date: 2021-09-15
location: "online"
excerpt: "Topic: Implementation of parallel computing in Sassena"
---

Topic: Implementation of parallel computing in Sassena.

Authors
======
Arnab Majumdar, Martin Müller, and Sebastian Busch

Abstract
======
Sassena is one of the software solutions to convert molecular dynamics (MD) simulations into elastic and quasi-/inelastic neutron and X-ray scattering curves. Current work makes an effort to introduce different strategies of parallel computing into sassena. Parallel computing can be a huge leap in the journey of reducing the computing time within sassena. It consists of different strategies like distributed memory parallelization(MPI), shared memory parallelization (OpenMP) and vectorization. Sassena inherits distributed memory parallelization from its previous version. This work further augments vectorization and shared memory parallelization into it. Through vectorization, this work bolsters the computing speed of sassena to a new height of up to an order of magnitude faster than its previous version. On the other hand, shared memory parallelization introduces a possibility of doing hybrid parallelization within sassena. Furthermore, this work plans to benefit from the achieved performance gain by validating simulations of hydrogen storage materials with neutron scattering data.

[Link to conference website](https://www.dpg-verhandlungen.de/year/2021/conference/skm/part/akpik/session/3/contribution/4)
