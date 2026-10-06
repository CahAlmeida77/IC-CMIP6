# Analysis of CMIP6 Climate Projections

A repository developed as part of an **Undergraduate Research Project in Environmental Engineering**, gathering Python scripts used for the processing, statistical analysis, and visualization of climate data from global models within the **Coupled Model Intercomparison Project Phase 6 (CMIP6)**.

The work integrates **future climate projections and historical records from weather stations**, focusing on the analysis of **precipitation and temperature** variables and the assessment of variability across different climate models.

## Objective

To develop a computational routine to organize, process, and analyze large volumes of climate data, enabling the comparison of different CMIP6 models and the construction of **ensemble** representations to evaluate patterns, extremes, and uncertainties in climate projections.

## Computational Methodology

The developed code covers the following stages:

* Reading and processing climate files in **NetCDF** format;
* Extracting time series based on weather station coordinates;
* Organizing and processing historical and projected series;
* Calculating **annual maximum precipitation**;
* Processing individual climate models;
* Constructing **ensembles** using the mean and standard deviation across models;
* Generating time series and visualizations for model comparison;
* Consolidating results into **CSV** files for further analysis. ## 📊 Repository structure

```text
iniciacao-cientifica/
│
├── Script
│   └── Precipitation data processing,
│       calculation of annual maxima and ensemble
│
├── Temperatura_ensemble
│   └── Ensemble processing and analysis
│       of temperature data
│
├── Temperatura_graficolinhas
│   └── Generation of temperature series and plots
│
├── acumulada
│   └── Routines related to the cumulative analysis
│       of climate variables
│
├── estacoes.csv
│   └── Identification and coordinates of the
│       weather stations used
│
└── LICENSE
```

## Technologies and libraries

**Python** was used as the primary language for data processing and analysis.

Key libraries employed:

* `pandas` — data organization, processing, and analysis;
* `numpy` — numerical operations and time series processing;
* `netCDF4` — reading and manipulating NetCDF files;
* `matplotlib` — generating plots and visualizations;
* `datetime` — handling time series data.

## Research application

The results obtained using this code are part of an analysis of **climate projections for the Sorocaba (SP) region and surrounding municipalities**, contributing to the investigation of potential future changes in precipitation and temperature patterns.

Using multiple climate models makes it possible to highlight not only trends and average patterns but also the **variability and uncertainty associated with the projections**—a crucial aspect for climate change adaptation studies and environmental planning.

## Note

The scripts in this repository were developed and adapted throughout the various stages of the research. Some file paths and directory structures originally used are specific to the research's development environment and may therefore require adjustments to run on other computers. ---

**Undergraduate Research Project — Environmental Engineering | UNESP Sorocaba**
