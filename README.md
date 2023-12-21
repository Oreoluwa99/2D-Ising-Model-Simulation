# Ising Model Simulation and Visualization

This repository contains Python code for simulating and visualizing the 2D Ising model, a mathematical model in statistical mechanics that describes the behavior of magnetic spins in a lattice. The simulation is performed using the Metropolis algorithm, and the results include thermodynamic properties and visual snapshots of the evolving spin configurations.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

The Ising model is a fundamental concept in statistical mechanics, providing insights into phase transitions and collective behavior in physical systems. This repository offers a comprehensive set of Python scripts for simulating the Ising model and visualizing its dynamics.

## Features

### Simulation Code (`ising_simulation.py`)

- **Monte Carlo Simulation**: Implementation of the Metropolis algorithm for simulating the Ising model.
- **Thermodynamic Properties**: Calculation of thermodynamic properties, including energy, magnetization, specific heat, and susceptibility.
- **Temperature Range**: Adjustable temperature range for exploring the model's behavior.

### Visualization Code (`ising_visualization.py`)

- **Snapshot Visualization**: Generation of visual snapshots of the Ising model's spin configurations at specific time steps.
- **Temperature Parameterization**: Adjustable parameters for lattice size, equilibration steps, calculation steps, and temperature range.
- **Matplotlib Plots**: Utilization of Matplotlib for creating visualizations.

## Usage

1. Install the required dependencies (NumPy and Matplotlib).

```bash
pip install numpy matplotlib
