CleaningData_Coursera
=====================
The run_analysis.R script does the following:

1.Merges the training and the test sets to create one data set.

2.Extracts only the measurements on the mean and standard deviation for each measurement.

3.Uses descriptive activity names to name the activities in the data set.

4.Appropriately labels the data set with descriptive activity names.

5.Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

How the run_analysis.R script works

1.Sets the path to the UCI HAR Dataset.

2.Loads and cleans the data to create the tiny data.

3.Selects only the mean and std features.

4.Calculates the mean of each variable, aggregating over activity and subject.

5.Writes the result data frame to a txt. file in given path.