# Project compendium template

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## A compendium of code, data, and author's manuscript accompanying the manuscript:

#### TBD


## Overview
This repository is organized as a reproducible research compendium. Future updates to this compendium will include a Dockerfile and Binder Container

## File Organization

    analysis/
    |
    ├── logs/
    │   └── log.md                 # weekly progress logs
    |
    ├── figures/                   # location of the figures produced for the manuscript
    |
    ├── 1. Data Cleaning and KDD/  # notebook and work for data prep, cleaning, and exploratory analysis
    │   └── Capstone_Data KDD.ipynb
    |
    ├── 2. Modality KDD & Analysis/                    # Modality KDD & Trend Analysis (project pivoted to CBI analysis
    │   ├── Capstone_Modality KDD.ipynb                # Modality KDD
    │   └── Capstone_Modality Trend Analysis.ipynb     # Modality Trend Analysis (project pivoted to CBI, did not complete Trend Analysis by Modality)
    |
    ├── 3. CBI Analysis/                               # CBI: Course Bottleneck Index         
    │   ├── Capstone_CBI Analysis.ipynb                        # CBI Analysis, Weight Analysis
    │   └── Capstone_CBI Analysis_Actionable Insights.ipynb    # Actionable Insights based on CBI Analysis
    |
    ├── data/
    |   ├── rawData/        # data obtained from elsewhere
    │   └── derivedData/    # data generated from rawData/ and scripts.*
    |   
    └── supplementaryMaterials/
        ├── supplementaryFigures/     
        |                   # supplementary figures for the main manuscript
        └── supplementaryTables/      
                            # supplementary tables for the main manuscript 
    
    R/Python/etc.           # scripts to run in the following order (also see associated README.md)
        └── script.*        # hypothetical script used to wrangle the raw data, produce figures, analyses, and supplementary materials

        

