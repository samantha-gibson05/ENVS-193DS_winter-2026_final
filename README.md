# ENVS-193DS_winter-2026_final
Final Project for ENV 193DS

## General information
**What is this repo for?**
This repository contains my completed final project assignment for ENVS 193DS (Winter 2026). The assignment includes 4 parts: research writing, data visualization, statistical modeling, and reflection on exploratory versus affective visualizations. Across these sections, I worked with datasets to practice statistical communication, data cleaning and visualization, logistic regression model selection and interpretation, and linear regression using my own personal sleep data. The repository includes the raw datasets, Quarto/R Markdown code used to complete the assignment, and the rendered HTML output.

**Whose repo is it? Who is contributing to it?**
This is Sami Gibson’s repository. All work was completed by Sami Gibson as an individual assignment for ENVS 193DS: Environmental Data Science at UCSB (Winter 2026). The assignment instructions were provided by the course instructor.

## Data and file overview 
**What files are there?**
The repository is organized into several folders and files: 
- `data/`: Contains the 3 datasets used in the assignment (Annual_Kelp_All_Years_20250903.csv, MOPL_nest-site_selection_Duchardt_et_al._2019.csv, 193DS data - stress (6).csv)
- `code/`: Contains the rmd file used to complete the final assignment and the rendered HTML output
- README.md: Provides an overview of the repository contents and links to the rendered output
- .Rproj file: Opens the project in RStudio with the correct working directory structure
- .gitignore: Specifies files Git should ignore

**What code is there, and what does it do?**
The code in this repository completes the ENVS 193DS final assignment. The setup section loads required packages and reads in the three datasets. Problem 1 contains written statistical interpretation and research communication related to linear regression and Kruskal–Wallis testing. Problem 2 cleans and summarizes the kelp dataset, creates a multi-series line plot of mean kelp fronds per year across three sites, and interprets variation among sites. Problem 3 uses the Mountain Plover dataset to create a binary response variable, fit four logistic regression models, compare them with AIC, check DHARMa residual diagnostics, generate predicted probabilities with confidence intervals, and interpret the biological meaning of the best-supported model. Problem 4 compares affective and exploratory visualizations from earlier assignments, proposes and runs a linear regression using personal sleep data, checks assumptions, visualizes model predictions with confidence intervals, and interprets the resulting relationship between sleep efficiency and time slept.

# Rendered output
[Link to the rendered .html here](https://samantha-gibson05.github.io/ENVS-193DS_winter-2026_final/code/Final_Project_Code.html)
