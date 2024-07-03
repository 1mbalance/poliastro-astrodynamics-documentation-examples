# Poliastro Astrodynamics Documentation Examples

This repository contains Jupyter notebooks of some examples from the official Poliastro documentation, demonstrating various functionalities and applications for astrodynamics. These notebooks are designed to provide comprehensive, hands-on tutorials for users interested in performing orbital mechanics computations with Poliastro.

## Contents

1. **CatchThatAsteroid.ipynb**
   - This notebook showcases an example of tracking and intercepting an asteroid. It demonstrates the process of defining the asteroid's orbit, planning an intercept mission, and visualizing the trajectory.

2. **LambertArc0and1.ipynb**
   - This notebook provides a detailed example of solving Lambert's problem for two different scenarios. Lambert's problem is crucial for mission planning, allowing for the determination of orbits that connect two points in space within a given time frame.

3. **ParkerSolarFlybys.ipynb**
   - This notebook illustrates the trajectory design for the Parker Solar Probe, focusing on its flybys around Venus to gradually decrease its perihelion and achieve closer approaches to the Sun. It includes the calculation of orbital maneuvers and visualization of the resulting trajectories.

4. **TheAtmosphereAndItsLayers.ipynb**
   - This notebook explores the properties of the Earth's atmosphere at various altitudes. Using the COESA-76 atmospheric model, it computes and plots temperature, pressure, and density as functions of altitude, providing insights into atmospheric dynamics.

## Getting Started

You can install the necessary packages using pip:

```bash
pip install poliastro numpy matplotlib astropy
