# Getting-and-Cleaning-Data-Course-Project

The script requires the dataset from the zip file found at https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip. After unzipping the file and moving that file into the working directory, the next step is to read the features, activity_labels, and each of the train and test txt files into its own dataset using the read.table function. Then using the rbind function, the script binds together the train and test datasets for  subject, x and y respectively. It then uses cbind to merge the merged subject, x, and y datasets into one large merged dataset. Next, the script takes the measurements (x dataset) on the mean and standard deviation for each of the measurements. Then replace the activities(y dataset) column to its labeled name from the activity_labels.txt file. Finally generate the tidy dataset that consists of the average for each of the variable for every subject and activity. Save this in the file tidyDataSet.txt

