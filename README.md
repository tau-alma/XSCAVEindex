# TAU XSCAVE Index
The index of TAU XSCAVE public codebase.

## [Physics-informed Data-driven Modeling of Rock Motion Dynamics in Excavation](https://github.com/tau-alma/simpat2025-rock-motion)

This repository contains the code and simulation framework for the paper:

**"Physics-informed data-driven modeling of rock motion dynamics in excavation using a high-fidelity simulator"**  
*Mohammad Heravi, Amirmasoud Molaei, Reza Ghabcheloo*  
*Simulation Modelling Practice and Theory, Volume 145, 2025*  
[DOI: 10.1016/j.simpat.2025.103208](https://doi.org/10.1016/j.simpat.2025.103208) | [Paper PDF](https://heravi.dev/papers/1-s2.0-S1569190X25001431-main.pdf)

### Overview

This project implements a physics-informed, data-driven framework for predicting the motion of large rocks during excavation. The framework uses the **Algoryx high-fidelity simulator** to generate training data and employs physics-informed neural networks (PINNs) to learn predictive models of rock dynamics. The approach addresses the complex interactions among excavator bucket, rock, and soil that are not effectively captured using analytical models.

### Key Features

- High-fidelity excavation simulation using Algoryx simulator
- Physics-informed neural network (PINN) implementation with kinematic constraints
- Support for multiple excavation scenarios with varying soil and rock properties
- Data collection and post-processing pipeline for 200+ experiments
- Comprehensive visualization and analysis tools
