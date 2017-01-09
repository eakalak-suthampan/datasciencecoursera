# This is my course project for the course "Getting and Cleaning Data" at coursera.
This project will do about "getting and cleaning data" using data downloaded from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones. This is a dataset about "Human Activity Recognition Using Smartphones Data Set". There is a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. The final result is a data set with the average of each variable for each activity and each subject (group of volunteers). 

## This project contains the following files.
1. README.md (this one, for explain about this project)
2. run_analysis.R (R code for run the analysis and product a tidy dataset which is the file in number 3)
3. tidy_dataset.txt (a tidy dataset produced from run_analysis.R)
4. codebook.md (the codebook for explaining tidy_dataset.txt)

### How to run "run_analysis.R"

I have tested this code on my environment which is  
  * Windows 10 Pro 64-bits
  * R-3.3.0 64-bits
  * RStudio 0.99.902

Please edit the variable "workingDirectory" in the first line of the code to be your working directory on your environment (make sure you have a permission to write on the workingdirectory).
Then just run the entire code. 

### How the code works
the R code "run_analysis.R" begins by downloading and unziping the data, then it will read data into data frame and do the analysis. Finally, it will produce the output file name "tidy_dataset.txt" located in the working directory. This dataset represents average of each variable for each activity and each subject.

Thank You.

Eakalak Suthampan

Coursera Student (DataScience specialization)
