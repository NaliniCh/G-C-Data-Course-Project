##Dataset:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip downloaded and extracted into R working directory

##run_analysis.R Details:
The script has different sections labeled according to the directions given in the course project description and also to load the data and required libraries.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The script generates an output file sensor_avg_by_act_sub.txt in the working directory with the columns as below with mean and standard deviation for each variable the data set by subject

"Subject"
"Activity"

"TimeDomain.BodyAcceleration.Mean.X"
"TimeDomain.BodyAcceleration.Mean.Y"

"TimeDomain.BodyAcceleration.Mean.Z"
"TimeDomain.BodyAcceleration.StandardDeviation.X"
"TimeDomain.BodyAcceleration.StandardDeviation.Y"
"TimeDomain.BodyAcceleration.StandardDeviation.Z"
"TimeDomain.GravityAcceleration.Mean.X"
"TimeDomain.GravityAcceleration.Mean.Y"
"TimeDomain.GravityAcceleration.Mean.Z"
"TimeDomain.GravityAcceleration.StandardDeviation.X"
"TimeDomain.GravityAcceleration.StandardDeviation.Y"
"TimeDomain.GravityAcceleration.StandardDeviation.Z"
"TimeDomain.BodyAccelerationJerk.Mean.X" 
"TimeDomain.BodyAccelerationJerk.Mean.Y" 
"TimeDomain.BodyAccelerationJerk.Mean.Z" 
"TimeDomain.BodyAccelerationJerk.StandardDeviation.X"
"TimeDomain.BodyAccelerationJerk.StandardDeviation.Y"
"TimeDomain.BodyAccelerationJerk.StandardDeviation.Z" 
"TimeDomain.BodyAngularSpeed.Mean.X" 
"TimeDomain.BodyAngularSpeed.Mean.Y"
"TimeDomain.BodyAngularSpeed.Mean.Z"
"TimeDomain.BodyAngularSpeed.StandardDeviation.X"
"TimeDomain.BodyAngularSpeed.StandardDeviation.Y" 
"TimeDomain.BodyAngularSpeed.StandardDeviation.Z" 
"TimeDomain.BodyAngularAcceleration.Mean.X" 
"TimeDomain.BodyAngularAcceleration.Mean.Y" 
"TimeDomain.BodyAngularAcceleration.Mean.Z" 
"TimeDomain.BodyAngularAcceleration.StandardDeviation.X"
"TimeDomain.BodyAngularAcceleration.StandardDeviation.Y"
"TimeDomain.BodyAngularAcceleration.StandardDeviation.Z" 
"TimeDomain.BodyAccelerationMagnitude.Mean"
"TimeDomain.BodyAccelerationMagnitude.StandardDeviation"
"TimeDomain.GravityAccelerationMagnitude.Mean"
"TimeDomain.GravityAccelerationMagnitude.StandardDeviation"
"TimeDomain.BodyAccelerationJerkMagnitude.Mean"
"TimeDomain.BodyAccelerationJerkMagnitude.StandardDeviation"
"TimeDomain.BodyAngularSpeedMagnitude.Mean" 
"TimeDomain.BodyAngularSpeedMagnitude.StandardDeviation" 
"TimeDomain.BodyAngularAccelerationMagnitude.Mean"
"TimeDomain.BodyAngularAccelerationMagnitude.StandardDeviation"
"FrequencyDomain.BodyAcceleration.Mean.X" 
"FrequencyDomain.BodyAcceleration.Mean.Y"
"FrequencyDomain.BodyAcceleration.Mean.Z"
"FrequencyDomain.BodyAcceleration.StandardDeviation.X"
"FrequencyDomain.BodyAcceleration.StandardDeviation.Y"
"FrequencyDomain.BodyAcceleration.StandardDeviation.Z" 
"FrequencyDomain.BodyAcceleration.MeanFrequency.X"
"FrequencyDomain.BodyAcceleration.MeanFrequency.Y"
"FrequencyDomain.BodyAcceleration.MeanFrequency.Z"
"FrequencyDomain.BodyAccelerationJerk.Mean.X" 
"FrequencyDomain.BodyAccelerationJerk.Mean.Y" 
"FrequencyDomain.BodyAccelerationJerk.Mean.Z" 
"FrequencyDomain.BodyAccelerationJerk.StandardDeviation.X" 
"FrequencyDomain.BodyAccelerationJerk.StandardDeviation.Y"
"FrequencyDomain.BodyAccelerationJerk.StandardDeviation.Z"
"FrequencyDomain.BodyAccelerationJerk.MeanFrequency.X"
"FrequencyDomain.BodyAccelerationJerk.MeanFrequency.Y"
"FrequencyDomain.BodyAccelerationJerk.MeanFrequency.Z"
"FrequencyDomain.BodyAngularSpeed.Mean.X" 
"FrequencyDomain.BodyAngularSpeed.Mean.Y" 
"FrequencyDomain.BodyAngularSpeed.Mean.Z" 
"FrequencyDomain.BodyAngularSpeed.StandardDeviation.X" 
"FrequencyDomain.BodyAngularSpeed.StandardDeviation.Y" 
"FrequencyDomain.BodyAngularSpeed.StandardDeviation.Z" 
"FrequencyDomain.BodyAngularSpeed.MeanFrequency.X"
"FrequencyDomain.BodyAngularSpeed.MeanFrequency.Y"
"FrequencyDomain.BodyAngularSpeed.MeanFrequency.Z" 
"FrequencyDomain.BodyAccelerationMagnitude.Mean"
"FrequencyDomain.BodyAccelerationMagnitude.StandardDeviation"
"FrequencyDomain.BodyAccelerationMagnitude.MeanFrequency" 
"FrequencyDomain.BodyBodyAccelerationJerkMagnitude.Mean"
"FrequencyDomain.BodyBodyAccelerationJerkMagnitude.StandardDeviation"
"FrequencyDomain.BodyBodyAccelerationJerkMagnitude.MeanFrequency"
"FrequencyDomain.BodyBodyAngularSpeedMagnitude.Mean" 
"FrequencyDomain.BodyBodyAngularSpeedMagnitude.StandardDeviation"
"FrequencyDomain.BodyBodyAngularSpeedMagnitude.MeanFrequency"
"FrequencyDomain.BodyBodyAngularAccelerationMagnitude.Mean"
"FrequencyDomain.BodyBodyAngularAccelerationMagnitude.StandardDeviation" 
"FrequencyDomain.BodyBodyAngularAccelerationMagnitude.MeanFrequency"