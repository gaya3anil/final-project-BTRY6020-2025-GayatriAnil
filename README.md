# final-project-BTRY6020-2025-GayatriAnil
Final project for BTRY 6020: A linear regression analysis to predict NBA player net rating


Linear Regression Analysis Predicting NBA Player Point Differential Based on Box Scores and Demographic Data

Name: Gayatri Anil

Date: May 14, 2024

This analysis was developed as part of a final project for BTRY 6020 Statistical Methods II, taught at Cornell University in Spring 2025.

##############################################################################

Computing Environment Details: 

-Operating System: Windows 11 

-Number of CPUs/Cores:  processor Intel(R) Core(TM) i7-8550U CPU @ 1.80GHz, 2001 Mhz, 4 Core(s), 8 Logical Processor(s) laptop

-R version: 4.4.1, R studio version: 2024.04.2

##############################################################################

Data:

The dataset used in this analysis is the NBA Players dataset curated by Justinas Cirtuatas and publicly available on Kaggle (https://www.kaggle.com/datasets/justinas/nba-players-data?resource=download&select=all_seasons.csv). I have downloaded the dataset as a .csv file, which is available in this repository as "all_seasons.csv"

##########################################################################

Required R packages:

1. "dplyr"

2. "car"

3. "lmtest"

4. "sandwich"

5. "boot"

The .Rmd file "Requirements.Rmd" installs and loads these five required R packages for the analysis.

###########################################################################

To run code:

1. Please begin by setting your working directory to the folder for this respository, titled "final-project-stsci6020-2025-GayatriAnil"

2. Next, please run the file "Requirements.Rmd" to install and load the necessary R packages for the analysis.

3. Then, please run the scripts in the listed order. To run each .Rmd script, you can click the dropdown option on the button "RUN" and select "Run all"

  Order to run scripts:

    "1_ExploratoryDataAnalysis.Rmd"

    "2_LinearRegressionAssumptions.Rmd"

    "3_HypothesisTestingandFeatureImpactAnalysis.Rmd"

    "4_Final_Report_Summary.Rmd"

If you would like to run all the scripts and view it rendered as a .pdf, please just run the script: "Final_Report_pdf.Rmd." If you try to render the scripts 1-4 individually, it will not work because there are variables that are created in a previous script that are necessary to run the next script. Therefore, to run all the scripts at once please use, "Final_Report_pdf.Rmd". Alternatively, if you would like to just view the .pdf file of all the rendered scripts (1-4), please open the file "Final_Report_pdf.pdf" available in the repository.

4. I structured this analysis such that scripts 1-3 include code for building the regression models and making various plots as well as descriptions of my     interpretations of the code/the analysis. Script 4 "4_Final_Report_Summary.Rmd" is a brief summary of the dataset and problem of interest, methods used, results, discussion, conclusion, and references used. 

