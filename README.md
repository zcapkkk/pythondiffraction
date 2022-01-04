# Python Diffraction Simulator

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/zcapkkk/pythondiffraction/HEAD?urlpath=voila%2Frender%2FPropagation_Notebook.ipynb)

This is Python code written to simulate the diffraction and interference of light. Clicking the binder button leads to a web host of the notebook, which is a GUI which the user can adjust various parameters to perform different interference effects.

## Introduction

Diffraction is a phenomenon which occurs when waves passes through a barrier. It was used to demonstrate the wavelike nature of light, and as such remains a fundamental topic in the study of optics. This also has further applications in Quantum Mechanics and Photonics, and as such is one of the most important topics in Physics. Diffraction effects are often unexpected and beautiful. They can be counterintuitive, and may be hard to visualize for people who approach it for the first time. Commonly, such effects are demonstrated with apparatus such as a diffraction grating or purpose-built double slit, which may be quite hard to acquire for most. As such, this simulation is created to bridge the gap between theory and visualization, and help learners of this topic gain a better understanding of how light diffracts around different obstacles. 

## Background

During my time at the State Key Laboratory of the Terahertz and Millimeter Waves at City University of Hong Kong, I have written MATLAB code to perform the propagation of Terahertz waves. I have noticed that such a program can also be used to demonstrate diffraction effects such as the famous double slit phenomenon. While MATLAB allows for creating a GUI app easily, it does not allow for an independent hosting of the app (unless you pay for the license), and requiring an installation of an independent application to run a simulation might be too cumbersome for many. Furthermore, there are approximations which cannot be applied at Terahertz regime but have to be used in the Terahertz regime. As such, modifications to the program has to be made. I have opted to rewrite the code in Python, and host the simulation on the web so it can be accessed more easily. 

## Functions

Currently, users can pick between a four different types of 'obstacles' for light to propagate through. Each obstacle would have parameters which can be adjusted to produce different diffraction effects. They are:
- Double Slit
- Single Slit
- Circular Obstacle
- Circular Hole
- Ring hole 
