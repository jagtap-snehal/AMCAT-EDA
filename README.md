
# Analysis and Prediction of AMCAT Scores

## Project Overview
The "Analysis and Prediction of AMCAT Scores" project aims to analyze the performance of candidates in the AMCAT test, understand the relationships between different sections, and develop a machine learning model to predict candidate performance based on historical data.

## Objectives
- Analyze the performance of candidates in various sections of the AMCAT test 
- Explore the relationships between different sections and the overall score.
- Develop a machine learning model to predict candidate performance based on their historical data.

## Libraries Used
This project utilizes the following libraries:
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations and array handling.
- **Matplotlib & Seaborn**: For data visualization and plotting the distribution of scores.
- **Scikit-learn**: For building and evaluating machine learning models (e.g., regression, classification).
- **Statsmodels**: For statistical modeling and hypothesis testing.
- **Jupyter Notebook**: For interactive coding and documentation.

## Data Description
The dataset used in this project contains historical AMCAT scores across various sections for a number of candidates. It includes:
- Section scores
- Overall scores.


## Plots and Visualizations
The analysis includes several visualizations:
- **Histogram and KDE Plots**: Display the distribution of individual section scores.
- **Boxplots**: Show outliers and the spread of scores across different sections.
- **Pairplots**: Visualize relationships between different sections.
- **Heatmap (Correlation Matrix)**: Analyze the correlation between different test sections and overall performance.
- **Bar Charts**: Represent the mean scores for different sections across different candidate demographics.

## Analysis Performed

### Exploratory Data Analysis (EDA)
- Investigated the distribution of scores across different sections.
- Identified outliers, missing values, and anomalies in the data.
  
### Univariate Analysis -> PDF, Histograms, Boxplots, Countplots, etc..
-Find the outliers in each numerical column
-Understand the probability and frequency distribution of each numerical column
-Understand the frequency distribution of each categorical Variable/Column

### Bivariate Analysis
-Discover the relationships between numerical columns using Scatter plots, hexbin plots, pair plots, etc..
-Identify the patterns between categorical and numerical columns using swarmplot, boxplot, barplot, etc..
-Identify relationships between categorical and categorical columns using stacked bar plots.


## Conclusion
The analysis revealed strong correlations between specific sections  and the overall AMCAT score. The machine learning model achieved high accuracy in predicting overall scores based on individual section performance. The insights gained can help candidates focus on areas needing improvement, enhancing their overall AMCAT performance and employability prospects.

## Installation
To run this project, ensure you have Python installed along with the necessary libraries. You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
