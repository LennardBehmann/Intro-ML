Homework 6: Fully Connected Neural Networks (100 Points)
In this homework, you will develop Fully Connected Neural Networks (FCNNs) for regression and classification problems using the Housing and Breast Cancer datasets from previous homeworks.

You will compare the performance of neural networks against traditional machine learning algorithms, including Linear Regression, Logistic Regression, Support Vector Regression (SVR), and Support Vector Machines (SVMs).

You may use built-in machine learning and deep learning libraries such as PyTorch, TensorFlow/Keras, and Scikit-learn.

For all problems, use an 80% training and 20% testing split. Make sure to perform appropriate input normalization or standardization before training.

Problem 1: Housing Price Prediction (50 Points)
Using the US Housing dataset from Homework 2, develop a fully connected neural network to predict housing prices using all available input features.

1.a) Neural Network Development (30 Points)

Develop and train a fully connected neural network using all input features from the Housing dataset.

Your neural network should include at least two hidden layers. You can experiment with the number of neurons, activation functions, learning rate, batch size, and training epochs to achieve the best performance.

Perform appropriate input normalization or standardization before training.

Plot the training and validation losses over epochs in a single graph. Report the final performance of your model using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.

Explain your selected neural network architecture and hyperparameters.

1.b) Comparison with Traditional Machine Learning (20 Points)

Compare your neural network results against Linear Regression and Support Vector Regression (SVR).

You may reuse your Linear Regression implementation from Homework 2 and use Scikit-learn for SVR.

Report and compare the test performance of all three models using MSE, RMSE, and R² score.

Which model performs best? Does the neural network outperform traditional regression methods? Explain your results.

Problem 2: Breast Cancer Classification (50 Points)
Using the Breast Cancer dataset from Homework 3, develop a fully connected neural network to classify cancer as malignant or benign using all 30 input features.

2.a) Neural Network Development (30 Points)

Develop and train a fully connected neural network using all 30 input features.

Your neural network should include at least two hidden layers. You can experiment with the number of neurons, activation functions, learning rate, batch size, and training epochs.

Perform appropriate input normalization or standardization before training.

Plot the training and validation losses and classification accuracy over epochs.

Report the classification performance of your neural network using accuracy, precision, recall, and F1 score. Plot the confusion matrix.

Explain your selected neural network architecture and hyperparameters.

2.b) Comparison with Traditional Machine Learning (20 Points)

Compare your neural network results against Logistic Regression and Support Vector Machines (SVMs).

You may reuse your Logistic Regression implementation from Homework 3 and use Scikit-learn for SVM.

Report and compare the test classification performance of all three models using accuracy, precision, recall, and F1 score.

Which model provides the best classification performance? Does the neural network outperform Logistic Regression and SVM? Explain your results.

Homework Instructions
You will submit: (1) a report (PDF file) that explains your answers for each problem. The report MUST contain the link to your GitHub repository to access the source code you have developed for this homework. Your report should contain your name, student ID, and homework number. (2) a second PDF file that contains the source code, results, and plots you have developed for this homework. You can generate this PDF in Jupyter Lab or Jupyter Notebook. The PDF filenames should contain your name, student ID, and homework number.
In your report, provide separate and clear responses for each problem. Make reasonable assumptions where necessary and clearly state them. Explain your neural network architecture, selected hyperparameters, and experimental results. If you provide only final answers without explanation, you may not receive full credit.
Use the same training and testing split for all models within each problem to ensure fair comparisons. Fit preprocessing transformations using the training data only, and reserve the test set for final evaluation.
You may use built-in machine learning and deep learning libraries for training, optimization, and evaluation.
