# Getting and Cleaning Data - Course Project

## Overview

This project is part of the Coursera **Getting and Cleaning Data** course, offered by Johns Hopkins University.

The goal of this project is to demonstrate the ability to collect, work with, and clean a data set. The resulting tidy data set provides the average of each variable for each activity and each subject.

The original data comes from experiments carried out with a group of 30 volunteers within an age bracket of 19–48 years. Each person performed six activities (walking, walking upstairs, walking downstairs, sitting, standing, laying) while wearing a smartphone (Samsung Galaxy S II) on the waist.

## Files Included

- `run_analysis.R`: The R script used to process and tidy the data.
- `tidydata.txt`: The final tidy dataset containing the average of each measurement for each activity and each subject.
- `CodeBook.md`: A file describing the variables and the transformation steps taken.

## How to Run the Script

1. Download the [dataset zip file](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and unzip it into your working directory.
2. Place `run_analysis.R` in the same folder.
3. Open R or RStudio and set the working directory to where `run_analysis.R` is located.
4. Run the script using:
   ```r
   source("run_analysis.R")
