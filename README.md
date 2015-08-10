
GETTING AND CLEANING DATA COURSE PROJECT

Project Description

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project.
You will be required to submit:
i.	a tidy data set as described below
ii.	a link to a Github repository with your script for performing the analysis, and
iii.	a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This file explains how all of the scripts work and how they are connected.

One of the most exciting areas in all of data science right now is wearable computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
You should create one R script called run_analysis.R that does the following.
i.	Merges the training and the test sets to create one data set.
ii.	Extracts only the measurements on the mean and standard deviation for each measurement.
iii.	Uses descriptive activity names to name the activities in the data set
iv.	Appropriately labels the data set with descriptive activity names.
v.	Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

What you find in this repository
i.	CodeBook.md: information about raw and tidy data set and elaboration made to transform them
ii.	tidyData.txt: data
iii.	README.md: this file
iv.	run_analysis.R: R script to transform raw data set in a tidy one

How to create the tidy data set:
i.	clone this repository: git clone https://github.com/equinenas/Coursera_Getting_and_Cleaning_Data_Course_Project.git
ii.	download compressed raw data
iii.	unzip raw data and copy the directory UCI HAR Dataset to the cloned repository root directory
iv.	open a R console and set the working directory to the repository root (use setwd())
v.	source run_analisys.R script (it requires the plyr package): source('run_analysis.R')

