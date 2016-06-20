#Source datasets
Original dataset was downloaded from
[https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

Original data collected from the accelerometers from the Samsung Galaxy S smartphone from 30 different subject participants for 6 different activities. 

My copy of the dataset was downloaded Jun 19 18:09.

---
Assignment specs: write a R script which
	  *  Merges the training and the test sets to create one data set.
	  *  Extracts only the measurements on the mean and standard deviation for each measurement.
	  *  Uses descriptive activity names to name the activities in the data set
	  * Appropriately labels the data set with descriptive variable names.
	  * From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
---
#my output
The run_analysis.R script is intended to be run from within the upper-most level of the original UCI HAR Dataset directory.
```
The R object “my_final.df” is the second, independent tidy data set.
```