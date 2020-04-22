Variables:

The first two variables are activity and subject. The activity shows which type of activity the person is performing e-g walking sitting etc.

Rest of the variables are self explanatory which are given below:
"Time domain signal: Body acceleration,  mean value in X direction" "Time domain signal: Body acceleration,  mean value in Y direction" 
"Time domain signal: Body acceleration,  mean value in Z direction" "Time domain signal: Gravity acceleration,  mean value in X direction" 
"Time domain signal: Gravity acceleration,  mean value in Y direction" "Time domain signal: Gravity acceleration,  mean value in Z direction"
"Time domain signal: Body acceleration jerk,  mean value in X direction" "Time domain signal: Body acceleration jerk,  mean value in Y direction" 
"Time domain signal: Body acceleration jerk,  mean value in Z direction" "Time domain signal: Body angular velocity,  mean value in X direction" 
"Time domain signal: Body angular velocity,  mean value in Y direction" "Time domain signal: Body angular velocity,  mean value in Z direction" 
"Time domain signal: Body angular velocity jerk, mean value in X direction" "Time domain signal: Body angular velocity jerk,  mean value in Y direction"
"Time domain signal: Body angular velocity jerk,  mean value in Z direction" "Time domain signal: Body acceleration magnitude,  mean value "
"Time domain signal: Gravity acceleration magnitude,  mean value " "Time domain signal: Body acceleration jerk magnitude,  mean value " 
"Time domain signal: Body angular velocity magnitude,  mean value " "Time domain signal: Body angular velocity jerk magnitude,  mean value "
"Frequency domain signal: Body acceleration,  mean value in X direction" "Frequency domain signal: Body acceleration,  mean value in Y direction"
"Frequency domain signal: Body acceleration,  mean value in Z direction" "Frequency domain signal: Body acceleration jerk,  mean value in X direction" 
"Frequency domain signal: Body acceleration jerk,  mean value in Y direction" "Frequency domain signal: Body acceleration jerk,  mean value in Z direction"
"Frequency domain signal: Body angular velocity,  mean value in X direction" "Frequency domain signal: Body angular velocity,  mean value in Y direction"
"Frequency domain signal: Body angular velocity,  mean value in Z direction" "Frequency domain signal: Body acceleration magnitude,  mean value " 
"Frequency domain signal: BodyBody acceleration jerk magnitude,  mean value " "Frequency domain signal: BodyBody angular velocity magnitude,  mean value "
"Frequency domain signal: BodyBody angular velocity jerk magnitude,  mean value " "Time domain signal: Body acceleration,  standart deviation in X direction"
"Time domain signal: Body acceleration,  standart deviation in Y direction" "Time domain signal: Body acceleration,  standart deviation in Z direction" 
"Time domain signal: Gravity acceleration,  standart deviation in X direction" "Time domain signal: Gravity acceleration,  standart deviation in Y direction" 
"Time domain signal: Gravity acceleration,  standart deviation in Z direction" "Time domain signal: Body acceleration jerk,  standart deviation in X direction" 
"Time domain signal: Body acceleration jerk,  standart deviation in Y direction" "Time domain signal: Body acceleration jerk,  standart deviation in Z direction" 
"Time domain signal: Body angular velocity,  standart deviation in X direction" "Time domain signal: Body angular velocity,  standart deviation in Y direction" 
"Time domain signal: Body angular velocity,  standart deviation in Z direction" "Time domain signal: Body angular velocity jerk,  standart deviation in X direction"
"Time domain signal: Body angular velocity jerk,  standart deviation in Y direction" "Time domain signal: Body angular velocity jerk,  standart deviation in Z direction"
"Time domain signal: Body acceleration magnitude,  standart deviation " "Time domain signal: Gravity acceleration magnitude,  standart deviation " 
"Time domain signal: Body acceleration jerk magnitude,  standart deviation " "Time domain signal: Body angular velocity magnitude,  standart deviation "
"Time domain signal: Body angular velocity jerk magnitude,  standart deviation " "Frequency domain signal: Body acceleration,  standart deviation in X direction"
"Frequency domain signal: Body acceleration,  standart deviation in Y direction" "Frequency domain signal: Body acceleration,  standart deviation in Z direction"
"Frequency domain signal: Body acceleration jerk,  standart deviation in X direction" "Frequency domain signal: Body acceleration jerk,  standart deviation in Y direction"
"Frequency domain signal: Body acceleration jerk,  standart deviation in Z direction" "Frequency domain signal: Body angular velocity,  standart deviation in X direction"
"Frequency domain signal: Body angular velocity,  standart deviation in Y direction" "Frequency domain signal: Body angular velocity,  standart deviation in Z direction" 
"Frequency domain signal: Body acceleration magnitude,  standart deviation " "Frequency domain signal: BodyBody acceleration jerk magnitude,  standart deviation "
"Frequency domain signal: BodyBody angular velocity magnitude,  standart deviation " "Frequency domain signal: BodyBody angular velocity jerk magnitude,  standart deviation "

Transformations:
1) Merged the training and test data set to get one data set.
2) Extracted only the measurements on the mean and standard deviation for each measurement.
3) Used descriptive activity names to name the activities in the data set
4) Appropriately labeled the data set with descriptive variable names.
5) From the data set in step 4, created a second, independent tidy data set with the average of each variable for each activity 
   and each subject.
