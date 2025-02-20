# Credit Card Fraud Detection system

 Overview 

This  projects contain the Exploratory data analysis of the dataset ( credit card fraud detection system) . The dataset contains almost 280000 rows and 31 columns making it a huge dataset for showcasing robust preprocessing and analytical techniques. 


The project involves exhaustive data analysis , preprocessing and  visualising using seaborn library . Finally algorithms like Logistic regression , Decision tree and other Ensemble Techniques ( Adaboost, Random Forest and XGBoost were applied).


Note:-

For maintaining the confidentiality of the Data , the column names were not specified , and PCA was already applied.
link of the dataset -  https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud



Workflow:-

Data Loading ( feature engineering was not required as the data was precleaned)
EDA : -
Found out the null values( there were 0 null values in the whole dataset).
Columns with fraud and non- fraud were found out.
Data cleaning:-
Upon analysis of  the ‘Classes’ column  , it was found out that , the data was highly imbalanced
Hence, Undersampling was applied to that column.
      4. There was no categorical data in the dataset hence , label encoding/ one-hot      encoding was not applicable.
       5.  Outlier Method : - 
Upon applying IQR method it was found out that , Outliers for the amount are < -281.88 or > 383.16
There were no null columns hence they were not replaced by their mean.
       6. Bivariate and Multivariate Analysis:-
Box plot were designed using seaborn for ‘Time ‘ and ‘Amount’ columns.
Correlation analysis was performed .

        7. Model training
After training the model and splitting the datasets algorithms were applied , followed by hyperparameter tuning .
All the scores are mentioned in the attached juypter file.
