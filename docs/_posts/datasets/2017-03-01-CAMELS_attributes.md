---
layout: dataset
date: 2017-03-01 10:46:43
publicationyear: 2017
lastupdate: October 2017

authorlist: "Addor, N., A.J. Newman, N. Mizukami, and M.P. Clark"
fulltitle: "The CAMELS data set: catchment attributes and meteorology for large-sample studies"
location: "Boulder, CO"
publisher: "UCAR/NCAR"
download: https://ral.ucar.edu/solutions/products/camels
versions: 2.0
latestversion: 2.0
status: available
doi: 10.5065/D6G73C3Q 

title: "CAMELS: Catchment Attributes for Large-Sample Studies"
shortblurb: "This dataset extends the Large-Sample Hydrometeorological Dataset introduced by Newman et al. 2015 (link below) by characterizing a wide range of attributes for the same 671 catchments in the contiguous USA. The attributes include topographic characteristics, climate indices, hydrological signatures, as well as soil and vegetation attributes."

teamline1: "NCAR: Martyn Clark (PI), Nans Addor, Andrew Newman, Naoki Mizukami"
contacts: "Nans Addor | naddor@ucar.edu"
sponsors: U.S. Army Corps of Engineers

paperdescribe: "Addor et al., HESS, 2017"
paperlink: http://dx.doi.org/10.5194/hess-21-5293-2017

format: ascii files, 1 MB
coverage: 671 watersheds across contiguous US
access: freely available at https://ral.ucar.edu/solutions/products/camels

modellink:
projectlink: meteorological_datasets
datasetlink: CAMELS_timeseries

ref: CAMELS_attributes
filename: CAMELS_attributes
tags: [datasets, dataset_params, dataset_met, dataset_CAMELS_attributes]
categories:
- datasets
---

This dataset covers the same 671 catchments as the Large-Sample Hydrometeorological Dataset introduced by Newman et al. (2015). For each catchment, we characterized a wide range of attributes that influence catchment behavior and hydrological processes. Datasets characterizing these attributes have been available separately for some time, but comprehensive multivariate catchment scale assessments have so far been difficult, because these datasets typically have different spatial configurations, are stored in different archives, or use different data formats. By creating catchment scale estimates of these attributes, our aim is to simplify the assessment of their interrelationships.

Topographic characteristics (e.g. elevation and slope) were retrieved from Newman et al. (2015). Climatic indices (e.g., aridity and frequency of dry days) and hydrological signatures (e.g., mean annual discharge and baseflow index) were computed using the time series provided by Newman et al. (2015). Soil characteristics (e.g., porosity and soil depth) were characterized using the STATSGO data set and the Pelletier et al. (2016) data set. Vegetation characteristics (e.g. the leaf area index and the rooting depth) were inferred using MODIS data. Geological characteristics (e.g., geologic class and the subsurface porosity) were computed using the GLiM and GLHYMPS data sets.

An essential feature, that differentiates this data set from similar ones, is that it both provides quantitative estimates of diverse catchment attributes, and involves assessments of the limitations of the data and methods used to compute those attributes (see Addor et al., 2017). The large number of catchments, combined with the diversity of their geophysical characteristics, makes this new data well suited for large-sample studies and comparative hydrology.

The hydrometeorological time series provided by Newman et al. (2015) together with the catchment attributes described here constitute the CAMELS data set: Catchment Attributes and MEteorology for Large-sample Studies.

<img src="{{ "/assets/img/datasets/CAMELS_attributes_fig1.png" | prepend: site.baseurl }}" class="img-responsive" height="100%" width="100%">

Figure. Four examples of attributes characterized over the contiguous United States.
