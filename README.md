# Getting-and-Cleaning-Data-Course-Project

Assumption: Data files are already downloaded, unzipped and available at working directory including subdirectories

###1. Read the activity_labels.txt into a label table for activity_id to activity_label referencing 

###2. Clean test data set
####a. Read test data
####b. Subset mean and std col only (excludes mean freq cols)
####c. Read y_test.txt (activity ids)
####d. Column bind activity ids to test data set
####e. Read subject_test.txt (subject ids)
####f. Column bind subject ids to test data set
####g. Reference activity_id to activity_label using label table
  
###3. Clean train data set
####a. Read train data
####b. Subset mean and std col only (excludes mean freq cols)
####c. Read y_train.txt (activity ids)
####d. Column bind activity ids to train data set
####e. Read subject_train.txt (subject ids)
####f. Column bind subject ids to train data set
####g. Reference activity_id to activity_label using label table

###4. Row bind train data set to test data set
 
###5. Calculate average of each variable for each activity and each subject

###6. Write data frame to file
  
