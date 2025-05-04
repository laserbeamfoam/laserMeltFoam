# laserMeltFoam

## Overview

**laserMeltFoam** solver ported to OpenFOAM v2412

Original solver can be found at the following [link](https://github.com/thaman1602/PBFSolvers/tree/main/OpenFOAM/thermofluid/solvers)

![](example_sim.gif)

## Installation 

The solver can be installed using OpenFOAM v2412 by first compiling the following libraries:

* geometricVof
* transportModels
* turbulenceModels

and then compiling the **laserMeltFoam** solver itself.

**setSolidFraction** utility can be compiled separately if needed. 
