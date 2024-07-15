Introduction and Dataset Overview:

This report analyzes a dataset comprising diverse demographic and economic attributes, including age, education, and occupation, to understand societal trends and behaviors. Key variables such as age, race, sex, educational attainment, employment status, and financial metrics like capital gains and losses are examined. The primary goal is to conduct exploratory data analysis (EDA) and prepare the dataset for classification modeling to predict income levels based on these attributes.

Data Cleaning:

Data cleaning involved handling missing values, removing unnecessary columns, and eliminating duplicates to maintain data integrity. Missing values were addressed using specific imputation strategies, such as group-specific medians for the age column and the mode for categorical variables like workclass and education. The 'fnlwgt' column was removed, and 379 duplicate rows were identified and excluded to ensure the dataset's accuracy.

Exploratory Data Analysis (EDA) and Variable Selection:

EDA was conducted to understand the dataset's structure, relationships between variables, and identify patterns influencing the target variable, salary. Visualizations such as box plots and heatmaps were used to gain insights. Key variables identified for their strong correlation with salary include education number, age, and hours per week. These variables were selected based on their significant impact on predicting income levels.

Model Building and Evaluation:

K-Nearest Neighbors (KNN) models were built using varying values of K (5, 15, and 25) to predict salary categories. Each model was evaluated based on accuracy and confusion matrices. The model with K=15 achieved the best balance, capturing local patterns while generalizing effectively. This K value provided robust performance, demonstrating the effectiveness of using demographic features to predict income categories. The findings highlight the practical applicability of these models in understanding economic disparities and informing decision-making processes.

Conclusion:

The report underscores the importance of using statistical techniques and machine learning models to analyze demographic and economic attributes for predicting income levels. By selecting optimal variables and employing rigorous data cleaning and EDA methods, the analysis provides valuable insights into the factors influencing income inequality. These insights are crucial for addressing economic disparities and guiding policy decisions.

