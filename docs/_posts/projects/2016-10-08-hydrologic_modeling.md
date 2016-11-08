---
layout: project
title:  "Hydrologic Modeling"
ref: SUMMA
date:   2016-08-03 16:55:00
categories:
- projects
img: hydrologic_modeling.jpg
img2: summa.png
factsheet1: comingsoon.pdf
factsheet2: summa_factsheet_2016_10.pdf
thumb: summa.jpg
sponsors: National Science Foundation, U.S. Army Corps of Engineers, Bureau of Reclamation, NOAA, NASA (check)
teamline1: "NCAR: Martyn Clark (PI), Grey Nearing, Andy Newman, Naoki Mizukami, Nans Addor, Andy Wood, Ethan Gutmann"
teamline2: "University of Washington: Bart Nijssen, Jessica Lundquist, Michael Ou"
teamline3: "U.S. Army Corps of Engineers: Jeff Arnold"
teamline4: "Bureau of Reclamation: Levi Brekke"
contacts: "Contact: Martyn Clark - mclark@ucar.edu | Julie Vano – jvano@ucar.edu"
modellink: SUMMA
tags: [projects]
---

# Improving Hydrologic Modeling for Climate Impact Assessments

#### **The challenge:** 

Management decisions about our nation’s water resources are made against a backdrop of uncertainty. Uncertainty about water supply and demand affects both short-range operational decisions and long-range planning. Risk-based operations and planning methods require realistic descriptions of uncertainty, yet an important source of uncertainty that has so far been neglected in climate impact assessments originates with hydrologic models. Hydrologic models can produce a wide range of predictions for the same events, even when forced with identical meteorology.

#### **Facing this challenge:**

Scientists and engineers in RAL's Hydrometeorological Applications Program at the National Center for Atmospheric Research are collaborating with the U.S. Army Corps of Engineers, the Bureau of Reclamation, and the University of Washington to develop a unified hydrologic modeling approach, SUMMA (the Structure for Unifying Multiple Modeling Alternatives), that is built on a common set of governing equations and a common numerical solver. The SUMMA framework can be used to systematically characterize hydrologic model uncertainty through exploring modeling decisions with controlled manipulations of model configurations and parameters. The resulting, large ensembles reveal the underlying model uncertainty and thus improve the probabilistic characterization of risk. By using a common modeling core, the overhead associated with the creation of large model ensembles is significantly reduced, which is a major departure from current “small ensemble” methods. SUMMA source code and test cases are freely available at https://www.ral.ucar.edu/projects/summa.

#### **Scientific advances:**

*   *Process flexibility.* SUMMA explicitly simulates dominant biophysical and hydrologic processes, from treetops to bedrock, and from the ridgetop to the stream, providing multiple options for how individual processes are simulated. SUMMA also allows for extensive flexibility to experiment with different model parameter values.

*   *Spatial flexibility.* SUMMA includes capabilities to easily experiment with different representations of spatial variability and hydrologic connectivity, including different spatial resolutions, different spatial configurations (e.g., grids and hydrologic response units), and different representations of how water moves laterally.

*   *Numerical flexibility.* To generalize approaches from multiple models, SUMMA separates the representation of physical processes from the numerical solution. This simplifies incorporating different modeling approaches, and, importantly, enables experimenting with different numerical solvers.

#### **Moving Forward:** 

*   Current work is focused on increasing the technical readiness level of SUMMA, to support large-ensemble continental-domain model applications.

*   SUMMA is being rigorously tested in research watersheds, and will be enhanced to enable accurate model simulations of dominant hydrologic processes in different environments, including glaciers and permafrost in Alaska and volcanic geology, intense rainfall, and high rates of evapotranspiration in Hawaii.

*   SUMMA will provide the foundation for future hydrologic scenarios for the next generation of climate impacts assessments.  This effort will carefully assess underlying model uncertainty and provide the water resources community with a manageable subset of quantitative hydrologic storylines to support water resources planning efforts.
