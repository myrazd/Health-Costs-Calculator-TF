# Health-Costs-Calculator-TF
This repository features a TensorFlow-based linear regression model designed to predict healthcare costs. The model utilizes various features such as age, sex, BMI, number of children, smoker status, and region to estimate healthcare expenses. It is built using TensorFlow's Sequential API with an architecture comprising two dense layers (128 and 64 units, respectively) with ReLU activation functions, followed by a dropout layer for regularization. The model is optimized with the Adam optimizer at a learning rate of 0.0012 and uses mean squared error as the loss function.

Key components include:
• Early Stopping: Monitors validation loss with a patience of 10 epochs to prevent overfitting and restore the best model weights.
• Training: The model is trained over 100 epochs with a validation split of 20% to evaluate performance.

This project is submitted as part of the "Linear Regression Health Costs Calculator" challenge from the "Machine Learning with Python Certification" by freeCodeCamp. The challenge is considered successful if the model achieves an MAE score of less than 3500.

Please note that this notebook is intended as a personal reference to the course materials provided. All credit for the course content and instructional materials goes to the course instructors.
