# Hackerthon: an introduction to my project
This is the repository for attending the Hackerthon held by Taichi Graphics Company, all the source code will be made available after the competition.
## Title of the project
Taichi-based high performance 3D solid fracture phase field method finite element numerical implementation.
## Background of the project
The fracture phase field method is a widely used calculation theory of crack propagation, which has the characteristics of strong robustness, wide application range, and friendly numerical realization. It has attracted the attention of a large number of researchers in the field of fracture mechanics. In the analysis of solid fracture Show great potential. However, due to the high nonlinearity of the fracture phase field method, a large number of iterations are required in the numerical implementation to obtain accurate calculation results. Due to the high computational cost, most of the current numerical implementations of the phase field method are limited to two-dimensional models, and the crack growth in solids is rarely studied, which seriously hinders people's understanding of solid crack growth. Based on the Taichi language, this project will develop a numerical model of the 3D solid fracture phase field method based on GPU acceleration, realize the high-performance numerical realization of the 3D solid fracture phase field simulation on a small high-performance server, and further broaden the application of the fracture phase field method in computational mechanics. domain applicability.
# Preferred expectation:
Implementation of high-performance computing for numerical simulation of fracture phase field method on a small high-performance server.
# Strategy:
Develop a computing model based on the Taichi language and calibrate the model through the experimental comparison in the paper.
# Supplyment:
Open source code: FEMpy
Commercial finite element software: Abaqus (with user subroutine)
