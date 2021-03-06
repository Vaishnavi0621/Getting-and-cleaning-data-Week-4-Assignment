# Getting-and-cleaning-data-Week-4-Assignment
This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.

   First, download and unzip the data file into your R working directory.
   Second, download the R source code into your R working directory.
   Finally, execute R source code to generate tidy data file.
   
### Data Description
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

### The code was written based on the instruction of this assignment

1. Merges the training and the test sets to create one data set.
Use command rbind to combine training and test set
2. Extracts only the measurements on the mean and standard deviation for each measurement.
Use grep command to get column indexes for variable name contains "mean()" or "std()"
3. Uses descriptive activity names to name the activities in the data set
Convert activity labels to characters and add a new column as factor
4. Appropriately labels the data set with descriptive variable names.
Give the selected descriptive names to variable columns
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.



