---
title: "Development of a bidirectional data-code-publication pipeline with change tracking to enable reproducible research"
collection: talks
type: "Talk"
permalink: /talks/2026-talk-snib-2
venue: "German conference on Research with Synchrotron Radiation, Neutrons, Ions and Accelerators at Large-Scale Facilities"
date: 2026-09-09
location: "Hamburg"
---

Topic: Reproducible workflow.

Authors
======
Arnab Majumdar, and Sebastian Busch

Abstract
======
Reproducibility remains a central challenge in computational and experimental research, where published results often depend on complex software pipelines, undocumented environments, and fragile data workflows [1]. This work presents a practical workflow for creating fully reproducible research articles using showyourwork [2], an open-source framework that treats a manuscript as an executable research object. Figures, tables, and results can be generated directly from raw data through scripted pipelines orchestrated by Snakemake and compiled automatically into a publication-ready document. By packaging data, code, and computational environments together, showyourwork ensures that every output in the paper can be regenerated from scratch on any machine. Integrated continuous integration and deployment via GitHub supports robust development, long-term preservation, and transparent peer review. The framework also enables seamless integration with Overleaf, fostering collaborative writing while preserving full computational reproducibility.

References:<br>
[1] Peng et al., DOI: https://doi.org/10.1146/annurev-publhealth-012420-105110<br>
[2] Luger et al., URL: https://arxiv.org/abs/2110.06271<br>

[Link to conference website](https://indico.desy.de/event/51551/contributions/208198/)
