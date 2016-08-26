# Course Project - Getting and Cleaning Data
## Data Science Specialization

### Purpose:
The purpose of this file is to explain the analysis done on the original study, the processes defined in 'Run_analysis.R' and the resultant data set 'tidy.txt'.

### Original Study:
Analysis was done on data sets produced from the original study of Human Activity Recoginition using smartphones done by Reyes-Ortiz, J. L.; Anguita, D.; Ghio, A.; Oneto, L.; and Parra, X.

### Analysis:
The objective of the analysis was to calculate Average Mean and Standard Deviation measurements for each Activity defined in the original Study. The analysis is carried out by running the script 'Run_Analysis.R'.

'Run_Analysis.R' does the following to data sets ascertained from the initial study.
1. Checks existance of or downloads the data set produced from original study in local working directory.
2. Reads all Training and Test data sets.
3. Combines all Training and Test data in a R Object named 'allData'.
4. Extracts all Measurements of Means and Standard Deviations in a R Object named 'meanStd'. Descriptive Activity labels are added in the column 'Activity' in 'meanStd'.
5. Calculates Average of all observed Mean & Standard Deviation measurements for each Activity and saves the result in a new file named 'tidy.txt' within the working directory.

'tidy.txt' is the resultant file created in the working directory. For details on 'tidy.txt' read 'CodeBook.md'.