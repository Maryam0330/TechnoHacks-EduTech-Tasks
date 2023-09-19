# TechnoHacks-EduTech-Tasks
In this repository, I have uploaded tasks which were assigned to me by TechnoHacks EduTech during Data Analytics Internship.

1. [Task 1 : **Data Cleaning** -](https://github.com/Maryam0330/TechnoHacks-EduTech-Tasks/blob/main/Task%201/data_cleaning.ipynb)
   Cleaned a dataset by removing missing values and outliers. I have used the Titanic dataset from Kaggle. I have used Python 
   various libraries such as NumPy, Pandas, SciPy to complete this task.
   
   Identified missing values from the dataset using  functions such as `isnull()`, `isnull().sum()`. Handled missing values by filling 
   them using the `mean()` and `mode()` of the specific column. Also dropped the column in which many missing values were present. 
   Verified the cleaned DataFrame to check if there are any remaining missing values in the DataFrame.
   
   Used statistical Methods for Outlier Detection : IQR (Interquartile Range) Method to find outliers by identifying data points. 
   Calculated IQR, detected and removed outliers for specific columns.

2. [Task 2 : **Summary Statistics** -](https://github.com/Maryam0330/TechnoHacks-EduTech-Tasks/blob/main/Task%202/summary_statistics.ipynb)
   Calculated summary statistics (mean, median, mode, standard deviation) for numeric columns in a dataset. I have used the Titanic 
   dataset from Kaggle. I have used Python libraries such as NumPy and Pandas to complete this task. 

   Calculated the mean (average) using Pandas `mean()` function, median (middle value) using Pandas `median()` function and standard 
   deviation (dispersion in a set of data points) of the numeric  columns using Pandas' `mean()` function. Calculated the mode (most 
   frequent value) of the numeric columns using SciPy's `mode()` function.

3. [Task 3 : **Remove Duplicates** -](https://github.com/Maryam0330/TechnoHacks-EduTech-Tasks/blob/main/Task%203/remove_duplicates.ipynb)
   Identified and removed duplicate values in a dataset. I have used the Iris dataset from Kaggle. I  have used Python libraries 
   such as NumPy and Pandas to complete this task. 

   Identified duplicates values using the most important method to deal with duplicates, `duplicated()` method which will tell which 
   values are duplicate. Removed duplicates using `drop_duplicates()` method to get rid of duplicate values. And finally checked 
   whether the duplicates are removed from the dataset. 
