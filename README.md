# Pymaceuticals' Anti-Cancer Drug Study Analysis
## Background
I recently joined Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The company conducted an animal study to screen potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer. The study involved 249 mice with SCC tumors who received different drug regimens, including Pymaceuticals' drug of interest, Capomulin. Tumor development was observed and measured over a period of 45 days. The goal was to compare the performance of Capomulin against other treatment regimens.

As a senior data analyst at Pymaceuticals, I was given access to the complete data from the animal study. My task was to generate all the necessary tables and figures for the technical report of the study and provide a top-level summary of the results.

## Repository Setup
To set up the project repository, I followed these steps:

1. Created a new repository named "pandas-challenge" specifically for this project.
2. Cloned the repository to my local machine.
3. Inside the local Git repository, created a folder named "Pymaceuticals" for this assignment.
4. Added my Jupyter Notebook file to the "Pymaceuticals" folder. This notebook serves as the main script for analysis.
5. Pushed the changes to the remote repository on GitHub.

## Instructions
I completed the assignment by following these tasks:

## Prepare the Data
* Ran the provided package dependency and data imports.
Merged the "mouse_metadata" and "study_results" DataFrames into a single DataFrame.
Displayed the number of unique mice IDs in the data.
Checked for any mouse ID with duplicate time points.
Displayed the data associated with the mouse ID with duplicate time points.
Created a new DataFrame where the duplicate data was removed.

## Generate Summary Statistics
* Created a DataFrame of summary statistics for each drug regimen.
* Calculated the mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen.

## Create Bar Charts and Pie Charts
* Generated two identical bar charts showing the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.
* Created the first bar chart using the Pandas DataFrame.plot() method.
* Created the second bar chart using Matplotlib's pyplot methods.
* Generated two identical pie charts showing the distribution of female versus male mice in the study.
* Created the first pie chart using the Pandas DataFrame.plot() method.
* Created the second pie chart using Matplotlib's pyplot methods.

## Calculate Quartiles, Find Outliers, and Create a Box Plot
* Calculated the final tumor volume of each mouse across four promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
* Calculated the quartiles and interquartile range (IQR) for each regimen.
* Identified potential outliers across all four treatment regimens.
* Generated a box plot using Matplotlib to visualize the distribution of the final tumor volume for all mice in each treatment group.
* Highlighted any potential outliers in the plot by changing their color and style.

## Create a Line Plot and a Scatter Plot
* Selected a single mouse that was treated with Capomulin and generated a line plot of tumor volume versus time point for that mouse.
* Generated a scatter plot of mouse weight versus the average observed tumor volume for the entire Capomulin treatment regimen.

## Calculate Correlation and Regression
* Calculated the correlation coefficient and performed linear regression between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
* Plotted the linear regression model on top of the scatter plot to visualize the relationship between mouse weight and tumor volume.

## Final Analysis
Based on the analysis of Pymaceuticals' anti-cancer drug study, I observed the following trends:

1. Capomulin and Ramicane demonstrated superior performance compared to Infubinol and Ceftamin in reducing tumor volume. The average tumor volume for mice treated with Capomulin and Ramicane decreased over the treatment period, while it increased for mice treated with Infubinol and Ceftamin.

2. There is a positive correlation between mouse weight and average tumor volume in the Capomulin treatment regimen. Heavier mice tend to have larger tumor volumes. This finding suggests that the effectiveness of Capomulin may be influenced by the weight of the mice.
