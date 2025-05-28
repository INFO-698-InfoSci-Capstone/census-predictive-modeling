# Project compendium template

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

## Enrollment Bottleneck Analysis: 

# Identifying Difficult-to-Access Courses in Undergraduate Information Science capstone project 

Author: Morgan Godley

## Overview
Course accessibility is essential for supporting student engagement and ensuring timely graduation. However, some undergraduate Information Science courses experience enrollment bottlenecks such as infrequent offering, limited instructor availability, and high student demand. This project introduces the Course Bottleneck Index (CBI) as a composite metric to identify and analyze these high-barrier courses across multiple semesters. By tracking CBI trends and contributing factors, we aim to highlight structural challenges and inform strategic scheduling decisions.

This project investigates course accessibility within the undergraduate Information Science program by addressing two key questions:
1. Which courses are the hardest to access, based on high CBI scores?
2. Which factors contribute most to enrollment bottlenecks?

## File Organization

    analysis/
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
    └──  logs/
        └── log.md            # weekly progress logs
    
    Python Jupyter Notebooks.                      # scripts to run in the following order 
        ├── Capstone_Data KDD.ipynb                # Data Cleaning & Preparing DFs by Modality
        ├── Capstone_Modality KDD.ipynb            # KDD for Modality (original project, before CBI)
        ├── Capstone_Modality Trend Analysis.ipynb # Modality Tend Analysis (original project, before CBI) has Time & Days graphs
        ├── Capstone_CBI Analysis.ipynb            # CBI analysis: calculates factors, weights, CBI
        └── Capstone_CBI Analysis_Actionable Insights.ipynb    # Identifying Hard-to-Access Courses & Underlying Factors Why

        

