A nice, convenient, and simple way to run these notebooks is via https://mybinder.org/ 

All you need to do is click the link and copy and paste the link to my git repository into the top line and hit "Launch".

Next, it will give you a new url in the "Copy the URL below and share your Binder with others:". Copy and paste that link into a new tab and it will create a server for you so that you can run all of the notebooks.



# These are all the files from my Machine Learning Project on the fictional IBM employee dataset.

All of them are in a Jupyter Notebook and can simply be run by running all cells.

HREmployeeNN is the neural network using the entire dataset, trying to predict whether an employee left or not.

BoosingModel is my XGBoost model -- This one might take a little to run since it uses a grid search.

EmployeeAttritionRF is the Random Forest model -- Also might take a long time to run due to grid search and randomized search.

LogisticModel is the Logistic Model for the entire dataset.

SVModel is the Support Vector Machine model for the entire dataset.

EmployeeAttritionEDA is all of my exploratory data analysis on the dataset.

1-2YearsNN is the neural network on a subset of the dataset for employees that have worked/worked at the company for 1-2 years.

1-2Boost is the XGBoost for the subset of the dataset.

1-2Logistic is the Logistic Model for the subset of the dataset.

YearsAtCompany1or2 is roughly the same EDA from the entire subset but now just on the subset for people who worked at the 
company for 1-2 years.
