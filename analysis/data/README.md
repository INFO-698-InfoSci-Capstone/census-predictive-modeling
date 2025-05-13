# README for data used in census-predictive-modeling

## Overview 
Data used for Enrollment Bottleneck Analysis: Identifying Difficult-to-Access Courses in Undergraduate Information Science capstone project
***

## All Data
All Data Lives in Box: https://arizona.box.com/s/41zintju69iar5eftnn7cm8lwe04d5iv
 * Access has been granted to Dr Chism & aligned College of InfoSci Staff

Box Includes Folders:
 * Folders The Code Should Create - this contains all the outputs by folder the code should create as you flow through the 5 notebooks. These are for reference.
 * CBI Analysis - necessary for "Capstone_CBI Analysis.ipynb" 
 * Capstone Project Data - necessary for "Capstone_Data KDD.ipynb" - Original data from UA

## Necessary Data To Download For Code to Run
1. Data Cleaning and KDD > "Capstone_Data KDD.ipynb"
 * Must have a saved folder "Capstone Project Data" in your Jupyter Notebook folder with the original data provided by UA
 * Source for download: https://arizona.box.com/s/co2vlp5aie9mb0gd1rrrb0t65kqza2vy

3. CBI Analysis > "Capstone_CBI Analysis.ipynb"
 * Must have a saved folder "CBI Analysis" in your Jupyter Notebook folder with the original data provided by UA
 * Source for download: https://arizona.box.com/s/r086ydcdxc1f328nee8z6ksbpeh9gqqc
 * Note - 2. Modality KDD & Analysis > "Capstone_Modality KDD.ipynb" should already make a folder for you "CBI Analysis" with df_all.xlsx exported into the folder. *What needs to be downloaded from Box* is the 2 new files for CBI analysis: 1) "2022_2025_Faculty Load Analysis w. Class # - CLEANED" and 2) "Course List w. Pre-Reqs"

## Folder Map: Folders Needed-for & Created-by per .ipynb Notebook

 * Begin: have a saved folder "Capstone Project Data" in your Jupyter Notebook folder with the original data provided by UA
     * Source for download: https://arizona.box.com/s/co2vlp5aie9mb0gd1rrrb0t65kqza2vy

1. Data Cleaning and KDD > "Capstone_Data KDD.ipynb"
 * Input Folder: "Capstone Project Data" (saved from Box)
 * Output Folder: Capstone Project Data_Cleaned

2. Modality KDD & Analysis > "Capstone_Modality KDD.ipynb"
 * Input Folder: Capstone Project Data_Cleaned, created above
 * Output Folder #1: Modality Trends
 * Output Folder #2: CBI Analysis
   
2. Modality KDD & Analysis > "Capstone_Modality KDD.ipynb"> "Capstone_Modality Trend Analysis.ipynb"
 * Input Folder: Modality Trends, created above
 * N/A Output Folder

4. CBI Analysis > "Capstone_CBI Analysis.ipynb"
 * Input Folder: CBI Analysis, created above (2. Modality KDD & Analysis > "Capstone_Modality KDD.ipynb")
     * **NOTE:** must save Faculty Load & Pre-Req documents from Box into this CBI Analysis Folder
     * Source for download: https://arizona.box.com/s/r086ydcdxc1f328nee8z6ksbpeh9gqqc
 * Output Folder: CBI Analysis_Actionable Insights

4. CBI Analysis > "Capstone_CBI Analysis_Actionable Insights.ipynb"
 * Input Folder: CBI Analysis_Actionable Insights
 * Output Folder: CBI Analysis_Actionable Insights_Final Findings

***
