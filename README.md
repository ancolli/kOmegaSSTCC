# kOmegaSSTCC
OpenFOAM code for rotation/curvature correction for the komegaSST turbulence model.
This is based on the following: https://github.com/cvillescas/TkOmegaSSTCC. which unfortunately is incompatible with the standard distribution from OpenFoam Foundation. Furthermore, from version 3.0 the whole concept of turbulence
modelling was re-written and now is template based. It means that there is only one
formulation of turbulence model for both incompressible and compressible flow.
I have tested it in OpenFOAM 5.
This repository code is not part of the official OpenFOAM distribution.

The code was successfully implemented here: International Journal of Heat and Mass Transfer 137 (2019) 835-846 (https://www.sciencedirect.com/science/article/pii/S0017931019304508) doi: 10.1016/j.ijheatmasstransfer.2019.03.152
