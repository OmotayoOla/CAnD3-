# CAnD3-
CAnD3 First Assignment

Data Availability Statement:

The data needed to conduct this analysis is freely available on the CAnD3 training platform. 

Datasets needed for this project:

The census dataset is needed to conduct this analysis. Given the relatively huge nature of the dataset, I created a subset of the dataset by copying all data for six (6) variables namely: Age, Sex, Marital Staus, Highest certificate diploma or degree, Class of worker, and place of work status presented as 'AGEGRP', 'Sex', 'MarStH', 'HDGREE', 'COW' and 'POWST' in the datset respectively. This subset of data was named 'Census_mini' and saved in the same location as the initial dataset within the folder linked to Github. The folder linked to Github is named 'Reproducibility'. 

Software Requirements: 

I used a Dell Inspiron 14 2-in-1 to conduct this project and used R version 4.3.2 (2023-10-31 ucrt) for the analysis within the windows operating system. 

Description of the program: 

The code for this analysis is saved as "R Code_Assignment 1". 
The imported dataset is named: 'Census_mini'. 
All other instructions are presented below, and in the code. 

Instructions for replication:

I conducted 3 major tasks in my analysis. Prior to commencing the analyses, I installed the 'readxl' package. This enabled the importation of an excel file. I also leaded the readxl library. 

In the first step, I imported the data as an excel workbook file using the 'read_excel' command anf the name of the file path in double quotation marks. R also required that I doubled the backslashes within the filepath for the code to run. 

In the second step, I viewed some summary statistics using the 'summary' function and converted 5 of the 6 variables (except age) from numerical to factor variables. 
Following this, I viewed the summary to ensure this process had been succcessfully conducted. 

In the last step, I ran a regression model with Age as the outcome, and marital status as the exposure with all the remaining variables included in the model. 

Latly, I printed the regression result. 

All three steps are presented in distinct R markdown code chunks and all codes are well explained in comments beside. 

