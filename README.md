# Matplotlib - The Power of Plots <!-- omit in toc -->

If you would like to see my finding, please scroll down to the findings section.

## Table of Contents <!-- omit in toc -->

- [Background](#background)
- [Reporting Steps](#reporting-steps)
  - [Summary Statistics Table](#summary-statistics-table)
  - [Bar plot](#bar-plot)
  - [Pie plot](#pie-plot)
  - [Box and whisker plot](#box-and-whisker-plot)
  - [Line plot](#line-plot)
  - [Scatter plot](#scatter-plot)
  - [Linear regression model](#linear-regression-model)
- [Findings](#findings)

## Background

In this assignment, I took on the role of of a senior data analyst, working for Pymaceuticals, Inc. a burgeoning pharmaceutical company.
The company began screening for potential treatments for squamous cell carcinoma(SCC), a commonly occurring form of skin cancer.
I've been given to the complete data from their most recent animal study covering 250 mice idetntifed  with SCC tumor growth.
Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of the company's new drug Capomulin versus other existing treatment resignments.
I have asked to generate all of the tables and figures needed for the technical report of the study.
The executive team also asked for a top-level summary of the study results.

## Reporting Steps

### Summary Statistics Table

- I created a table using Pandas dataframes which included the following measures for tumor volume of each regimen in the study:
  - Mean
  - Median
  - Variance
  - Standard Deviation
  - SEM 

### Bar plot

- I generated bar plots showing the number of data points for each treatment regimen. This was done using both:
  - Matplotlib's pyplot
  - Pandas' DataFrame.plot

### Pie plot

- I generated pie plots showing the distribution of mice per gender using:
  - Matplotlib's pyplot
  - Pandas' DataFrame.plot

### Box and whisker plot

- I caluclated the final tumor volume of each mouse across four of the most promising treatment regimens and used it to create a box and whisker plot. The four regimens were:
  - Capomulin
  - Ramicane
  - Infubinol
  - Caftamin

### Line plot

- I created a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

### Scatter plot

- I created a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

### Linear regression model

- I calculated the correlation coefficient using pearsonr and created a linear regression model between mouse weight and average tumor volume. 

## Findings

These are my three inferences or observations of the data:

-Competitor drug Ramicane seems to be the best drug for the mice based on smallest final tumor volume after the test period. 

- The mice used in the Ramicane trial were the youngest of all mice used across regimens. This could have contributed to the fact that Ramicane came out as the most effective. 

-Thereis a positive correlation between the weight of the mice and their tumors. As the size of the tumor increase, the total weight of the mice increase as well.
