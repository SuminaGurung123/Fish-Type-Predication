Fish Species Prediction using Logistic Regression
Project Description:
This project focuses on building a machine learning model that can accurately predict the type of fish based on various physical measurements such as length, weight, height, and width. It uses Logistic Regression, a widely used supervised classification algorithm, and includes hyperparameter tuning to improve model performance.

Objective:
To classify fish into different species (like Bream, Roach, Pike, etc.) using physical features with the help of a logistic regression classifier.
Machine Learning Details:
Algorithm Used: Logistic Regression
Type: Supervised Classification
Dataset: Fish dataset with 7 different species
Features Used:
- Weight
- Length1 (Vertical length)
- Length2 (Diagonal length)
- Length3 (Cross length)
- Height
- Width
Target: Fish Species (Categorical)

Hyperparameter Tuning:
To enhance model performance, GridSearchCV was used for hyperparameter optimization. The tuned parameters include:
C	Regularization strength (inverse)	[0.01, 0.1, 1, 10]
solver	Optimization algorithm	[liblinear]
penalty	Regularization type	[l1, l2]

Model Performance:
- Accuracy: 100%
- Confusion Matrix used to evaluate performance

Streamlit Deployment :
An interactive Streamlit app was created to:
- Accept user inputs (fish measurements)
- Predict and display the fish species in real-time

 Conclusion:
The model successfully classifies fish species using Logistic Regression, showing decent accuracy after tuning. This project demonstrates the power of simple linear models in multi-class classification when paired with effective feature selection and hyperparameter tuning.
