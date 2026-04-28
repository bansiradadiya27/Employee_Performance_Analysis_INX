# Employee_Performance_Analysis_INX
This project focuses on analyzing employee data from INX Future Inc. to understand the key factors affecting employee performance and to build a predictive model for performance rating. INX Future Inc. is a global data analytics and automation solutions provider known for its employee-friendly policies and strong employer reputation. However, the company has recently faced challenges with declining employee performance and reduced client satisfaction, making this analysis highly relevant.

The dataset used in this project consists of 1200 records and 28 features, including both quantitative and qualitative variables. Initial data preprocessing was performed to clean the dataset, handle missing values, and remove irrelevant features such as EmpNumber, which do not contribute to performance prediction. Categorical variables were encoded into numerical form to make the data suitable for machine learning algorithms.

Exploratory Data Analysis (EDA) was conducted using univariate, bivariate, and multivariate techniques to understand the distribution of data and relationships between features. Outlier detection and handling were performed using the IQR method to improve data quality. Correlation analysis and visualization techniques such as heatmaps and violin plots were used to identify patterns and trends in employee performance across different departments.

Department-wise analysis revealed that most employees perform at an average level, with departments like Development and Data Science showing consistent performance, while Sales, HR, and Finance exhibit higher variability. Feature importance analysis using a Random Forest model identified EmpEnvironmentSatisfaction, EmpLastSalaryHikePercent, and YearsSinceLastPromotion as the top factors influencing employee performance, highlighting the importance of compensation and experience.

A machine learning model (Random Forest Classifier) was developed to predict employee performance based on input features. The model was evaluated using accuracy and classification metrics to ensure reliable predictions.

The insights derived from this project can help organizations make data-driven decisions, improve employee performance, optimize hiring strategies, and enhance overall productivity and client satisfaction.
