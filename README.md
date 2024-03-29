# Circular Standing Waves Simulation

## Table of Contents
I. [Introduction](#introduction)  
II. [Model](#model)  
III. [Methods](#methods)  
IV. [Results](#results)  
    A. [Reproduction of Bohr Model Figure](#reproduction-of-bohr-model-figure)  
    B. [Traveling vs. Standing Waves on Circular Paths](#traveling-vs-standing-waves-on-circular-paths)  
    C. [Fitting/Comparison to Theoretical Expectation](#fitting-comparison-to-theoretical-expectation)  
    D. [Investigating Different Initial Conditions](#investigating-different-initial-conditions)  
V. [Conclusions](#conclusions)  

## Introduction
Understanding waves provides predictive insight into various physical systems. This project explores standing waves on circular paths, a topic crucial for explaining wave behavior in cavities or along strings and wires. The project aims to reproduce results from previous formulations and investigate different numerical methods' abilities to model standing waves.

## Model
The simulation utilizes the one-dimensional advection equation to model waves along a circular path. The advection equation resembles the wave equation and allows for the investigation of standing waves' behavior. 

## Methods
Two numerical methods, Lax and Lax-Wendroff, are employed to solve the advection equation. These methods are modifications of the finite difference method and are chosen for their suitability in solving partial differential equations.

## Results
### Reproduction of Bohr Model Figure
The simulation reproduces figures from previous formulations, showcasing solutions for different numbers of antinodes.

### Traveling vs. Standing Waves on Circular Paths
The project investigates the difference between waves traveling along a circle and standing waves. While partially reproducing standing wave behavior, challenges in reflecting antinodes across the path are noted.

### Fitting/Comparison to Theoretical Expectation
Numerical results are compared to analytical solutions using LMFIT. While the Lax-Wendroff method produces stable solutions, challenges arise in fitting decay behavior over time.

### Investigating Different Initial Conditions
Various initial conditions, including sine and Gaussian pulses, are explored. Results indicate the behavior of single waves and their interaction on the circular path.

## Conclusions
The project demonstrates the effectiveness of the Lax-Wendroff method in modeling standing waves on circular paths. While challenges in reproducing full wave behavior persist, valuable insights are gained for future improvements and alternative approaches.
