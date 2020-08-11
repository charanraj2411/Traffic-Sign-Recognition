# Traffic-Sign-Recognition

A Traffic sign recognition system which helps to gather the message conveyed via images is trained over 50k images with around 95% of model accuracy.

Technologies used : Python 
Libraries used    : keras , tensorflow , numpy , sklearn 

We created a training data set consisting of 43 different signs with ample amount of images for each set in order to get the accuracy of more than 90%

The images for training and test set are taken from the kaggle challenge of German Traffic Sign Recognition challenge.
https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

We created a training model and saved it in a traffic.clasifier.h5 file.

The model is first trained against 80% of train images and tested against the remaining 20% images
Also the final validation is performed again on the model with a different set of input.

After  validation we created a Graphical User Interace which takes the input as traffic.classifier.h5 model and creates a UI which accepts inputs from the user and predicts the sign.

Model Training file : Traffic Sign Recognition System.ipynb



GUI file            : GUI.ipynb


