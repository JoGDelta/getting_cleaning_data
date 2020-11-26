# getting_cleaning_data

This is a repository for the Coursera "Getting and Cleaning Data" peer graded final assignment.

The assignment is an exercise in acquiring and cleaning data, and uses data from the [UCI Machine Learning Repository: Human Activity Recognition and Smart Phone Data website.](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) The data for the project can be downloaded [here.](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

## Project Files

### Data Processing Script: run_analysis.R

This R script reads the data files, combines them into one data file, and assigns meaningful names to variables. The full set of variables is reduced to a subset of means and standard deviations.

### Tidy Data Output: tidyDataset.txt

This tidy data set contains data that is grouped by subject and activity, and summarized by the mean of each variable.

### Data Processing Description and Variable Names: CodeBook.md

This file contains the data processing steps and variable that were used in the run_analysis.R script.
