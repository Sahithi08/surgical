# surgical
This is a surgical tool presence detection project where we have a dataset which contains surgical vidoes and a text file containing instrument information about the video 
i.e which frame contains which instrument with binary value 1 and 0 (1 if instrument is present, 0 if it is not present).
With this data we extract frames fromo videos and take the text file data and train a CNN model 
Then we use the testing data for the model to predict the instruments and find the accuracy.
