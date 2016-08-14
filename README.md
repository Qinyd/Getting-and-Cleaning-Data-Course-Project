# Getting-and-Cleaning-Data-Course-Project
UCIHAR-Data-Project

Course Project for Gettting & Celaning Data based on Human Activity Recognition Using Smartphones Dataset

This README file explains details around what files are included and what are their features.

Original Data Source

Data for analysis is downloaded from the below URL
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Files Included in Repository

This repo includes following files

run_analysis.R
CodeBook.md
README.md

This is the script used to perform analysis on raw data to create a tidy datafile called tidyData.txt

Functions of run_analysis.R Script：
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


To be more specific, the scrip works as following:
Downloads the dataset from the URL mentioned above and unzips it to create UCI HAR Dataset folder
Imports test and train datsets and creates data frames from then and then Merges the training and the test sets to create one data frame.
Extracts a subset of data with only the measurements on the mean mean() and standard deviation std() for each measurement. Also excludes meanFreq()-X measurements or angle measurements where the term mean exists resulting in 66 measurement variables.
Updates the variable names in dataframe variable names for data fame to improve readibility
Appropriately labels the data set with descriptive activity names in place of activity Ids
Reshapes dataset to create a data frame with average of each measurement variable for each activity and each subject
Writes new tidy data frame to a text file to create the required tidy data set file of 180 observations and 68 columns(2 columns for activityName and subjectID and 66 columns for measurement variables)
Running the script

To run the script, you just have to download the script and source the script from your working directory in R. source(run_analysis.R)

