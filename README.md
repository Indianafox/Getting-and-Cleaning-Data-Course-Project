# Read me file for accelerometer data analysis.
Raw data collected from the from the Samsung Galaxy S smartphone

This github repository contains 
  - Code to analyse and tidy the accelarometer data
  - A code book of the tidy data output
  
 The code performs the following functions 
  - Downloads a zip file from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
  - Loads commponent data from the zip file into R
  - Limits features to the mean and standard deviation features
  - Calculates the mean and sd for these features
  - Writes a tidy data file in txt format
 
