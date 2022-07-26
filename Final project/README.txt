README

1. IN "Traffic_sign.ipynb" & "Traffic_shape.ipynb¡±
# READ DATASET
Read image data and read data from "txt" into dataframe.
# PRE-PROCESSING
Intercept the traffic sign in each picture.
Divided traffic signs into training_objects and testing_objects
Divided the information of traffic signs as shape data and sign data
# NORMALIZATION
Did normalization to training_objects and testing_objects.
We test the result when adding normalization, but we did not get a better result, so we did not run this sell when testing.
#RESIZE & RENAME LABELS
resize pictures to 24 x 24 and rename the shape labels as 0-9.
# CTEATE VALIDATION DATASET
Randomly selected 700 pictures as validation dataset
# CNN
Built a convolutional neural network
#TRAINING & TESTING
Used 128 picutres as a batch and ran 500 epochs.
Computed the final result using test dataset 
# RANDOM TEST
Randomly selected 20 pictures in test dataset and test if our prediction is right
3. IN "SVM & KNN"
Test SVM & KNN algorithm
4. IN "ResNet.ipynb"
We tried to use ResNet to deal with the problem of Gradient explosion.
For the worse result, we did not use it.