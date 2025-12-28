# laminar_BL_OpenFOAM
This is a Laminar Boundary Layer using OpenFOAM's icoFoam solver.

The boundary conditions in the U file are ...

We have zeroGradient on top and bottom of the entrance region.
We have constant velocity on left side of the entrance region.
We have zeroGradient on top of the flat plate region and the right side.
We have noSlip condition on bottom of the flat plate region.

For the future, we want to add turbulent modelling as well... Let's see how we can do it (in another repository)
