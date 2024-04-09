### What is this repository for? ###
The Virtual Blade Model (VBM) has been proven to be one of the most efficient and accurate models for wind and tidal turbine analysis. This feature has been added to the ANSYS FLUENT software since 2006, but is limited to only 10 turbines. The end goal of the current project is to enable ANSYS FLUENT to accommodate any number of turbines and increase its applicability to technical problems.

### How do I get set up? ###
1. Setup Model/s:
According to the physics of the flow field user will select required model/s to simulate the flow.
2. Setup Working Fluid/s & Solid/s:
User will define the physical and thermodynamical properties of the working fluid/s and solid/s in the problem.
3. Setup Boundary & Zone Conditions:
Solving the governing equations of the flow (i.e. system of partial differential equations) requires well-defined boundary conditions within the CFD domain. These conditions are selected and defined in this step.
4. Setup Solution Methods:
In CFD simulations the governing equations of the flow are solve numerically. Based on the physics of the problem appropriate numerical schemes and solution methods are selected at this step.

For more information and step by step guide go to following link:
http://nbviewer.jupyter.org/github/sfo-project/3D-flow-over-WindTidal-turbine-VBM-turbulent/blob/master/Fluent/Simulation.ipynb

### Who do I talk to? ###
The audiences of this repository are the researchers and the engineers of energy sector; especially, in the fields of tidal and wind energies.

# How to cite:
If you use this code, please cite the following paper:
Radfar, S.; Kianoush, B.; Majidi Nezhad, M.; Neshat, M. Developing an Extended Virtual Blade Model for Efficient Numerical Modeling of Wind and Tidal Farms. Sustainability 2022, 14, 13886. https://doi.org/10.3390/su142113886
