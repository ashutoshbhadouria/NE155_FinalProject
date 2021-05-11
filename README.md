# NE155_FinalProject

This repository is created for NE155 Final Project Assignment. The goal of the project is to create a solver for steady state 2D neutron diffusion equation that has vacuum boundaries on the bottom and left faces and reflecting boundaries on the top and right boundaries. The project uses Finite Volume Method to discretize the equations for a mesh grid. 

The project files are divided into 3 parts:

iterative_solvers.ipynb: This file contains iterative solvers for Ax=b linear systems. It has three algortims: Jacobi, SOR and gauss sedidel

2Dsolver.ipynb: This file contains algorithm that solves the discretized Finite Volume equations. It uses the iterative solvers to obtain solutions for fluxes in cell

2Dtests.ipynb: This file is a demo that contains visualizations as a way to validate and test the code

References: A. Mitra, Jiang Z., Duderstadt J and Hamilton, Professor R. Slaybaugh  

