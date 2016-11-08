---
layout: project
title:  "Intermediate-Complexity Downscaling"
ref: ICAR
date:   2016-08-01 16:55:00
categories:
- projects
img: intermediate-complexity_downscaling.jpg
img2: icar.png
factsheet1: comingsoon.pdf
factsheet2: icar_factsheet_2016_10.pdf
sponsors: U.S. Army Corps of Engineers, Bureau of Reclamation, National Science Foundation (check)
teamline1: "NCAR: Ethan Gutmann (PI), Martyn Clark, Trude Eidhammer, Roy Rasmussen"
teamline2: "Uni Research (Bergen, Norway):  Idar Bartstad"
teamline3: "U.S. Army Corps of Engineers: Jeff Arnold"
teamline4: "Bureau of Reclamation: Levi Brekke"
contacts: "Contact: Ethan Gutmann- gutmann@ucar.edu | Julie Vano - jvano@ucar.edu"
modellink: ICAR
tags: [projects]
---

# Advances in Generating Locally Relevant Climate Change Information

#### **The challenge:** 

While climate change is occurring globally, changes are felt locally.  However, global climate models do not produce information at locally relevant scales.  Therefore, water managers and planners use “downscaling” methods to convert global climate data to decision-relevant spatial scales. 

One of the more reliable ways to perform this downscaling is through the use of high-resolution regional climate models; however, such models are too computationally expensive to be run for long time periods.  As a result, water managers often rely on simpler, statistical methods to downscale climate data. Such statistical methods however do not include atmospheric dynamics, and, therefore, may not represent local climate changes as well.

#### **Facing this challenge:**

Scientists and engineers in RAL's Hydrometeorological Applications Program at the National Center for Atmospheric Research are collaborating with the U.S. Army Corps of Engineers, the Bureau of Reclamation, and the University of Bergen to develop a more computationally efficient form of regional climate modeling, the Intermediate Complexity Atmospheric Research model (ICAR).  ICAR combines large-scale atmospheric circulation from climate models with Linear Mountain Wave theory, a mathematical solution for determining the effect of mountains on atmospheric winds, to generate wind fields and calculate the motion of air parcels within the atmosphere. Then ICAR performs detailed full-physics calculations relating three-dimensional water vapor and temperature to the formation of clouds, rain, and snow.  The resulting precipitation predictions are similar to those predicted by a full-complexity regional climate model (WRF), and to the PRISM observed dataset (illustrated in the figure). The source code for ICAR, along with a growing library of documentation, is freely available at https://www.github.com/NCAR/icar.

#### **Scientific advances:**

ICAR provides a new way of generating local climate information that captures local atmospheric dynamics and is computationally efficient, freeing water managers and planners from needing to choose between statistical and dynamical downscaling methods.

*   *Physical processes.* ICAR provides a method of downscaling that is derived from physical principles, and incorporates some of the most advanced cloud and precipitation calculations in the scientific literature.

*   *Computational efficiency.* ICAR simulations can be performed 100 to 1000 times faster than a comparable simulation with a traditional regional climate model.

*   *Skill in current climate.* ICAR’s representation of the precipitation that forms mountain snowpack, which is of great importance to those managing water resources in the western U.S., is excellent. ICAR explains 85-95% of the variability represented in a much more complex regional climate model, and is highly correlated with observed precipitation.

*   *Flexibility.* ICAR has been designed to use a variety of model inputs and can easily be used to evaluate the influence of different physical assumptions on the downscaling process.

#### **Moving Forward:** 

*   Current work is focused on improving the skill and physical process representation of ICAR, particularly for convective precipitation and land surface feedbacks.

*	ICAR is being used to generate downscaled climate datasets for the United States, including Alaska and Hawaii.

*   ICAR is being evaluated in a variety of environments, including tests in the Alps, Norway, the Himalayas, and Chile.
