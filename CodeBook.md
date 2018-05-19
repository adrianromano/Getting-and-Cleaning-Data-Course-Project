# Code book 

This code book describes the data, variables and transformations used in the project.

# Data

The data source is a dataset that was taken from the Human Activity Recognition Using Smartphones from the UCI Machince Learning Repository.

A full description about the data is available from the webstite http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

The raw data for the project can be found here https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The final data result tidydata.txt contains the output of the clean tidy dataset of the project.

# Transformations

The transformations performed include the following steps:

1. Merging the test set with the training sets to create one data set.
2. Changing the activity and subject columns to factors.
3. Extracting only the column names that contain mean and standard deviation.
4. Name the activity column to the appropriate descriptive names.
5. Clean the rest of the column names to an appropriate descriptive variable names.
6. Create a second independent tidy data set of the average of each variable for each activity and subject.

# Variables

* subject: contains the ID of the test subjects from 1 - 30.
* activity: contains the type of activity performed when the test measurement was taken, the activity labels are WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING.

*Measurements:*
* timeBodyAccelerometerMeanX
* timeBodyAccelerometerMeanY
* timeBodyAccelerometerMeanZ
* timeBodyAccelerometerStdX
* timeBodyAccelerometerStdY
* timeBodyAccelerometerStdZ
* timeGravityAccelerometerMeanX
* timeGravityAccelerometerMeanY
* timeGravityAccelerometerMeanZ
* timeGravityAccelerometerStdX
* timeGravityAccelerometerStdY
* timeGravityAccelerometerStdZ
* timeBodyAccelerometerJerkMeanX
* timeBodyAccelerometerJerkMeanY
* timeBodyAccelerometerJerkMeanZ
* timeBodyAccelerometerJerkStdX
* timeBodyAccelerometerJerkStdY
* timeBodyAccelerometerJerkStdZ
* timeBodyGyroscopeMeanX
* timeBodyGyroscopeMeanY
* timeBodyGyroscopeMeanZ
* timeBodyGyroscopeStdX
* timeBodyGyroscopeStdY
* timeBodyGyroscopeStdZ
* timeBodyGyroscopeJerkMeanX
* timeBodyGyroscopeJerkMeanY
* timeBodyGyroscopeJerkMeanZ
* timeBodyGyroscopeJerkStdX
* timeBodyGyroscopeJerkStdY
* timeBodyGyroscopeJerkStdZ
* timeBodyAccelerometerMagnitudeMean
* timeBodyAccelerometerMagnitudeStd
* timeGravityAccelerometerMagnitudeMean
* timeGravityAccelerometerMagnitudeStd
* timeBodyAccelerometerJerkMagnitudeMean
* timeBodyAccelerometerJerkMagnitudeStd
* timeBodyGyroscopeMagnitudeMean
* timeBodyGyroscopeMagnitudeStd
* timeBodyGyroscopeJerkMagnitudeMean
* timeBodyGyroscopeJerkMagnitudeStd
* frequencyBodyAccelerometerMeanX
* frequencyBodyAccelerometerMeanY
* frequencyBodyAccelerometerMeanZ
* frequencyBodyAccelerometerStdX
* frequencyBodyAccelerometerStdY
* frequencyBodyAccelerometerStdZ
* frequencyBodyAccelerometerMeanFreqX
* frequencyBodyAccelerometerMeanFreqY
* frequencyBodyAccelerometerMeanFreqZ
* frequencyBodyAccelerometerJerkMeanX
* frequencyBodyAccelerometerJerkMeanY
* frequencyBodyAccelerometerJerkMeanZ
* frequencyBodyAccelerometerJerkStdX
* frequencyBodyAccelerometerJerkStdY
* frequencyBodyAccelerometerJerkStdZ
* frequencyBodyAccelerometerJerkMeanFreqX
* frequencyBodyAccelerometerJerkMeanFreqY
* frequencyBodyAccelerometerJerkMeanFreqZ
* frequencyBodyGyroscopeMeanX
* frequencyBodyGyroscopeMeanY
* frequencyBodyGyroscopeMeanZ
* frequencyBodyGyroscopeStdX
* frequencyBodyGyroscopeStdY
* frequencyBodyGyroscopeStdZ
* frequencyBodyGyroscopeMeanFreqX
* frequencyBodyGyroscopeMeanFreqY
* frequencyBodyGyroscopeMeanFreqZ
* frequencyBodyAccelerometerMagnitudeMean
* frequencyBodyAccelerometerMagnitudeStd
* frequencyBodyAccelerometerMagnitudeMeanFreq
* frequencyBodyAccelerometerJerkMagnitudeMean
* frequencyBodyAccelerometerJerkMagnitudeStd
* frequencyBodyAccelerometerJerkMagnitudeMeanFreq
* frequencyBodyGyroscopeMagnitudeMean
* frequencyBodyGyroscopeMagnitudeStd
* frequencyBodyGyroscopeMagnitudeMeanFreq
* frequencyBodyGyroscopeJerkMagnitudeMean
* frequencyBodyGyroscopeJerkMagnitudeStd
* frequencyBodyGyroscopeJerkMagnitudeMeanFreq

**Mean: the mean average of the measurement.**

**Std: standard deviation of the measurement.**


