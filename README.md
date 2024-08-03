# MLOps_Group_38_Assignment_1

MLOps_Group_38_Assignment_1

## ML OPS

## ASSIGNMENT – 1

## GROUP – 38

### “MLOps Foundations, Process and Tooling, Model Experimentation and Packaging & Model Deployment & Orchestration”


# Model Experimentation and Packaging Summary

## Description of the Work Completed

We trained a TensorFlow Keras model on the Iris dataset to classify iris species. The workflow involved hyperparameter tuning using GridSearchCV, model training, and packaging the model into a Flask application. The Flask app was then containerized using Docker for easy deployment.

## Justification for the Choices Made

1. **Dataset**: The Iris dataset was chosen due to its simplicity and well-understood features, making it ideal for demonstrating model training and deployment workflows.
2. **Model**: A TensorFlow Keras Sequential model was selected for its flexibility and ease of integration with Scikit-learn for hyperparameter tuning.
3. **Hyperparameter Tuning**: GridSearchCV was used to find the optimal hyperparameters, balancing simplicity and effectiveness for our purposes.
4. **Flask**: Flask was chosen as the web framework for its lightweight and straightforward setup, suitable for serving the model.
5. **Docker**: Docker was utilized to ensure a consistent and reproducible environment for running the Flask application, making it easy to deploy the model across different platforms.

