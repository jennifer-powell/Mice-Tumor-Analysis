# Mice-Tumor-Analysis

- ## Overview and Background of Assignment
  - While your data companions rushed off to jobs in finance and government, you remained adamant that science was the way for you. Staying true to your mission, you've joined Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
  - As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. 
  
- ## Programs, Languages and Tools
  - Python Matplotlib in jupyter notebook was used to analyze and visualize the data.

- ## Analysis of the data
  - The data was checked for any mouse ID with duplicate time points and then removed. This cleaned data was used for the rest of the analysis
  - A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen was created
  - A bar plot shows the number of total mice for each treatment regimen throughout the course of the study.
  - Generated a pie plot shows the distribution of female or male mice in the study.
  - Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
  - A mouse that was treated with Capomulin was selected at random and a line plot of tumor volume vs. time point for that mouse was created
  - Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.
  - Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.

- ## Overall Observations
    - Over all the study had even control: males to females and amount of mice used for each drug regimen, with a variety of age and weight. There is a moderate correlation betweent eh size of the mouse and the size of the tumor. On first look the assumption could be made that a bigger mouse will develop a bigger tumor. As can be seen in the summary table, some of the drugs made the tumors bigger while others got smaller and had on averge smaller tumors.

