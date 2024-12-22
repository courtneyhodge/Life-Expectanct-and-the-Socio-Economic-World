# Life Expectancy & Socio-Economic Analysis  

This project explores the relationship between socio-economic factors and life expectancy across global regions using data analysis and predictive modeling techniques in R.  

## Dataset  
The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/mjshri23/life-expectancy-and-socio-economic-world-bank), contains 3,306 observations and 16 variables, including:  
- **Life Expectancy (World Bank)**  
- **Prevalence of Undernourishment**  
- **CO2 Emissions**  
- **Health and Education Expenditures**  
- **Corruption Levels**  
- **Income Classifications**  

## Objectives  
The primary objective of this project is to analyze and model socio-economic indicators that influence life expectancy. Specific goals include:  
1. Investigating how factors like corruption, unemployment, and CO2 emissions impact life expectancy.  
2. Examining patterns in income classifications by region.  
3. Developing a predictive model to estimate undernourishment rates based on life expectancy.  

## Methodology  
### 1. Exploratory Data Analysis (EDA)  
- Created visualizations using `ggplot2` to analyze regional and income-based patterns.  
- Examples:  
  - Stacked bar charts to explore income distribution by region.  
  - Boxplots comparing life expectancy across European, Central Asian, and Sub-Saharan African countries.  

### 2. Predictive Modeling  
- Built a K-Nearest Neighbors (KNN) regression model using the `tidymodels` framework.  
- Performed data preprocessing, including normalization and handling missing values.  
- Tuned the model to minimize RMSE, achieving optimal performance with `k = 49`.  

### 3. Results  
- **Key Insights**:  
  - Regions with higher life expectancy exhibit lower rates of undernourishment.  
  - Socio-economic disparities, such as income level and corruption, are significant predictors of quality of life.  
- **Predictive Model Performance**:  
  - Training RMSE: 7.4  
  - Testing RMSE: 8.13  

## Technologies Used  
- **R Programming**: Data wrangling, visualization, and modeling  
- **Packages**: `ggplot2`, `tidymodels`, `gridExtra`, `dplyr`, `tidyverse`  

## Files  
- `Computational Statistics Project.Rmd`: The RMarkdown file containing all code and analysis.  
- `Computational Statistics Project.pdf`: The compiled report.  

## How to Run  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/life-expectancy-analysis.git  
   cd life-expectancy-analysis
   ```

2. Open `Computational Statistics Project.Rmd` in RStudio
3. Run all code chunks to reproduce the analysis and visualizations.
