# Geographically Weighted Logistic Regression (GWLR) Analysis

This repository contains R code for mapping and documentation for performing Geographically Weighted Logistic Regression (GWLR) analysis using the GWR4 software. The analysis focuses on the impact of various demographic and socioeconomic factors on malaria rapid diagnostic test results.

## Overview

Geographically Weighted Logistic Regression (GWLR) is an extension of logistic regression that accounts for spatial heterogeneity in the data. This analysis was performed using the GWR4 software, which is an open-source tool developed by Brunsdon, Fotheringham, and Charlton. The results were then mapped using R.

## Contents

- `R codes for mapping GWLR results`: R scripts for visualizing the results of the GWLR analysis.
- `for_R^2.shp`: Spatial data in shapefile format used for mapping.
- Documentation on the workflow and methods used in the analysis.

## Prerequisites

To run the scripts, ensure you have the following installed:

- R (version 3.5 or higher)
- RStudio (optional but recommended)
- Required R packages:
  - `datasets`
  - `cluster`
  - `factoextra`
  - `purrr`
  - `ClustGeo`
  - `dendextend`
  - `maptools`
  - `GWmodel`
  - `sp`
  - `spdep`
  - `spData`
  - `sf`
  - `mapdata`
  - `RColorBrewer`
  - `classInt`
  - `ape`
  - `tmap`
  - `cartogram`
  - `car`
  - `ggplot2`
  - `latticeExtra`

## Installation

To install the required packages, run the following commands in R:

```r
install.packages(c("datasets", "cluster", "factoextra", "purrr", "ClustGeo", "dendextend", "maptools", 
                   "GWmodel", "sp", "spdep", "spData", "sf", "mapdata", "RColorBrewer", "classInt", 
                   "ape", "tmap", "cartogram", "car", "ggplot2", "latticeExtra"))
