Description

The following script run_analysis.R completes five steps to reach its objective. 
1.	Merge all the similar data using the rbind() function. For this, since they are similar, we are talking about the files that have the same number of columns and have reference to the same units.
2.	Next, we note that only the columns with the mean and standard deviation measures are extracted from the entire dataset. Then, after taking these columns, they are renamed the correct names, that are from features.txt.
3.	The activity data is issued with the values 1:6, then we use the activity names and IDs from activity_labels.txt and they are replaced in the dataset.
4.	Throughout the dataset, the columns with unclear column names are fixed and corrected.
5.	Lastly, we can create a newer dataset with the average measures for each subject and activity type (30 subjects * 6 activities = 180 rows). The output file is called averages_data.txt, and uploaded to this repository.

The Variables

•	x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from all of the downloaded files.
•	x_data, y_data and subject_data merge the previous datasets for further analysis later on.
•	These features embody the right names for the x_data dataset, which are added to the column names stored in mean_and_std_features, a numeric vector used to extract the data that you want.
•	Another approach is to take with the activity names through the activities variable.
•	all_data merges x_data, y_data and subject_data in a large dataset.
•	Then lastly, averages_data holds the important averages which will be later stored in a .txt file. ddply() from the plyr package is used to apply colMeans() and ease the development.

