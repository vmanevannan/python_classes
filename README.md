# This notebook organises a RandomForest Classifier into python classes for easy extension of code

# We import a customer-churn dataset with a label 'Churn' :0/1

Custom Class: Define a CustomClassifier that inherits a RandomForest Classifier from python's scikitlearn library.
              We define test_size and random_state as class attributes
              These are required to define a Random Forest Classifier.
              
USECASE 1: We extend our CustomClassifier class to build a Model Class with attributes n_estimators and max_depth.
           These parameters are required to tune hyperparamters and fit an appropriate RandomForest Classifier onto our churn data.
           
USECASE 2: A Model Visualization class is built by extending Model Class 
           This object only uses the predicted and actual values of the churn label in it's implementation.


