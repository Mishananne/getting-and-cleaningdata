The code book for run_analysis.R
This codebook is part of the Coursera data science course and describes the measurements calculated for the run.analysis.R project in detail.
The data used is from the Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.
A full description is available at the site where the data was obtained.
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Metadata
Data Set Characteristics: Multivariate, Time-Series
Attribute Characteristics: N/A
Associated Tasks: Classidfication, Clustering
Number of Instances: 10299
Number of Attributes: 561
Missing values? N/A
Area: Computer
Date Donated: 2012-12-10
Number of Web Hits: 143843
The raw data represent data collected from the accelerometers from the Samsung Galaxy S II smartphone which the volunteers were wearing on their the waists.
Description of the raw data
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities:
WALKING,
WALKING_UPSTAIRS,
WALKING_DOWNSTAIRS,
SITTING,
STANDING,
LAYING.
The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.
The 3-axial linear acceleration data (time Acc-XYZ) was collected from the embedded accelerometer and 3-axial gyro data was collected from the gyroscope time Gyro-XYZ. The data was obtained at a constant rate of 50 Hz.
Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.
Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).
Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).
These signals were used to estimate variables of the feature vector for each pattern:
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.
The data files contained:
1. activity lables.txt - containing all labels as mentioned above and connects the activity with the labels.
2. features_info.txt - text file explaining the features selection
3. features.txt - text file containing 561 features
4. README.txt - text file with information about the experiment
5. test/subject_test.txt - text file with the subjects of the activities (range 2-24)
6. test/X_test.txt - text file with the x test dataset
7. test/y_test.txt - text file with the y test labels
8. test/Inertial Signals/body_acc_x_test.txt - text file with body acc x data.
9. test/Inertial Signals/body_acc_y_test.txt - text file with body acc y data.
10. test/Inertial Signals/body_acc_z_test.txt - text file with body acc z data.
11. test/Inertial Signals/body_gyro_x_test.txt - text file with body gyro x test data in radian/second units.
12. test/Inertial Signals/body_gyro_y_test.txt - text file with body gyro y test data in in radian/second units.
13. std gravity units:g test/Inertial Signals/body_gyro_z_test.txt - text file with body gyro z test data in radian/second units.
14. test/Inertial Signals/body_total_x_test.txt - text file with body total x data in std gravity units:g
15. test/Inertial Signals/body_total_y_test.txt - text file with body total y data in std gravity units:g
16. test/Inertial Signals/body_total_z_test.txt - text file with body total z data in std gravity units:g
17. train/X_train.txt - text file with the x train dataset
18. train/y_train.txt - text file with the y train labels
19. train/subject_train_txt - text file with the subjects of the activities (range 1-30)
20. train/Inertial Signals/body_acc_x_test.txt - text file with body acc x data.
21. train/Inertial Signals/body_acc_y_test.txt - text file with body acc y data.
22. train/Inertial Signals/body_acc_z_test.txt - text file with body acc z data.
23. train/Inertial Signals/body_gyro_x_test.txt - text file with body gyro x test data in radian/second units.
24. train/Inertial Signals/body_gyro_y_test.txt - text file with body gyro y test data i in radian/second units.
25. train/Inertial Signals/body_gyro_z_test.txt - text file with body gyro z test data in radian/second units.
26. train/Inertial Signals/body_total_x_test.txt - text file with body total x data in std gravity units:g
27. train/Inertial Signals/body_total_y_test.txt - text file with body total y data in std gravity units:g
28. train/Inertial Signals/body_total_z_test.txt - text file with body total z data in std gravity units:g
