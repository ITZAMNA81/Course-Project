# Course-Project
Getting and Cleaning Data Course Project


Introduction
------------
This repository contains the course project for the Coursera course "Getting and Cleaning data", part of the Data Science specialization.


About the raw data
------------------

The features can be found in the x_test.txt. 
The activity labels are in the y_test.txt file.
The test subjects are in the subject_test.txt file.

The same holds for the training set.

About the script and the tidy dataset
-------------------------------------
The script called run_analysis.R will merge the test and training sets together.

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity.

About the Code Book
-------------------
The CodeBook.md file explains the transformations performed and the resulting data and variables.
