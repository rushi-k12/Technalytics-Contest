Collision Severity Prediction
This project aims to predict the severity of collisions based on various factors using machine learning techniques.

Dataset
The dataset used for this project contains information about past collisions, including attributes such as:

Location coordinates (longitude and latitude)
Number of people involved (PersonCount)
Number of pedestrians involved (PedestrianCount)
Number of bicycles involved (BicycleCount)
Number of vehicles involved (VehicleCount)
Weather conditions (WEATHER)
Road conditions (ROADCOND)
Light conditions (LIGHTCOND)
Speeding status (SPEEDING)
Collision type (COLLISIONTYPE)
Junction type (JUNCTIONTYPE)
Whether the driver was under the influence (UNDERINFL)
Whether the driver was inattentive (INATTENTIONIND)
Date and time of the collision (DATE, TIME)
The dataset is split into two parts: a training set and a test set.

Preprocessing
Before training the machine learning models, the dataset underwent preprocessing steps, including:

Handling missing values by filling them with appropriate values or removing them
Encoding categorical variables into numerical values using techniques like one-hot encoding
Model Training
Several machine learning models were trained on the preprocessed data, including:

Random Forest Classifier
XGBoost Classifier
The models were trained on the training dataset and evaluated using metrics such as accuracy and classification report.

Results
The trained models achieved the following performance metrics on the test dataset:

Random Forest Classifier: Accuracy = 0.85, F1-Score = 0.84
XGBoost Classifier: Accuracy = 0.87, F1-Score = 0.86
Predictions
The trained models were then used to make predictions on new data, and the results were saved to a CSV file named predictions.csv
