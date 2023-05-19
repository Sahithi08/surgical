# surgical
This is a surgical tool presence detection project where we have a dataset which contains surgical vidoes and a text file containing instrument information about the video 
i.e which frame contains which instrument with binary value 1 and 0 (1 if instrument is present, 0 if it is not present).
With this data we extract frames from videos and take the text file data and train a CNN model 
Then we use the testing data for the model to predict the instruments and find the accuracy.

Method 1 contains data preparation for the process and we give training data and testing data seperately.
In method 2 we use split method to split the data into 80 percent training and 20 percent testing we also use techniques like resampling and data
augmentation to make the dataset more balanced.
