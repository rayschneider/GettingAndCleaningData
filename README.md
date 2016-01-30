Project for Getting and Cleaning Data
=====================================
Author: Raymond Schneider (https://github.com/rayschneider/GettingAndCleaningData)

Parameters for Project
----------------------
> The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project. You will be required to submit: 1) a tidy data set as described below, 2) a link to a Github repository with your script for performing the analysis, and 3) a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  
> 
> One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 
> 
> http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 
> 
> Here are the data for the project: 
> 
> https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
> 
> You should create one R script called run_analysis.R that does the following. 
> 
> 1. Merges the training and the test sets to create one data set.
> 2. Extracts only the measurements on the mean and standard deviation for each measurement.
> 3. Uses descriptive activity names to name the activities in the data set.
> 4. Appropriately labels the data set with descriptive activity names.
> 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
> 
> Good luck!

Steps to create the tidy data set
--------------------------------
1. Open 'run_analysis.R' in either a text editor or R Studio.
2. Change parameter of the 'setwd' function to your desired working directory, and save the change.
3. Run 'run_analysis.R' in R or R Studio.  This will download the data set, unzip the data, and create the tidy data set.  The output will be 'tidyData.txt' in the directory specified in Step 2.

Notes
-----
1. The dplyr and data.table packages are used in 'run_analysis.R'.  Please make sure these are installed before running the script.  The script will call these packages for you.
2. The codebook for the data set is in the 'codebook.md' file in the repository.
3. Additional information on the original dataset is contained in the files in "./UCI HAR Dataset", which is created when the data set is downloaded and unzipped.
