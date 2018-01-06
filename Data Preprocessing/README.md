# data_preprocessing_template.py

*Step 1* - Load our csv file containing our dataset. <br>
*Step 2* - Store the independent variables in X and dependent variables in y.<br>
*Step 3* - Split dataset into training and testing set.<br>
*Step 4* - Apply feature scaling to our independent variables.<br><br>

**Note** - Feature Scaling is applied so that an independent variable of higher value does not dominate while predicting the value of dependent variable.

# missing_data.py
We replace the missing the values in a column with values that is average of that column.

# categorical_data.py

*use of LabelEncoder()*<br>
We can't use strings for mathematical calculations. So we replace the values of columns **Country** and **purchased** with numbers in the range **0 to ((no. of unique values) - 1)** <br>
For example **Country** column has 3 unique values : **France, Spain and Germany**. So they will be replaced by values **0, 1, 2.**
<br>
