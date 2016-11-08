---
layout: project
title:  "Meteorological Datasets"
ref: GMET
date:   2016-08-01 16:54:46
categories:
- projects
img: meteorological_datasets.jpg
img2: gmet.png
factsheet1: gmet_1pg.pdf
factsheet2: gmet_factsheet_2016_10.pdf
sponsors: U.S. Army Corps of Engineers, Bureau of Reclamation
teamline1: "NCAR: Martyn Clark (PI), Andrew Newman, Andy Wood, Ethan Gutmann"
teamline2: "U.S. Army Corps of Engineers: Jeff Arnold"
teamline3: "Bureau of Reclamation: Levi Brekke"
contacts: "Contact: Andy Newman - anewman@ucar.edu | Julie Vano - jvano@ucar.edu"
modellink: GMET
tags: [projects]
---

# New Tools and Datasets for Understanding Observational Uncertainty

#### **The challenge:** 
Many hydrologic applications require spatial meteorological datasets (gridded observations), but meteorological stations are neither evenly spaced nor are their observations (e.g. precipitation, temperature) always complete and error free.  Previous efforts to create gridded meteorological datasets from observations ignored uncertainties in measurements and in their interpolation across space, which is especially problematic when observations are sparse or terrain is complex.

#### **Facing this challenge:**

Scientists and engineers in RAL's Hydrometeorological Applications Program at the National Center for Atmospheric Research are collaborating with the U.S. Army Corps of Engineers, the Bureau of Reclamation, and the University of Washington to generate high-quality, probabilistic gridded meteorological fields that reflect uncertainties in historical meteorological datasets. These datasets are useful for global climate model evaluation, hydrologic model parameter estimation, and hydrologic model data assimilation. For example, during the Mississippi River flood of 1993, two areas in the central U.S. showed heavy precipitation: the flood region and the Gulf coast (top panel in figure).  Precipitation in the north of the domain was more spatially uniform than precipitation along the Gulf coast. Areas with highly spatially variable precipitation measurements will have larger uncertainty when interpolated to a grid.  The ensemble is able to capture these differences as shown in the bottom panel, which displays a measure of spread in the ensemble of precipitation estimates.

#### **Scientific advances:**

Development of the Gridded Meteorological Ensemble Tool (GMET) allows for quantification of uncertainty for station-based gridded precipitation and temperature datasets, specifically:

*	GMET completes the many steps needed to construct gridded meteorological ensembles: (1) ingests station data (current simulations draw from over 12,000 unique stations), (2) ensures stations are serially complete (rejects records too short to be validated and fills data gaps using well-established methods), (3) interpolates the serially-complete precipitation and temperature time series from station data to estimate the probability of precipitation occurrence and probability distributions of precipitation amounts, and (4) generates ensemble gridded spatial fields using spatially and temporally correlated random fields to sample from estimated distributions generated in the earlier step, which allows for consistent estimates of uncertainty in both space and time.  The probabilistic interpolation approach is detailed in Clark and Slater [2006].

*	GMET has been used to develop a first-of-its-kind ensemble dataset of daily precipitation and temperature at one-eighth degree spatial resolution for the contiguous United States from 1980 to 2012. The 100-member ensemble dataset, described in Newman et al. [2015], compares well with established data products, reflects observational and interpolation uncertainty, and is freely available at: http://dx. doi.org/10.5065/D6TH8JR2.

*	GMET produced ensembles have been used in hydrologic data assimilation (e.g., to evaluate the potential for snow data assimilation to improve seasonal streamflow prediction across the western US) and high-resolution regional climate model evaluation.

#### **Moving Forward:** 

*	Augment the GMET tool, for example by adding new data sources (e.g., radar, satellite).

*	Use GMET to further evaluate global climate model projections and examine methodological choices such as station selection criteria, interpolation scheme, spatial resolution, and topographic considerations (e.g., lapse rate choices). 

*   Continue to promote ways to incorporate uncertainty estimates as an integrated and formalized component of dataset generation and use.

*   Use GMET to develop ensemble historical meteorological datasets in Alaska and Hawaii.

*   Update the ensemble dataset for the contiguous United States through 2015, yearly updates thereafter.
