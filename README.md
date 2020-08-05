# Getting-and-cleaning-data-week-4-assignment

Getting-and-Cleaning-Data-Week-4-Assignment

   1. download and unzip the data file into your R working directory.
 2. download the R source code into your R working directory.
 3. execute R source code to generate tidy data file.

Data description

The variables in the data X are  signals m The variable in the data Y indicates activity type the subjects performed during recording.
Code explaination

The code combined training dataset and test dataset.
New dataset

The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.
The code was written based on the instruction of this assignment

Read training and test dataset into R environment. Read variable names into R envrionment. Read subject index into R environment.

   1. Merges the training and the test sets to create one data set. 
    2.Extracts only the measurements on the mean and standard deviation for each measurement.r 
    3.Uses descriptive activity names to name the activities in the data set add a new column as factor
    4.Appropriately labels the data set with descriptive variable names. 
    5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
