# GettingCleaningData
## Week 4 Assignment

---
In the script run_analysis.R, these steps,
```
"features" allows the variable names to be read, so they can be assigned in
"testDF" and "trainDF", which read the data from each group.
```
"my_mergedtables" merges the 2 different data sets.
```
my_mergedtablesedit is a pipeline which:
* selects only the columns that represent the mean and standard deviation for each measurement
* adds a column which has the descriptive term for each activity
* renames the variable V1.1 to "subject_id_number"
```
gsub("x.", "", names(my_mergedtablesedit) removes the "x." text from the colnames where it appears
```
my_mergedtablesedited selects only the columns needed, by removing column 67
```
my_groups  regroups the data by subject_id_number and activity
```
my_final is an clumsy approach to summarizing the data by each subject and activity 
and the mean of each other variable.