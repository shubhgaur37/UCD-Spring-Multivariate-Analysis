# UCD Spring Multivariate Analysis

Welcome to my GitHub repository for the "Multivariate Analysis" module, taken during the Spring trimester. This repository contains my coursework, including the assignment and its solution.

You can view the hosted solution and detailed descriptions of the assignment [here](https://shubhgaur37.github.io/UCD-Spring-Multivariate-Analysis/).

## Assignment Details

This assignment is based on a dataset of human facial temperature measurements made using an Infrared Thermograph (IRT). The dataset includes IRT temperature measurements, Oral Temperature measurement, demographic covariates, and an indicator of elevated temperature. The objective is to apply various multivariate analysis techniques to this dataset.

- **Files**:
  - `STAT40150_Assignment_23_24.pdf`: Assignment questions.
  - `Temperature_data.csv`: Dataset used for the analysis.
  - `Solution.qmd`: Quarto Markdown file with the solutions.
  - `Solution.html`: Solution hosted on GitHub Pages.

## Assignment Questions

### 1. Data Loading and Subsetting
- **Task**: Load the `Temperature_data.csv` dataset and select a random subset of 1000 observations.
- **Details**: Use the `set.seed` function in R to set the seed to your student number and select a random subset. Ensure reproducibility by including the code used in this step.

### 2. Data Cleaning and Visualization
- **Task**: Clean the dataset by removing records with missing or extreme values for Oral_Temp, and visualize the data.
- **Details**: Remove observations with missing Oral_Temp or those more than 4 standard deviations below the mean. Create suitable plots and comment on them.

### 3. Clustering Analysis
- **Task**: Perform hierarchical and k-means clustering on the facial temperature measurements.
- **Details**: Motivate decisions, compare clustering solutions, and comment on the clustering structure considering the data context.

### 4. Discriminant Analysis
- **Task**: Classify subjects by gender using linear or quadratic discriminant analysis (LDA/QDA).
- **Details**: Assess classifier performance, plot the decision boundary, and compare LDA and QDA performance.

### 5. Principal Components Analysis (PCA)
- **Task**: Apply PCA to the facial temperature data and plot the cumulative variance explained.
- **Details**: Determine the number of principal components required and explain the choice.

### 6. Principal Component Scores
- **Task**: Derive and plot principal component scores for each subject from first principles.
- **Details**: Comment on any observed structure.

### 7. Principal Components Regression (PCR)
- **Task**: Research and provide a synopsis of the PCR method.
- **Details**: Explain the method’s purpose, workings, choices, and its advantages/disadvantages.

### 8. PCR Model Application
- **Task**: Perform PCR on training data and predict Oral Temperature in the test set.
- **Details**: Motivate decisions and evaluate model performance.

## Solution

The complete solution to this assignment is available as an HTML document. You can view the solution by visiting the following link:

**[View Solution](https://shubhgaur37.github.io/UCD-Spring-Multivariate-Analysis/Solution.html)**

## Contact

For queries or further discussion on these projects, please reach out via email at shubhgaur7833@gmail.com.
