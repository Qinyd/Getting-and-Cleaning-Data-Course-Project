All files to be used as listed above are imported to created data frames and column variables names are updated as follows

data.frame | Variable Names
--- | ---
`featureVariables`   | `"varId", "varName"`          
`activityLabels`     | `"activityId", "activityName"` 
`xTest`              | `featureVariables$varName`    
`yTest`              | `"activityId"`                
`subjectTest`        | `"subjectId"`                 
`xTrain`             | `featureVariables$varName`    
`yTrain`             | `"activityId"`                
`subjectTrain`       | `"subjectId"`    

#### Description of variables in the Tidy Data
Variable Name | Details
--- | ---
`activityName` | Factor with 6 levels WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING
`subjectId` | Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30
`tBodyAccMeanX` | Average of Mean Value time doman Body Accelration in x direction
`tBodyAccMeanY` | Average of Mean Value time doman Body Accelration in Y direction
`tBodyAccMeanZ` | Average of Mean Value time doman Body Accelration in Z direction
`tBodyAccStdX` | Average of Standard deviation time doman Body Accelration in x direction
`tBodyAccStdY` | Average of Standard deviation time doman Body Accelration in Y direction
`tBodyAccStdZ` | Average of Standard deviation time doman Body Accelration in Z direction
`tGravityAccMeanX` | Average of Mean Value time doman Gravity Accelrationin x direction
`tGravityAccMeanY` | Average of Mean Value time doman Gravity Accelrationin Y direction
`tGravityAccMeanZ` | Average of Mean Value time doman Gravity Accelrationin Z direction
`tGravityAccStdX` | Average of Standard deviation time doman Gravity Accelrationin x direction
`tGravityAccStdY` | Average of Standard deviation time doman Gravity Accelrationin Y direction
`tGravityAccStdZ` | Average of Standard deviation time doman Gravity Accelrationin Z direction
`tBodyAccJerkMeanX` | Average of Mean Value time doman Body Accelration Jerk in x direction
`tBodyAccJerkMeanY` | Average of Mean Value time doman Body Accelration Jerk in Y direction
`tBodyAccJerkMeanZ` | Average of Mean Value time doman Body Accelration Jerk in Z direction
`tBodyAccJerkStdX` | Average of Standard deviation time doman Body Accelration Jerk in x direction
`tBodyAccJerkStdY` | Average of Standard deviation time doman Body Accelration Jerk in Y direction
`tBodyAccJerkStdZ` | Average of Standard deviation time doman Body Accelration Jerk in Z direction
`tBodyGyroMeanX` | Average of Mean Value time doman Body Gyro in x direction
`tBodyGyroMeanY` | Average of Mean Value time doman Body Gyro in Y direction
`tBodyGyroMeanZ` | Average of Mean Value time doman Body Gyro in Z direction
`tBodyGyroStdX` | Average of Standard deviation time doman Body Gyro in x direction
`tBodyGyroStdY` | Average of Standard deviation time doman Body Gyro in Y direction
`tBodyGyroStdZ` | Average of Standard deviation time doman Body Gyro in Z direction
`tBodyGyroJerkMeanX` | Average of Mean Value time doman Body Gyro Jerk signal in x direction
`tBodyGyroJerkMeanY` | Average of Mean Value time doman Body Gyro Jerk signal in Y direction
`tBodyGyroJerkMeanZ` | Average of Mean Value time doman Body Gyro Jerk signal in Z direction
`tBodyGyroJerkStdX` | Average of Standard deviation time doman Body Gyro Jerk signal in x direction
`tBodyGyroJerkStdY` | Average of Standard deviation time doman Body Gyro Jerk signal in Y direction
`tBodyGyroJerkStdZ` | Average of Standard deviation time doman Body Gyro Jerk signal in Z direction
`tBodyAccMagMean` | Average of Mean Value time doman Body Accelration magnitude 
`tBodyAccMagStd` | Average of Standard deviation time doman Body Accelration magnitude 
`tGravityAccMagMean` | Average of Mean Value time doman Gravity Accelration magnitude
`tGravityAccMagStd` | Average of Standard deviation time doman Gravity Accelration magnitude
`tBodyAccJerkMagMean` | Average of Mean Value time doman Body Accelration jerk magnitude 
`tBodyAccJerkMagStd` | Average of Standard deviation time doman Body Accelration jerk magnitude 
`tBodyGyroMagMean` | Average of Mean Value time doman Body Gyro magnitude
`tBodyGyroMagStd` | Average of Standard deviation time doman Body Gyro magnitude
`tBodyGyroJerkMagMean` | Average of Mean Value time doman Body Gyro Jerk magnitude
`tBodyGyroJerkMagStd` | Average of Standard deviation time doman Body Gyro Jerk magnitude
`fBodyAccMeanX` | Average of Mean Value frequency domainBody Accelration in x direction
`fBodyAccMeanY` | Average of Mean Value frequency domainBody Accelration in Y direction
`fBodyAccMeanZ` | Average of Mean Value frequency domainBody Accelration in Z direction
`fBodyAccStdX` | Average of Standard deviation frequency domainBody Accelration in x direction
`fBodyAccStdY` | Average of Standard deviation frequency domainBody Accelration in Y direction
`fBodyAccStdZ` | Average of Standard deviation frequency domainBody Accelration in Z direction
`fBodyAccJerkMeanX` | Average of Mean Value frequency domainBody Accelration Jerk in x direction
`fBodyAccJerkMeanY` | Average of Mean Value frequency domainBody Accelration Jerk in Y direction
`fBodyAccJerkMeanZ` | Average of Mean Value frequency domainBody Accelration Jerk in Z direction
`fBodyAccJerkStdX` | Average of Standard deviation frequency domainBody Accelration Jerk in x direction
`fBodyAccJerkStdY` | Average of Standard deviation frequency domainBody Accelration Jerk in Y direction
`fBodyAccJerkStdZ` | Average of Standard deviation frequency domainBody Accelration Jerk in Z direction
`fBodyGyroMeanX` | Average of Mean Value frequency domainBody Gyro in x direction
`fBodyGyroMeanY` | Average of Mean Value frequency domainBody Gyro in Y direction
`fBodyGyroMeanZ` | Average of Mean Value frequency domainBody Gyro in Z direction
`fBodyGyroStdX` | Average of Standard deviation frequency domainBody Gyro in x direction
`fBodyGyroStdY` | Average of Standard deviation frequency domainBody Gyro in Y direction
`fBodyGyroStdZ` | Average of Standard deviation frequency domainBody Gyro in Z direction
`fBodyAccMagMean` | Average of Mean Value frequency domainBody Accelration magnitude 
`fBodyAccMagStd` | Average of Standard deviation frequency domainBody Accelration magnitude 
`fBodyBodyAccJerkMagMean` | Average of Mean Value frequency domainBody Accelration jerk magnitude 
`fBodyBodyAccJerkMagStd` | Average of Standard deviation frequency domainBody Accelration jerk magnitude 
`fBodyBodyGyroMagMean` | Average of Mean Value frequency domainBody Body Gyro magnitude
`fBodyBodyGyroMagStd` | Average of Standard deviation frequency domainBody Body Gyro magnitude
`fBodyBodyGyroJerkMagMean` | Average of Mean Value frequency domainBody Body Gyro jerk magnitude
`fBodyBodyGyroJerkMagStd` | Average of Standard deviation frequency domainBody Body Gyro jerk magnitude 


---
