# Customer Segmentation Analysis

## Overview
I developed this customer segmentation project to identify distinct customer groups and provide actionable insights for targeted marketing strategies. Using a combination of R for data preprocessing and modeling, and Tableau for visualization, I created a complete analytics pipeline from raw customer data to business recommendations.

## Project Objectives
- Analyze customer behavior patterns to identify natural segments
- Build a predictive model to classify new customers into appropriate segments
- Create interactive visualizations to communicate key insights
- Provide actionable recommendations for marketing strategies

## Data
The project uses a customer dataset with the following key attributes:
- Demographics: Gender, Age, Marital Status, Education
- Behavioral: Spending Score, Profession, Work Experience
- Household: Family Size

## Methodology

### Data Preprocessing
- Removed ID column and missing values
- Converted categorical variables to factors
- Transformed Spending Score into an ordered factor (Low, Average, High)
- Split data into training (80%) and testing (20%) sets
- Standardized numerical features like Age, Work Experience, and Family Size

### Modeling
- Implemented a Random Forest classifier to segment customers
- Attempted SVM modeling with radial kernel
- Evaluated model performance through confusion matrix and accuracy metrics
- Achieved 44% classification accuracy with the Random Forest model

### Visualization
Used Tableau to create:
- Pie chart showing distribution of customer segments
- Scatter plot of Spending Score vs Age, colored by segment
- Bar chart displaying average age by customer segment
- Box plot showing relationship between Family Size and Spending Score

## Key Findings
- Identified four distinct customer segments with unique characteristics
- Found significant relationships between age, spending patterns, and segment membership
- Discovered family size influences spending behavior across segments

## Tools & Technologies
- R: Data preprocessing, statistical analysis, and machine learning
- Libraries: dplyr, randomForest, e1071, ggplot2
- Tableau: Interactive data visualization and dashboard creation
  - [Dashboard](https://public.tableau.com/app/profile/faven.desta/viz/CustomerSegmentationAnalysis_17417308211040/Dashboard1)

## Future Improvements
- Explore additional feature engineering to improve model accuracy
- Implement hyperparameter tuning for the Random Forest model
- Add more advanced clustering algorithms (K-means, hierarchical)
- Create a predictive model for customer spending potential
