# STAT545 Homework 3 Repository
## Eric Sanders

Welcome! This is a repository used to store the contents of Homework Assignment 3 of *STAT545*, a course taught in the fall of 2018 at the University of British Columbia.

This repository is only contributed to by Eric Sanders, me. The main contribution to this repository besides this ReadMe is an exploration of the `flchain` data frame available for free in R in the `survival` package. This work is visible **[here](https://github.com/STAT545-UBC-students/hw03-ericjsanders/blob/master/hw03Exploration.md**!

## Purpose and Use of the Data

The data set in question tracks some variables describing 7874 persons who participated in a study that identified measures of free light chains in blood serum as well as creatinine levels in blood serum, which can be used to identify kidney function. Patients were tracked to identify if they died during the sudy period.

More background information can be seen in the **[original study here](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2904571/)**, or **[this useful link](https://www.biovendor.com/immunoglobulin-free-light-chains-kappa-and-lambda)** which describes free light chains and their purpose.

In this document you will see the following sections of the data exploration:

* Loading in, Describing, and Observing the Data
* Question 1: How do creatinine levels compare between people with a usual kappa-lambda ratio and people with extreme kappa-lambda ratios?
* Question 2: What is the minimum, maximum, mean, etc. of creatinine level within each death classification?
* Question 3: What is the minimum, maximum, mean, etc. of kappa-lambda ratio within each death classification?
* Question 4: How do creatinine levels and kappa-lambda ratios relate? 
* Question 5: What percentage of people in each age bracket have abnormal kappa-lambda ratios? 
* Summary Statements

## Results of Data Exploration

In the document you will also be able to see how we arrive at the following possible interpretations of our visualizations of the data:

* Creatinine levels did **not** have a visibly different distribution between people that did and did not have abnormal kappa-lambda ratios.
* The only notable death classification to visibly have a different average creatinine level is genitourinary, which makes sense at it involves diseases of the kidneys. Trimmed means were calculated in each classification, alongside other summary statistics.
* There were no clearly visible patterns in kappa-lambda ratio between levels of death classification, although trimmed means were calculated alongside other summary statistics.
* Kappa-lambda levels and creatinine levels appear to slightly positively correlate, evidenced by a discretization of the data as well as a scatter plot. It is uncertain why higher kappa free light chains than lambda might be related to kidney disease.
* The rate of abnormal kappa-lambda ratios decreases with age.