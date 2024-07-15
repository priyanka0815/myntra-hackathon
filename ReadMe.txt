The ML model developed is used to detect skin tone and according to the skin tone recommend lip colours and eye shadow colours.
IDE that has been used is jupyter notebook.
For training the model I have used this Kaggle data set- https://www.kaggle.com/datasets/ducnguyen168/dataset-skin-tone/data
The libraries that have been used for the model are numpy , scikit learn ,open cv ,os and joblib
For image processing I have used open CV and extracted skin colour from the image and did basic operations on it
For the classification purpose I have used simple KNN model that is K nearest neighbour model with value of k as 5
The folder contains two file one is skintonedetector and the other one is recommend_colour .In skin_tone_detector the model has been prepared and it has been stored in the form of pickle Python file- knn_skin_tone_model.pkl and the recommend_colour notebook allows you to open webcam,capture a picture when the key S is pressed and predict your skin tone and recommend lip colours and eye shadow colours based on the trained model.