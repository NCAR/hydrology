---
layout: project
title:  "Parameter Estimation"
ref: MPR-flex
date:   2016-04-25 16:54:46
categories:
- projects
img: parameter_estimation.jpg
img2: mpr-flex.png
factsheet1: comingsoon.pdf
factsheet2: mpr-flex_factsheet_2016_10.pdf
thumb: mpr-flex.png
sponsors: U.S. Army Corps of Engineers, Bureau of Reclamation
teamline1: "NCAR: Martyn Clark (PI), Naoki Mizukami, Andrew Newman, Andy Wood, Ethan Gutmann"
teamline2: "UFZ Helmholz Institute (Leipzig, Germany): Luis Samaniego, Olda Rakevic, Stephan Thober"
teamline3: "U.S. Army Corps of Engineers: Jeff Arnold"
teamline4: "Bureau of Reclamation: Levi Brekke"
contacts: "Contact: Martyn Clark - mclark@ucar.edu | Julie Vano - jvano@ucar.edu"
modellink: MPR-flex
tags: [projects]
---

# Removing Artificial Barriers in Nationwide Hydrologic Simulations

#### **The challenge:** 
Hydrologic models estimate the exchange of water and energy at the land surface using physically-based equations that represent the features of different locations (e.g., forests v. grasslands) based on parameters that vary spatially. While many parameter values are based on satellite information or geological surveys, others are estimated through calibration (e.g., adjust parameter values to match historical streamflow). Parameter estimation over large domains is especially difficult. Consequently, many current large scale hydrologic assessments rely on spatially inconsistent parameter fields (left panels in figure below) resulting from individual basin calibration, or spatially constant parameters resulting from the adoption of default or a-priori estimates.

#### **Facing this challenge:**

Scientists and engineers in RAL's Hydrometeorological Applications Program at the National Center for Atmospheric Research are collaborating with the U.S. Army Corps of Engineers, the Bureau of Reclamation, and the University of Washington to build a model-independent, flexible parameter estimation tool that enables continental-domain applications of multiple hydrologic models in a spatially consistent way.

#### **Scientific advances:**

Parameter estimation over the United States is being improved by:

*	Development of a stand-alone software package that can generate optimized, spatially continuous parameter fields for multiple hydrologic models. This parameter estimation tool, MPR-flex, uses the Multi-scale Parameter Regionalization (MPR) technique, first developed for the meso-scale Hydrologic Model (mHM) [Samaniego et al. 2010]. 

*   Improved the functionality in the MPR technique through adding a library of equations (pedo-transfer functions), which relate measurable geophysical properties of soil and vegetation to parameter values that hydrologic models use to simulate water movement and storage in the soil.  

*   Modifications in how parameters are estimated spatially. Instead of conducting simulations for every grid, obtain optimized transfer function coefficients for key hydrologic model parameters, based on several hundred unimpaired headwater basins across the United States.  Then, parameter values in locations that are ungauged (and therefore cannot be calibrated) can be estimated using these optimized transfer function coefficients.

*	Discovery of viable parameters that can be based on a combination of measureable properties (e.g., root-zone depth is based on vegetation-soil interaction, base flow parameter depends on topography and saturated hydraulic conductivity). MPR-flex is designed to ingest various geophysical properties such as soil, topography, vegetation information in the same framework, which facilitates estimation of these multifaceted parameters.

*   New parameter sets for the contiguous United States are generated for the VIC hydrologic model using MPR-flex (two parameter fields are illustrated in the figure).


#### **Moving Forward:** 

These scientific advances provide opportunities to:

*	Use MPR-flex to generate spatially distributed parameter sets for other hydrologic models (e.g., the modeling framework SUMMA).

*	Conduct spatially consistent, continental-domain climate impact assessments using multiple hydrologic models.

*	Better understand and evaluate parameter uncertainty in hydrologic models by varying assumptions made during the parameter estimation process.

*	Use MPR-flex to estimate parameters in Alaska and Hawaii.
