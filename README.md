# DS-4002-Project1: Investigating Inequalities in Cancer Research Funding

The goal of this project is to gather data from the NIH Website to determine whethere there is an inequal distribution of cancer research across different cancer types or treatment methods. To do this we will first harvest data from the NIH website, clean the data, and then perform keyword analysis techniques to determine relationships between project abstracts and funding amounts. 

**Software and Platforms:**
All of the code created in this project was run through the google colab platform for the ease of collaboration and sharing. Packages that are used in the file include pandas, numpy, seaborn, matplot, sklearn, and math functions. All of these package downloads are included in the code to make sure that anyone who runs the code can reproduce the results. The program was run across different computers but the online nature of the coding process prevented any problems with the type of computer platform that we individually used. 


**File Directory:**

README.md : This document contains general information about the project and files included in this Repo

LICENSE.md : Licensing and copyright reproducibility information

**DATA FOLDER**
This folder contains all data files, both raw and cleaned, that are used in the project.

Cancer Research Grants(2).csv : This is the raw data file drawn straight from the NIH website. This is the first called file in the cleaning code. 

Clean DF.csv : This file is an intermediate cleaning file that is created through the initial cleaning code. 

Final_dataframe (1).csv : This dataframe is the final clean dataset that we used to conduct analysis. 

Data appendix: This file contains explanations of the data and any important visual statistics.

**SCRIPTS FOLDER**
This folder contains any code used in the project:

Project_1_Code.ipynb : This is the cleaning code that we used to reformat the raw data set downloaded from the NIH website. This code also generates the visualizations that we used in our original data understanding phase to direct the future analysis.

Project 1 Analysis.ipynb : This is the code where we run a few final cleaning functions and then the actual analysis of the data. This is where the conclusions and analysis methods can be found.

**OUTPUT FOLDER**
This folder contains any visual outputs used for preanalysis and understanding of the data set. Files in this folder are named according to their relevance.

Project 1 Presentation: This file includes the slides that will be presented in class. 

**Reproduction Instructions**
The first step for analysis replication is downloading the initial dataset indluded in the DATA folder above. Using this dataset, run the "Project_1_code.ipynb" to obtain the outputs and clean dataframe used in the analysis section. To return the results of the analysis, run the code "project 1 analysis.ipynb" which calls on the dataframe created in the first code. This should produce identical results to the ones that we achieved. 

**References**
[1]National Cancer Institute, “Common Cancer Types,” National Cancer Institute, Mar. 07, 2023. https://www.cancer.gov/types/common-cancers

[2]“Home | RePORT,” report.nih.gov. https://report.nih.gov/
