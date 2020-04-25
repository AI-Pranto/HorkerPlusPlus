#HORKER++
![emblem](pics/horker.png)
###(High Order Reactor Kinetics and Evaluation of Reactivity, in C++)

This is a simple finite element program only requiring you to have [Eigen](eigen.tuxfamily.org) installed.
Arbitrary order Lagrange element meshes are automatically generated based on simple input files which
resemble commercial nuclear reactor simulation code, examples of which can be found in the examples
directory. HORKER++ is capable of both core eigenvalue and transient calculations, and currently has
no support for thermalhydraulic coupling. Paraview output (VTKU) is provided for each calculation.

This was written for an MIT 22.213 final project.

Licensed under GPL 3.