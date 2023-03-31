# 05-Matplotlib
Hi there! Welcome to my Github repository for the assignment "What good is data without a good plot to tell the story?" In this assignment, I was tasked with applying my knowledge of Matplotlib to a real-world situation and dataset.

As a senior data analyst at Pymaceuticals, Inc., a pharmaceutical company that specializes in anti-cancer medications, I was given access to the complete data from their most recent animal study. The study involved 249 mice with SCC tumors that received treatment with a range of drug regimens, including Pymaceuticals’ drug of interest, Capomulin. The purpose of the study was to compare the performance of Capomulin against the other treatment regimens.

The executive team at Pymaceuticals has tasked me with generating all of the tables and figures needed for the technical report of the clinical study, as well as a top-level summary of the study results. To complete this assignment, I will follow the following tasks:

Prepare the data.
Generate summary statistics.
Create bar charts and pie charts.
Calculate quartiles, find outliers, and create a box plot.
Create a line plot and a scatter plot.
Calculate correlation and regression.
Submit my final analysis.
To get started, I will download the provided files and run the package dependency and data imports, and then merge the mouse_metadata and study_results DataFrames into a single DataFrame. I will then display the number of unique mice IDs in the data, check for any mouse ID with duplicate time points, and create a new DataFrame where this data is removed.

I will then create a DataFrame of summary statistics that includes a row for each drug regimen and a column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.

Next, I will generate two bar charts and two pie charts. The bar charts will show the total number of time points for all mice tested for each drug regimen throughout the study, while the pie charts will show the distribution of female versus male mice in the study.

I will then calculate the final tumor volume of each mouse across four of the most promising treatment regimens and determine if there are any potential outliers across all four treatment regimens. Using Matplotlib, I will generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group.

To create a line plot and a scatter plot, I will select a mouse that was treated with Capomulin and generate a line plot of tumor volume versus time point for that mouse. I will also generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

Finally, I will calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment and plot the linear regression model on top of the scatter plot.

I hope this readme file provides a clear understanding of the tasks I will be completing for this assignment. Stay tuned for my final analysis!