# Hand Digit Classifier
This contains the code and data for numbers to be recognised from 0 to 5 using hand gestures. A base-data is already provided and the additional data can be generated by the user using hand gestures. During the process of generating and testing data, hand to be placed on dedicated area on video frames.
## Content
* collect-data.py: Uses opencv to take the image from camera and store it in a pre-built directory structure.
* predict.py: Load the model from the json file and predict a number from 0 to 5.
* train.py: Create a CNN and uses training and testing images to train the model and store it in a json file.
