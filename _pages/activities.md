---
permalink: /research/
title: ""
toc: true
---

# Current activities
My ongoing works are focused on developing robust methods and implementations for mesh adaptation in computational mechanics, particularly on parallel computing environments.

## Development of the parallel mesh adaptation library _ParMmg_
[ParMmg](https://github.com/MmgTools/ParMmg){:target="_blank"} is an open source library for parallel mesh adaptation on top of the [Mmg](https://github.com/MmgTools/Mmg){:target="_blank"} remesher.

Written in C with MPI, version-controlled with git and tested with Jenkins, it is designed to meet the academic and industrial needs of the [Mmg platform](https://www.mmgtools.org){:target="_blank"} and the [ExaQUte](http://exaqute.eu){:target="_blank"} European research project.
It targets three-dimensional unstructured meshes and parallel adaptation is performed by iteratively remeshing each partition (except on the parallel interfaces) and migrating the parallel interfaces.

<img src="/assets/images/n1g8_my_mark_pre-P00-00_cut.png" width="300">
<img src="/assets/images/n1g8_my_mark_post-P00-00_cut.png" width="300">

Details on the algorithm can be found in:
- The conference paper (2021) [Parallel unstructured mesh adaptation based on iterative remeshing and repartitioning](https://hal.inria.fr/hal-03208569/document){:target="_blank"}
- The research report (2018) [Parallel unstructured mesh adaptation using iterative remeshing and repartitioning](https://hal.inria.fr/hal-02386837/document){:target="_blank"}

## Development of the constant-connectivity mesh adaptation library _Fmg_
_Fmg_ is a library to perform constant-connectivity mesh adaptation (r-adaptation) in two and three dimensions for fluid mechanics simulations with moving fronts (like shock waves, free surface waves). R-adaptation can be particulary useful in conjunction with Arbitrary-Lagrangian Eulerian formulations of fluid flows, to ease the enforcement of conservation of flow quantities from the old to the adapted mesh.

<img src="/assets/images/sortie4_cut_res500.png" width="300">
<img src="/assets/images/sortie14_cut_res500.png" width="300">

Details on the algorithm can be found in:
- The journal paper (2021) [Adaptive deformation of 3D unstructured meshes with curved body fitted boundaries with application to unsteady compressible flows](https://hal.inria.fr/hal-03194100/document){:target="_blank"}
- The conference paper (2019) [R-adaptation for unsteady compressible flow simulations in three dimensions](https://hal.inria.fr/hal-02284746/document){:target="_blank"}

# Past activities

## Interpolation-free mesh adaptation for three-dimensional unsteady aeroelastic simulations
Study of transonic flutter phenomena with unsteady mesh adaptation, through the Mmg library coupled to a Fortran 2003 solver for compressible flow simulations, using an interpolation-free approach allowing the conservation of flow quantities over adaptive meshes.

Detailed descriptions can be found in:
- My Ph.D. thesis (2018) [Conservative interpolation-free mesh adaptation for three-dimensional aeroelastic simulations in unsteady compressible flows](https://www.politesi.polimi.it/handle/10589/142548){:target="_blank"}
- The conference paper (2018) [Numerical simulation of nonclassical aileron buzz over 3D unstructured adaptive meshes](https://re.public.polimi.it/retrieve/handle/11311/1057445/295441/CIRRL01-18.pdf){:target="_blank"}

## Generalized beam models for aeroelastic morphing analysis
Analysis and development of a reduced-order structural model for the aeroelastic design of morphing helicopter blades.

Detailed descriptions can be found in:
- My Ph.D. thesis (2018) [Conservative interpolation-free mesh adaptation for three-dimensional aeroelastic simulations in unsteady compressible flows](https://www.politesi.polimi.it/handle/10589/142548){:target="_blank"}
- The conference proceeding (2018) [Generalized beam models analysis for aeroelastic morphing applications](https://re.public.polimi.it/retrieve/handle/11311/1057446/295443/CIRRL02-18.pdf){:target="_blank"}

## Older activities
More activities in the [CV](/cv).
