---
layout: project
title:  "Streamflow Routing"
ref: mizuRoute
date:   2016-08-01 16:54:46
categories:
- projects
img: streamflow_routing.jpg
img2: mizuRoute.png
factsheet1: mizuRoute_1pg.pdf
factsheet2: mizuRoute_factsheet_2016_10.pdf
sponsors: U.S. Army Corps of Engineers, Bureau of Reclamation
teamline1: "NCAR: Martyn Clark (PI), Naoki Mizukami"
teamline2: "University of Washington: Bart Nijssen"
contacts: "Contact:  Martyn Clark - mclark@ucar.edu | Julie Vano - jvano@ucar.edu"
modellink: mizuRoute
tags: [projects]
---

# Routing Streamflow to Places Important for Infrastructure Design

#### **The challenge:** 

Hydrologic models generate runoff that is spatially distributed (e.g., across a lattice of grid cells), which then needs to be routed through the channel network to produce streamflow at specific locations. Existing continental domain portrayals of climate impacts commonly evaluate streamflow changes on a grid-based river network, and typically use a single routing scheme and single parameter set to generate flow at a limited number of gauge points. Additionally, different routing schemes work better in different locations (e.g., relatively flat locations benefit from more detailed dynamic simulations than places with a greater elevation gradient).

#### **Facing this challenge:**

Scientists and engineers in RAL's Hydrometeorological Applications Program at the National Center for Atmospheric Research are collaborating with the U.S. Army Corps of Engineers, the Bureau of Reclamation, and the University of Washington to build a multi-method, continental-domain routing model that efficiently routes streamflow from any distributed hydrologic model. This software package, called mizuRoute (in Japanese “mizu” means water), is designed to quickly process large ensembles of future runoff at each time step to any location within the river network (illustrated in figure), facilitating spatial and temporal analysis that can be easily modified to address specific user needs.

#### **Scientific advances:**

*   mizuRoute is a stand-alone software package that can be used with output from any spatially distributed hydrologic model. It can be easily run in parallel and is well-suited for running large-ensembles.

*   mizuRoute can represent both a grid-type or vector-type river network. One benefit of the vector river network is accurate representation of river length and contributing area, leading to more accurate streamflow simulations.

*   mizuRoute can route streamflow for headwater basins, continental-wide river systems, and any desired location in the entire river network (not just pre-designated gauge points).   It currently produces values at 54,000 river segments across the contiguous United States based on the USGS Geospatial Fabric dataset, providing a more efficient and physically realistic alternative to gridded representations of the channel network.

*   mizuRoute is developed in a modular framework. Therefore, multiple routing schemes can be implemented. mizuRoute currently has two routing schemes, one that includes more dynamics (kinematic wave tracking) and another that runs faster by using an impulse response function (unit hydrograph). 

#### **Moving Forward:** 

These scientific advances provide opportunities to:

*	Simulate streamflow for hydrologic model evaluation, calibration, and future climate projections at locations most important to infrastructure design and operations.

*   Development is underway to add elements of water mass tracking, which would allow mizuRoute to be used in water quality evaluation (streamflow temperature, chemical constituents). 

*   Implementation of fuller dynamical routing, which would be more suitable for flat areas. To this end, a user could select the most appropriate routing scheme, depending on the location (e.g., elevation gradients) and compute times, or multiple schemes to assess routing model uncertainty.
