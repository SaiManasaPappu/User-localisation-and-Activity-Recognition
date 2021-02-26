# User-localisation-and-Activity-Recognition
Trained Random Forest Classifier and Random Forest Regressor models on
[user activity](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones#) dataset and 
[indoor localisation](https://www.kaggle.com/giantuji/UjiIndoorLoc) dataset.

- Given a user_id, we predict the user's location i.e. floor, building, latitude and longitude from the wifi RF signals.

- We also classify the activity the user is performing based on the smart phone sensor data.

Running Source Code Files:


1. Place all the files in the same folder, unzip the compressed files.
2. Run the rf_activity_model.ipynb first. This creates and saves the Random Forest Model for activity classification.
3. Then run the rf_localisation_model.ipynb to build localisation models. This creates 4 separate models to predict floor, building, longitude, latitude. Then tests the code.
