# run_analysisUsingR

Targets

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Under the title "# Load Packages and get the Data" the script downloads the documents and extracts files from the zip downloaded.

Then, the script loads the documents related with activity labels and features. First, identifying the mean and the Standard deviation and second, giving an structure.

The next step wrote in the script loads and cleans the documents into the folder "train" on another hand in the folder "test". Resulting two datasets, one of them with the combinadion of the documents into the folder "train and the second one a dataset with the data into the folder "test". 

Once the datasets of train and test are setted up, the script combines both into an unique dataset. So, the current step output is a dataset with the data of both train and test.

The last one is the step 5. Creation of a second tidy dataset.
