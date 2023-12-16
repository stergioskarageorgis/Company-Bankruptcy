# Company-Bankruptcy
In this kernel we will use various predictive models and analysis on whether a company will go bankrupt or not. Nevertheless, we can still analyze some important aspects of the dataset and draw some conclusions.
This project consists of two programs developed for learning purposes and personal growth. The primary objective is to gain practical experience in programming and advance our skills in python and predictive analysis.

Company Bankrupt Taiwan data set
Data Collection:
Data collected from the Taiwan Economic Journal for the years 1999 to 2009.
Company bankruptcy defined based on the business regulations of the Taiwan Stock Exchange.

Dataset Characteristics:
Large dataset with 96 features, providing an excellent opportunity for dimensionality reduction, exploratory data analysis (EDA), and machine learning.

Data Exploration:
Checking for null values and examining the dataset's shape.
Not performing descriptive analytics at this stage due to the intention to drop many features in the next step.

Feature Selection:
Utilizing a random forest classifier for model-based feature selection.
Acknowledging the challenge of highly unbalanced data and planning to address it through oversampling.

Data Analysis and Model Building Insights:
Noting the influence of outliers on the distribution and considering the use of the median for central measures.
Identifying patterns, including indicators associated with bankruptcy.
Observing that companies with specific financial characteristics tend to go bankrupt.

Model Building Approach:
Considering a KNN algorithm due to evident clusters.
Recognizing the importance of oversampling in dealing with highly imbalanced data.

Tendencies and Key Indicators:
Highlighting tendencies such as high interest-bearing debt interest rate, total debt/total net worth, fixed assets turnover frequency, low cash/total assets, and low equity to liability being associated with bankruptcy.

Next Steps:
Planning to build a reliable model using selected indicators.
Acknowledging the need for oversampling in the preprocessing phase.

Gradient Boosting Classifier:
Implementing a more sophisticated classifier on reduced data.
Achieving a set accuracy of 0.97 with only 7 features, saving significant running time.

Conclusion:
Describing how companies might go bankrupt based on the model's findings.





Overview Company Bankrupt (second file)
Data Loading and Exploration:
The financial dataset is loaded from 'data.csv'.
Data collected from the Taiwan Economic Journal for the years 1999 to 2009.
Initial data exploration includes checking for null values and shaping the dataset.

Data Preprocessing:
Unnecessary features are removed, and column names are cleaned.

Outlier values are replaced with thresholds.
Constant, correlated, and duplicate features are dropped using the Feature Engine library.

Feature Engineering:
Categorical and numerical columns are identified.
Principal Component Analysis (PCA) is applied for dimensionality reduction.

Model Building:
Various machine learning models are implemented, including Logistic Regression, Random Forest, XGBoost, LightGBM, CatBoost, and a Stacking Classifier.
Models are evaluated using classification metrics and visualizations.

Results:
Model performance metrics, including accuracy, precision, recall, F1 score, and ROC-AUC, are presented in a tabular format.
