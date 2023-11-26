# VehicleClassification

## The Business problem

Imagine a company that has a large inventory of used cars and wants to create a website or a mobile app to make it easier for customers to search and find the exact car they are looking for. One way to improve the user experience would be to allow customers to search for cars by make and model. However, manually entering this information for every car in the inventory could be time-consuming and error-prone.

Using a machine learning model capable of classifying vehicle make and model from images, the company could automatically extract this information from pictures of the cars. This would make it faster and more accurate to input the information, allowing customers to easily search and filter cars by make and model. This would not only improve the customer experience but also save the company time and resources. Additionally, the model could be used to automatically identify and categorize new cars as they come into the inventory.

Now, image you are working for that company as a Machine Learning Engineer and are in charge of creating such model. For the initial proof-of-concept, the Data team collected and labelled pictures for 25 different cars. Your task will be to train a model able to classify those vehicles with a high accuracy (over 80% on the testing dataset).

This is a Multi-class Classification task: we want to predict, given a picture of a vehicle, which of the possible 25 classes is the correct vehicle make-model.

## About the data

The dataset is composed of JPG images, already stored in folders containing the label (vehicle make-model), separated in train and test sets.


## Technical aspects

The technologies involved are:
- Python as the main programming language
- Tensorflow and keras for building features and training ML models
- Matplotlib for the visualizations
- Jupyter notebooks to make the experimentation in an interactive way
