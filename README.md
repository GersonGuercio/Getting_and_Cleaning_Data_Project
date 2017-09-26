# Getting_and_Cleaning_Data_Project Readme file
The code gets data from "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip" and puts it in a folder
called "Samsungdata". Then it extracts the folder and creates a path to the files. 
The code merges the data from subjects, activity and features (which has the variables) in one data frame. It calculates the mean and stardat deviation and also changes the names of variables in the final data set:

"^t" to "time"
"^f" to "frequency"
"Acc" to "Accelerometer"
"Gyro" to "Gyroscope"
"Mag" to "Magnitude"
"BodyBody" to "Body"
