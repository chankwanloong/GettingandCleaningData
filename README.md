# Getting and Cleaning Data Course Project

## Purpose
The purpose of this project is to demonstrate an ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

## Files
* run_analysis.R: Script for performing the analysis.
* CodeBook.md: Code book that describes the variables, the data, and any transformations or work that were performed to clean up the data.
* tidydata.txt: Tidy data set with the average of each variable for each activity and each subject.

## Assumptions
* The Samsung data is available in the working directory in an unzipped UCI HAR Dataset folder.
* The dplyr package has been installed.

## Instructions
Run run_analysis.R by typing source("run_analysis.R") in Console.

The run_analysis.R script does the following steps:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The output is a tidydata.txt file that contains the results from step 5.
