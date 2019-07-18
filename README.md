# CoursraWeek4CleaningData
 Assignment Week4 Coursera
##This repository containst the submission for the assignment for week 4 of Getting and Cleaning Data Coursera course.
##First, download and unzip the data file into your R working directory.
##Second, download the R source code into your R working directory.
##Third and last step, execute R source code to generate tidy data file.

# Data Description
##The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects. 
##The variable in the data Y indicates activity type the subjects performed during recording.

#Code explanation
##The code combined training dataset and test dataset, and extracted partial variables to create another dataset with the averages of each variable for each activity.

#New DataSet
##The new generated dataset contains variables calculated based on the mean and standard deviation. 
## Everyrow of the dataset is an average of each activity type for all subjects.
##All the code written it is based on an interpretation of the instruction published in this assignment.
##The R script called run_analysis.R perform the following tasks:

##1.Merges the training and the test sets to create one data set
##2.Extracts only the measurements on the mean and standard deviation for each measurement. 
##3.Uses descriptive activity names to name the activities in the data set
##4.Appropriately labels the data set with descriptive variable names. 
##5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
