Getting and Cleaning Data: Course Project
Introduction

This repository holds my course project for the Coursera course "Getting and Cleaning Data", part of the Data Science specialization. 

Here is a brief description of the raw data:

The 561 unlabeled features can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file.
This also is the case for the training set.

Here is a brief description of the script and the tidy dataset:

I created a script called run_analysis.R which will merge the test and training sets together. These are the prerequisites for this script:

the UCI HAR Dataset must be extracted and must be availble in a directory called "UCI HAR Dataset"
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.

Here is an explanation of the Code Book:

The CodeBook.md file explains the transformations performed and the resulting data and variables.
