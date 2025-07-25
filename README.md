# House-Prices-EDA-Project
Exploratory Data Analysis of House Prices dataset using Python, Pandas, and Seaborn
House Prices - Exploratory Data Analysis (EDA) Project

Project Overview
This project focuses on performing a comprehensive Exploratory Data Analysis (EDA) on the "House Prices - Advanced Regression Techniques" dataset from Kaggle. The primary goal is to understand the underlying patterns, relationships, and key insights within the data that could influence house prices, ultimately laying the groundwork for a future predictive modeling task.

Dataset
The dataset used in this analysis is the "House Prices" dataset, originally hosted on Kaggle. It contains 79 explanatory variables describing almost every aspect of residential homes in Ames, Iowa, and aims to predict the final SalePrice of each home.

Source: Kaggle: House Prices - Advanced Regression Techniques

Key Features: Includes a rich mix of numerical (e.g., GrLivArea, YearBuilt) and categorical (e.g., Neighborhood, HouseStyle) features, making it ideal for demonstrating various EDA techniques.

Exploratory Data Analysis (EDA) Sections & Key Findings
This EDA was conducted following a structured approach, covering various aspects of data understanding and visualization.

1. Overall Data Structure and Information
The dataset contains 1460 rows and 81 columns. It includes a mix of numerical and categorical features. A significant number of columns, such as PoolQC, MiscFeature, Alley, and Fence, have a high percentage of missing values, indicating a need for careful handling during data preprocessing.

2. Examining the Target Variable (SalePrice)
SalePrice has a mean of approximately $180,921.20 and a median of $163,000.00, suggesting a right-skewed distribution. The standard deviation is around $79,442.50, indicating considerable variability. Histograms and boxplots visually confirm this right-skewness and highlight the presence of several high-value outliers.



3. Examining Numerical Variables (Excluding SalePrice)
Numerical features like GrLivArea, GarageArea, and TotalBsmtSF show varying distributions, with many exhibiting right-skewness and outliers. YearBuilt indicates the construction year range, while OverallQual (treated as numerical here) spans from 1 to 10, showing its quality scale. These variables represent key physical attributes of the houses.




4. Examining Categorical Variables
Categorical variables like MSZoning, Neighborhood, and HouseStyle reveal the distribution of properties across different categories. Neighborhood shows a wide range of categories with varying frequencies, indicating diverse geographical locations. OverallQual, ExterQual, and KitchenQual (when treated as categorical) highlight the distribution of quality ratings, with certain quality levels being more common.



5. Examining Correlation Between Numerical Variables
The correlation matrix shows varying degrees of linear relationships among numerical features. GrLivArea, GarageArea, TotalBsmtSF, and OverallQual exhibit strong positive correlations with SalePrice. Heatmaps provide a clear visual representation of these relationships, indicating which features move together and which are most influential for predicting house prices.



6. Examining Relationship Between Categorical Variables and SalePrice
Boxplots and violin plots effectively demonstrate how SalePrice distributions vary across different categories of features like OverallQual, Neighborhood, and ExterQual. For instance, higher OverallQual categories consistently show higher median SalePrice and narrower price ranges, indicating a strong positive relationship between perceived quality and selling price. Neighborhood also shows distinct price distributions, highlighting the impact of location.



Tools and Technologies
Python: Programming language for data analysis.

Pandas: Data manipulation and analysis library.

NumPy: Numerical computing library.

Matplotlib: Plotting library (used for basic plot configurations).

Seaborn: Statistical data visualization library (used for creating aesthetically pleasing and informative plots).

Google Colab: Cloud-based Jupyter notebook environment for execution.




Author
Omidreza Ahmadi/omidrezaasdev
