# Project compendium template

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## A compendium of code, data, and author's manuscript accompanying the manuscript:
Enrollment Bottleneck Analysis: Identifying Difficult-to-Access Courses in Undergraduate Information Science capstone project. 

## Overview
This repository is organized as a reproducible research compendium. 

## File Organization

    analysis/
    |
    ├── logs/
    │   └── log.md                 # weekly progress logs
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
    |   └── README.md/        # download necessary data from Box, links provided. 
    |   
    └── supplementaryMaterials/
        ├── supplementaryFigures/     
        |                   # supplementary figures for the main manuscript
        └── supplementaryTables/      
                            # supplementary tables for the main manuscript 
    
    Python Jupyter Notebooks.                      # scripts to run in the following order 
        ├── Capstone_Data KDD.ipynb                # Data Cleaning & Preparing DFs by Modality
        ├── Capstone_Modality KDD.ipynb            # KDD for Modality (original project, before CBI)
        ├── Capstone_Modality Trend Analysis.ipynb # Modality Tend Analysis (original project, before CBI) has Time & Days graphs
        ├── Capstone_CBI Analysis.ipynb            # CBI analysis: calculates factors, weights, CBI
        └── Capstone_CBI Analysis_Actionable Insights.ipynb    # Identifying Hard-to-Access Courses & Underlying Factors Why

        

