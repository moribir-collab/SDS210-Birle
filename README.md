# SDS210-Birle
Analysis of vegetation and surface-related raster values in Zurich using Landsat data from 1985 to 2024 for the Project


## Project Overview

This project investigates how surface-related raster values and vegetation developed in Zurich between 1985 and 2024. The analysis uses Landsat composite raster data and focuses on the relationship between Band 1 values and the Normalized Difference Vegetation Index (NDVI).

The project was created for the course **SDS210 Programming with Spatial Data**.

## Research Question

How have surface-related Band 1 values and vegetation developed in Zurich between 1985 and 2024, and is there a measurable relationship between them across Zurich’s urban districts?

## Data

The analysis is based on 14 Landsat composite raster files for Zurich. Each raster contains 7 bands and covers one year between 1985 and 2024.

Example files:

- LandsatComposite_Zurich_1985.tif
- LandsatComposite_Zurich_1988.tif
- LandsatComposite_Zurich_1991.tif

The raster files are not included in this repository if they exceed GitHub’s file size limits. The expected folder structure is:

```text
Landsat_Zurich/
├── LandsatComposite_Zurich_1985.tif
├── LandsatComposite_Zurich_1988.tif
├── LandsatComposite_Zurich_1991.tif
└── ...
