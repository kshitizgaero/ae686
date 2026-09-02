# Numerical Analysis of Helicopter Blade Element/Momentum Theory (BEMT)

**Course:** AE686 – Helicopter Theory
**Supervisor:** Prof. Abhishek, Helicopter and VTOL Lab, Department of Aerospace Engineering, IIT Kanpur
**Type:** Group Project
**Duration:** Jan 2026 – Apr 2026

## Overview

This project implements a numerical Blade Element Momentum Theory (BEMT) analysis for a helicopter rotor in hover, using Gaussian quadrature for accurate spanwise integration and Prandtl's tip-loss correction to capture rotor tip effects.

## Objectives

- Build a numerical BEMT solver in MATLAB for a rotor in hover
- Evaluate rotor aerodynamic loading (thrust and torque distribution) along the blade span
- Incorporate tip-loss effects to improve prediction accuracy near the blade tip

## Methodology

### 1. Numerical Implementation
- Implemented a MATLAB program using six-point Gaussian quadrature to numerically integrate BEMT equations along the blade span
- Discretized the rotor blade into elements and evaluated reference pitch inputs for hovering flight

### 2. Aerodynamic Analysis
- Analyzed local pitch angle, angle of attack, and induced inflow at each blade element
- Computed thrust distribution and torque variation along the blade span

### 3. Tip-Loss Correction
- Incorporated Prandtl's tip-loss function into the BEMT formulation
- Used the corrected results to reveal and characterize rotor dynamic effects near the blade tip

## Key Results

| Aspect | Result |
|---|---|
| Integration method | Six-point Gaussian quadrature |
| Flight condition | Hover, reference pitch inputs |
| Outputs computed | Pitch angle, angle of attack, induced inflow, thrust distribution, torque variation |
| Tip-loss model | Prandtl's tip-loss function |

## Tools Used
- MATLAB (numerical BEMT solver, Gaussian quadrature integration)

## Repository Structure


## Author
Kshitiz Gupta — MS (Research), Department of Aerospace Engineering, IIT Kanpur
