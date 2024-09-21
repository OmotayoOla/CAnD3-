# CAnD3-
CAnD3 First Assignment

Data Availability Statement
The data needed to conduct this analysis is freely available on the CAnD3 training platform. 

Datasets needed for this project
The census dataset is needed to conduct this analysis. Given the relatively huge nature of the dataset, a subset of the dataset was created by copying all data for six (6) variables namely: Age, Sex, Marital Staus, Highest certificate diploma or degree, Class of worker, and place of work status presented as 'AGEGRP', 'Sex', 'MarStH', 'HDGREE', 'COW' and 'POWST' in the datset respectively. This subset of data was named 'Census_mini' and saved in the same location as the initial dataset within the folder linked to Github. This folder is named 'Reproducibility'. 

Software Requirements
A Dell Inspiron 14 2-in-1 was used to conduct this project. R version 4.3.2 (2023-10-31 ucrt) was used for the analysis within the windows operating system. 

Description of the program. 
The code for this analysis is saved as "R Code_Assignment 1". 
The imported dataset is named: 'Census_mini'. 
All other instructions are presented in the code. 

Instructions for replication
I conducted 3 major tasks in my analysis. Prior to commencing the analyses, the 'readxl' package was installed. This enabled the importation of an excel file. 
In the first step, the data was imported. 
In the second step, I viewed some summary statistics using the 'summary' function and converted 5 of the 6 variables (except age) from numerical to factor variables. 
In the last step, I ran a regression model with Age as the outcome, and marital status as the exposure with all the remaining variables in the model. 

Latly, I printed the result. 

All codes are well explained in comments beside the codes. 

