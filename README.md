# CDC-Diabetes-Health-Indicators-UCI-Machine-Learning
This lab applies nonlinear models (RBF, Perceptron, MLP) to the CDC Diabetes dataset. After preprocessing and splitting the data, models are trained, tuned, and evaluated using accuracy, precision, recall, and F1-score, then compared with linear results.


Diabetes is one of the most significant chronic diseases worldwide, requiring effective prediction and prevention strategies to reduce health risks and improve patient outcomes. The CDC Diabetes Health Indicators dataset from the UCI Machine Learning Repository provides a rich set of health, demographic, and lifestyle factors that can be leveraged to build predictive models.

This task focuses on applying nonlinear machine learning models to the dataset, aiming to improve prediction accuracy compared to simple linear approaches. The workflow begins with careful data preprocessing, including handling missing values, encoding categorical features, and splitting the dataset into training, validation, and test subsets.

Three models are implemented and studied in detail:
1. Radial Basis Function (RBF) network, which captures nonlinear relationships through kernel-based transformations.
2. Perceptron, representing a simple neural network model for classification.
3. Multi-Layer Perceptron (MLP), a more advanced neural network capable of modeling complex patterns.

Each model is trained, optimized, and evaluated using metrics such as accuracy, precision, recall, and F1-score. Learning curves are plotted to examine convergence behavior and identify overfitting or underfitting. Finally, results are compared with previous linear models to highlight improvements in predictive performance, the effect of regularization, and the advantages of nonlinear approaches in healthcare data analysis.
