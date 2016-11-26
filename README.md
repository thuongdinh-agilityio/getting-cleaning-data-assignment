# Getting and Cleaning Data - Coursera Assignment

This is the course project for the Getting and Cleaning Data Coursera course.

## How to
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it does not already exist.
2. Load the activity and features info.
3. Loads both the training and test datasets, keep only those columns which
   reflect a mean or standard deviation.
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset.
5. Merges the two datasets.
6. Converts the `activity` and `subject` columns into factors.
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable.