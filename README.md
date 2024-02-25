## Exploratory Data Analysis for Car Price Prediction

### Objective:
The main objective of this analysis is to identify the main characteristics that have the most impact on the car price.

### Data Source:
The dataset used for this analysis contains various features of automobiles and their corresponding prices. You can access the dataset [here](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-SkillsNetwork/labs/Data%20files/automobileEDA.csv).

### Libraries Used:
- pandas (version 1.3.3)
- numpy (version 1.21.2)
- scipy (version 1.7.1)
- seaborn (version 0.9.0)

### Initial Data Loading and Overview:
The analysis begins with loading the dataset into a pandas DataFrame and examining the first few rows to understand the structure and content of the data.

### Analyzing Individual Feature Patterns Using Visualization:
The analysis starts by visualizing individual variables to understand their distributions and relationships with the target variable (car price). Visualizations include scatter plots, box plots, and heatmaps to explore the relationships between different features and the target variable.

### Descriptive Statistical Analysis:
Descriptive statistics are computed for continuous numerical variables to gain insights into their central tendency, dispersion, and shape of the distribution. Additionally, value counts are calculated for categorical variables to understand the frequency distribution of different categories.

### Basics of Grouping:
Grouping is performed to understand how different categories of variables impact the car price. Grouping is done based on specific features, and statistics such as mean are computed for each group.

### Correlation and Causation:
The analysis includes calculating the Pearson correlation coefficient and p-values to determine the strength and significance of the linear relationships between numerical variables and car price. The correlation results help identify potential predictors of car price.

### Conclusion:
Based on the analysis, the following variables are identified as potential predictors of car price:
- Horsepower
- Length
- Width
- Curb-weight
- Engine-size
- Bore
- City-mpg
- Highway-mpg

These variables exhibit statistically significant correlations with the car price and can be used for building predictive models in car price estimation tasks.
