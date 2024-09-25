# Thermal Dendrite and Solid-Liquid Interface Simulation Notebooks

This repository contains Jupyter notebooks used to simulate dendritic growth and solid-liquid interface dynamics. These simulations model the thermal and structural evolution of systems relevant to material science, particularly for studying dendrite formation in solidification processes and solid-liquid interfaces. The notebooks are organized into two main categories: **Thermal Dendrite** and **Solid-Liquid Interface**.

## Repository Structure

- **dendrite/**: Contains notebooks related to thermal dendrite simulations.
  - `ThermalDendrite_2D_0.ipynb`
  - `ThermalDendrite_2D_1.ipynb`
  - `ThermalDendrite_2D_2.ipynb`

- **interface/**: Contains notebooks focused on solid-liquid interface dynamics.
  - `SLInterface_1D_0.ipynb`
  - `SLInterface_1D_1.ipynb`

## Requirements

Ensure that you have the following libraries installed to run the notebooks:

- Python 3.x
- NumPy
- Matplotlib
- SciPy

You can install the necessary packages using the following command: 
`pip install numpy matplotlib scipy`

## Thermal Dendrite Simulations

The notebooks in the `dendrite/` folder simulate 2D thermal dendrite growth, a common phenomenon in material solidification processes. The simulations model heat flow and the growth morphology of dendrites under specific initial conditions.

### Files:
- **ThermalDendrite_2D_0.ipynb**  
  This notebook sets up the basic simulation environment for 2D dendritic growth, defining the temperature fields and initiating the dendrite seed.

- **ThermalDendrite_2D_1.ipynb**  
  Builds upon the initial conditions, adding more complex boundary conditions and refining the simulation's spatial grid to capture finer details of dendrite arm growth.

- **ThermalDendrite_2D_2.ipynb**  
  Finalizes the simulation by implementing advanced cooling profiles, allowing the user to explore the impact of different temperature gradients on dendrite morphology.

## Solid-Liquid Interface Simulations

The `interface/` folder contains simulations focused on 1D solid-liquid interface dynamics. These simulations investigate how the solidification front evolves over time and the influence of thermal gradients at the interface.

### Files:
- **SLInterface_1D_0.ipynb**  
  This notebook models the initial setup of a 1D solid-liquid interface with a constant temperature gradient. The focus is on calculating the position of the interface over time.

- **SLInterface_1D_1.ipynb**  
  Extends the initial simulation by introducing variations in the thermal conductivity and latent heat, providing insights into how these factors influence the solidification rate and the interface's stability.

## Running the Simulations

To run a notebook, follow these steps:

1. **Clone this repository**:
   `git clone https://github.com/PhaseFieldTutorial/`

2. **Navigate to the folder containing the notebooks**:
   `cd dendrite/   # or cd interface/`

3. **Launch the Jupyter notebook**:
   `jupyter notebook`

4. **Open the desired notebook (e.g., ThermalDendrite_2D_0.ipynb) and run the cells sequentially to execute the simulation.**

## Results

The output of each simulation includes:

- **Temperature fields**: Visualizing the temperature distribution across the simulation domain.
- **Dendrite/Interface Growth**: Dynamic plots showing the evolution of dendritic arms or the solid-liquid interface.
- **Time Evolution**: Data on the growth rate of dendrites or the speed of the solidification front as a function of time.

