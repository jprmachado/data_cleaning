## Source of the original data:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## Original description:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

# R script (run_analysis.R) performs the following

Merges the training and test sets to create one data set:

train/X_train.txt with test/X_test.txt
train/subject_train.txt with test/subject_test.txt
train/y_train.txt with test/y_test.txt

Reads file features.txt and extracts only the measurements on the mean
and standard deviation for each measurement.

Reads activity_labels.txt and applies descriptive activity names to
name the activities in the data set.

The script also appropriately labels the data set with descriptive
names.

Finally, the script creates a 2nd, independent tidy data set with the
average of each measurement for each activity and each subject.

