---
permalink: /about/
title: About LightDock
---

LightDock is a protein-protein, protein-peptide and protein-DNA docking framework based on the [Glowworm Swarm Optimization](https://link.springer.com/article/10.1007/s11721-008-0021-5) (GSO) algorithm.

**The framework is written in the Python programming language (version >=3.6) and Rust (2021 edition) for selected high computation-intensive parts of the framework.**

The LightDock framework is highly versatile, with many options that can be further developed and optimized by the users:

* Accepts any user-defined scoring function, including custom ones.
* Backbone flexibility can be enabled/disabled for receptor and ligand molecules in an independent way.
* Can use local gradient-free minimization.
* The simulation can be restrained from the beginning to focus on user-assigned interacting regions, for example, transmembrane domains or highly-variable loops in antibody-antigen systems.
* [Residue restraints in both receptor and ligand partners](https://doi.org/10.1093/bioinformatics/btz642).
* Integrative approaches such as [membrane docking](https://www.nature.com/articles/s41467-020-20076-5) using coarse-grained information.
* Protein-protein, protein-peptide and protein-DNA support.
* Shared-memory (`multiprocessing`) and distributed-memory (`MPI`).
* Simulation step is [embarrassingly parallel](https://en.wikipedia.org/wiki/Embarrassingly_parallel) by design and scales very well to the number of CPU cores in [HPC](https://en.wikipedia.org/wiki/High-performance_computing) architectures.

## License
LightDock is available under [GPLv3 License](https://github.com/lightdock/lightdock/blob/master/LICENSE). If you have any doubt, please don't hesitate to contact us at <lightdocking@gmail.com>.

## With the support of:

<p align="center">
    <a href="https://bioexcel.eu/" target="_blank"><img src="../assets/images/bioexcel_logo.png"></a>
    <br>
    <a href="https://www.eosc-hub.eu/" target="_blank"><img src="../assets/images/eosc_hub_logo.png"></a>
    <br>
    <a href="https://sbgrid.org/" target="_blank"><img src="../assets/images/sbgrid_logo.png"></a>
    <br>
    <a href="https://zymvol.com" target="_blank"><img src="../assets/images/zymvol_logo.jpg"></a>
</p>


## Logo
Please use the following image in PNG format (transparent background):

<p align="center">
    <img src="../assets/images/lightdock_logo.png">
</p>

