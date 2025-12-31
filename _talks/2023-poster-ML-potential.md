---
title: "Sassena - tool for computation of scattering pattern from MD simulation"
collection: talks
type: "Poster"
permalink: /talks/2023-poster-ML-potential
venue: "Machine Learning Interatomic Potentials: Theory and Practice"
date: 2023-11-06
location: "Helsinki, Finland"
---

Topic: Demonstration of Sassena as a tool to calculate scattering patterns from MD simulations

Authors
======
Arnab Majumdar, Martin Müller, and Sebastian Busch

Abstract
======
Scattering experiments and Molecular Dynamics (MD) simulations have been complementary techniques for the investigation of materials at the Angstrom length scale. This work proposes a tool named Sassena [1] for the direct computation of scattering patterns from Molecular Dynamics (MD) simulations. Sassena can calculate the scattering functions for spectroscopy, wide angle diffraction, and small angle diffraction measurements. Additionally, it can also calculate the elastic part of a spectroscopic pattern, i.e. Elastic Incoherent/ coherent Structure Factor (EISF/ ECSF). The original version of Sassena was developed by ORNL [2-3] and it was equipped with MPI and threading. We added vectorization and OpenMP to bolster the speed even further. A finite-size effect in the small angle region was observed. We implemented a new solution, which is an improvement in comparison to the previous solution within the original version of Sassena. The capabilities of Sassena are described with various
examples.

References:<br>
[1] Sassena repository, url: https://codebase.helmholtz.cloud/DAPHNE4NFDI/sassena<br>
[2] Lindner et al., doi: 10.1016/j.cpc.2012.02.010<br>
[3] Lindner, url: https://trace.tennessee.edu/utk_graddiss/1589/

[Link to conference website](https://www.cecam.org/workshop-details/machine-learning-interatomic-potentials-theory-and-practice-1213)
