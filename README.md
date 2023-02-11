## Team members

| Team members   | Role |
| ----------- | ----------- |
| Shatha alyousef |EDA, Encoding and Random Forest algorithm |
| Ali |EDA, KNN algorithm|
| lama |imported several libraries such as numpy, pandas, matplotlib, arabic_reshaper, and sklearn.
loaded the data from a csv file "tamheer_2022.csv" into a pandas dataframe called "df".
preprocessed by dropping some columns and removing any rows with missing values in specific columns.
used the matplotlib library to create different plots such as bar plots and pie charts to visualize the distribution of data in the dataframe.
used the Arabic reshaper library to display Arabic text in the plots correctly.
created a correlation matrix to find the relationships between different columns.
split the data into a training and testing set using the train_test_split function from the sklearn library. |

## Problem

The problem here is that some trainees withdraw from the Tamheer program after a certain period of their registration has passed. Therefore, we created a model that predicts the possibility of the trainee completing or withdrawing from the Tamheer program.

## Dataset Overview

The dataset was taken from open data and contains the following columns: ID - The gender of the trainee - City Apprentice - Trainee District - Specialization of the trainee - Trainee Qualification - Trainee rate - rate from - The age of the trainee is - Trainee status - Name of the training opportunity - The economic activity of the training opportunity - Training qualification - The size of the training institution - The economic activity of the training institution - The educational institution of the trainee

## final results of ML models

 ML algorithm   | Accuracy |
| ----------- | ----------- |
| decision tree |99.06% |
| random forest |99.26%|
| KNN |66.34%|
