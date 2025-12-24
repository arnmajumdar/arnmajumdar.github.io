---
title: "Sassena -- a tool for validation of Molecular Dynamics simulations with neutron and X-Ray scattering experiments"
collection: talks
type: "Talk"
permalink: /talks/2023-talk-MLZ-Grainau
venue: "5th internal biannual science meeting of the MLZ"
date: 2023-06-21
location: "Grainau, Germany"
---

Topic: Demonstration of computer simulation usage for analysis of neutron scattering data.

Authors
======
Arnab Majumdar, Martin Müller, and Sebastian Busch

Abstract
======
Neutron and X-ray scattering experiments are powerful techniques to investigate any material at the atomic to mesoscopic level. They give us structural and dynamic information. However, it is not possible to extract the relative position, shape, and velocity of the scatterers directly from the scattering data due to the phase problem. One possibility to circumvent this problem is to simulate the materials at different length scales and to calculate scattering patterns from these simulations.
To cover the several orders of magnitude in reciprocal space accessible by scattering techniques, a high-performance software solution is required to deal with large systems at fine resolution. For this task, several programs are available; we have chosen Sassena for our work. Sassena inherits distributed memory parallelization (MPI) from its previous version. We augmented this by vectorization and shared memory parallelization (OpenMP) to bolster the computing speed; gains of up to an order of magnitude were achieved. Furthermore, the introduction of shared memory parallelization introduces the possibility of hybrid parallelization.

Additionally, we also added a new feature in the program that allows the removal of the coherent scattering signal caused by the finite size of the simulation box.

[Link to conference website](https://indico.frm2.tum.de/event/389/contributions/4271/)
