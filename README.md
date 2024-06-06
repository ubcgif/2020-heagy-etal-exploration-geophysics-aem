# Open-source software for simulations and inversions of airborne electromagnetic data

_Lindsey J. Heagy, Seogi Kang, Rowan Cockett and Douglas W. Oldenburg_

https://doi.org/10.1080/08123985.2019.1583538

![magnetic flux](./paper/thumbnail.png)

## Summary

Inversions of airborne EM data are often an iterative process, not only requiring that the researcher be able to explore the impact of changing components such as the choice of regularization functional or model parameterization, but also often requiring that forward simulations be run and fields and fluxes visualized in order to build an understanding of the physical processes governing what we observe in the data. In the hope of facilitating this exploration and promoting reproducibility of geophysical simulations and inversions, we have developed the open source software package, SimPEG. The software has been designed to be modular and extensible with the goal of allowing researchers to interrogate all of the components and to facilitate the exploration of new inversion strategies. We present an overview of the software in its application to airborne EM and demonstrate its use for visualizing fields and fluxes in a forward simulation as well as its flexibility in formulating and solving the inverse problem. We invert a line of airborne TDEM data over a conductive vertical plate using a 1D voxel-inversion, a 2D voxel inversion and a parametric inversion, where all of the forward modelling is done on a 3D grid. The results in this paper can be reproduced  by using the provided Jupyter notebooks. The Python software can also be modified to allow users to experiment with parameters and explore the physics of the electromagnetics and intricacies of inversion.
 

## Citation

Heagy, L. J., Kang, S., Cockett, R., & Oldenburg, D. W. (2019). Open-source software for simulations and inversions of airborne electromagnetic data. Exploration Geophysics, 51(1), 38–44. https://doi.org/10.1080/08123985.2019.1583538

```
@article{heagy_open_2020,
         author = {Lindsey J. Heagy, Seogi Kang, Rowan Cockett and Douglas W. Oldenburg},
         title = {Open-source software for simulations and inversions of airborne electromagnetic data},
         journal = {Exploration Geophysics},
         volume = {51},
         number = {1},
         pages = {38--44},
         year = {2020},
         publisher = {Taylor \& Francis},
         doi = {10.1080/08123985.2019.1583538},
         URL = {https://doi.org/10.1080/08123985.2019.1583538}  
}

```
