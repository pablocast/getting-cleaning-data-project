README
================

Getting and Cleaning Data - Project
-----------------------------------

run\_analysis.R does:

1.  Download data and unzip it in the working directory (data.zip)
2.  Loads both the training and test datasets (subjects, x and y axis)
3.  Merges the two datasets
4.  Loads the variable names and activity. Renames the columns of the merged dataset and merges the activity description (by activity id)
5.  Extracts only the data on mean and standard deviation (this is done 3.Extract only the data on mean and standard deviation section) 
6.  Converts activity and subject columns into id variables
7.  Creates a tidy dataset consisting of the mean value of each variable for each subject and activity pair.  

Output: `tidy.txt`
