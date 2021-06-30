# Revenue-Prediction-Model
Task 2

For this assignment I started by importing packages that I will need which are pandas, numpy, matplotlib and etc.
Afterwards, I uploaded the data and had a glance at first 5 rows. Then, I decided to do Exploratory Data Analysis (EDA) to get a better grasp of the data. 
I checked the dimensions of the data, tried to see what datatypes I have. Here I found that the Revenue columns are not floats, but rather objects.
To change this, I replaced the comma with no space and converted them to float types. Afterwards, I checked the summary statistics of the numerical data.
Another crucial step was to check the missing data. As expected, there were a lot of missing data in the dataset. I also checked the percentage of missing data in each column
to have better idea on how I can handle them later. After checking these values, I decided to impute the values with the mean of eac column. Not an ideal way to go about this, as
I prefer to do multiple imputation, but for the purpose of this task, I chose to do mean substitution. After filling in the missing values, I again checked to verify that I do 
not have any missing values. After this, I checked to see if I have duplicate data however didn't encounter any. I also checked to see the correlation of the variables to further 
help me in building the predicitive model.
