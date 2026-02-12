TITANIC DATA PREPROCESSING PROJECT:

About This Project :
In this project, I worked on cleaning and preparing the Titanic dataset so that it can be used for machine learning. Before building any ML model, the data needs to be cleaned and organized properly. Real-world datasets usually contain missing values and unnecessary information, so preprocessing is a very important step.
This task helped me understand how raw data is transformed into a format that models can actually learn from.

What I Did :
First, I loaded the Titanic dataset using Pandas and explored the structure of the data.
Then i Checked for missing values in the dataset
Removed unnecessary columns like PassengerId, Name, Ticket, and Cabin

Filled missing values:
Replaced missing Age values with the average age
Replaced missing Embarked values with the most frequent value
Converted categorical data into numerical form:
Male → 0
Female → 1
Used one-hot encoding for the Embarked column
Applied feature scaling on Age and Fare using StandardScaler
Saved the cleaned dataset as titanic_cleaned.csv
The final dataset has no missing values and is ready for machine learning model training.

Tools I Used :
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

What I Learned
Through this task, I learned:
How to handle missing data properly
How to convert categorical values into numbers
How data preprocessing fits into the machine learning workflow
This project improved my understanding of how important clean data is for building accurate ML models.
