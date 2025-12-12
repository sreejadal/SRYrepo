# SRYrepo
ConRR group activity 12Dec2025

DATA COLLECTION: H file from Simon transcribed into Excel

DATA IMPORTING:
Files A, B, P, SouthEast, POP

PROCESS:

Data Cleaning:
- change "current" to Y for smoker status in all files
- fill in any blank fields with NA (all columns, all files)
--> in the gender column: change PNTS to NA as well
- create new ID column to merge each dataset on (calculate it for A, B, P, SE; 
manually add to H file which was technically data we collected)
- make sure all common column names in all files are the same (i.e. MH, PH, etc.)
--> and that their values are coded the same (i.e. Y/N instead of yes/no in all)
- merge A, B, P, SouthEast, and H on ID column
** ran into issues here!!! needed to ensure all datasets had the same # of columns
before merging

Data Encoding:

ANALYSIS:
1) binomial regression to assess whether individuals with ongoing health issues 
believe their condition will get worse while waiting for treatment
- glm()
2) prevalence of health issues in the cohort (adjusting for other factors)
- 
3) how representative the sample is compared to the population
- 

