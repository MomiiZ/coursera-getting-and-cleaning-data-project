# coursera-getting-and-cleaning-data-project

---------- Getting and Cleaning Data Project -------------


## Goal of the Project ## 

1. A tidy data set 
2. A link to a Github repository with your script for performing the analysis 
3. A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
4. Analysis R Script




##  Files in repo ## 

Analysis R Script 
	run_analysis.R 
	https://github.com/MomiiZ/coursera-getting-and-cleaning-data-project/run_analysis.R 
Tidy Data Set 
	tidy.txt
	https://github.com/MomiiZ/coursera-getting-and-cleaning-data-project/tidy.txt

Cookbook
	CODEBOOK.txt
	https://github.com/MomiiZ/coursera-getting-and-cleaning-data-project/CODEBOOK.txt

README  
	README.md
	https://github.com/MomiiZ/coursera-getting-and-cleaning-data-project/README.md

Github Repo 
	Repo 
	https://github.com/MomiiZ/coursera-getting-and-cleaning-data-project




## Project ## 


This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

Download the dataset if it does not already exist in the working directory
Load the activity and feature info
Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidy.txt.


## Author ## 
Project done by Antoine BUI
