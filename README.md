# Getting-and-Cleaning-Data-Course-Project

Assumption: Data files are already downloaded, unzipped and available at working directory including subdirectories

###1. Read the activity_labels.txt into a table for activity_id to activity_label referencing 

###2. Clean test data set
####a. Subset mean and std col only (excludes mean freq cols)
####b. Column bind activity ids to test data set
####c. Column bind subject ids to test data set
####d. Reference activity_id to activity_label using label table
  
###3. Clean train data set
####a. Subset mean and std col only (excludes mean freq cols)
####b. Column bind activity ids to train data set
####c. Column bind subject ids to train data set
####d. Reference activity_id to activity_label using label table

###4. Row bind train data set to test data set
 
###5. Calculate average of each variable for each activity and each subject

###6. Write data frame to file
  
