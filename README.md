Data Exploration:
You’ve loaded a CSV file named ‘add.csv’ into a Pandas DataFrame called data.
The DataFrame contains three columns: ‘x’, ‘y’, and ‘sum’.
There are no missing values in the dataset.
You’ve visualized the relationship between ‘x’ and ‘sum’ as well as ‘y’ and ‘sum’ using scatter plots.

Model Training:
You split the data into training and test sets (80% training, 20% test).
You trained a linear regression model (lr_model) on the training data.

Model Evaluation:
The model achieved a perfect score of 1.0 on both the training and test data.
You compared the predicted values (y_pred) with the actual test values (y_test).

Predictions:
You made predictions for a test input of [10, 20], resulting in a predicted sum of 30.

Model Persistence:
You saved the trained model using joblib.dump() and loaded it back using joblib.load().

GUI Application:
You’ve created a simple Tkinter GUI that takes two input numbers and predicts their sum using the trained model.
