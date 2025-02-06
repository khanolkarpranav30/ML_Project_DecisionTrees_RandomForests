# ML_Project_DecisionTrees_RandomForests
Decision Trees and Random Forests

The goal of this project is to predict whether a bank loan application will be approved based on customer data such as income, credit history, loan amount, and other financial indicators. We use Machine Learning algorithms, specifically Decision Trees and Random Forests, to build predictive models and evaluate their performance.

🌳 1. Decision Trees
A Decision Tree is a supervised learning algorithm that can be used for both classification and regression tasks. It splits the data into smaller subsets based on feature values and makes predictions by traversing from the root node to a leaf node.

How it works:

Each internal node represents a decision based on a feature.
Branches represent the outcomes of these decisions.
Leaf nodes represent the final prediction or output.
Advantages of Decision Trees:

Easy to understand and interpret
Handles both numerical and categorical data
Requires little data preprocessing
However, decision trees are prone to overfitting, especially on small datasets.

🌲 2. Random Forests
Random Forest is an ensemble learning method that combines multiple decision trees to improve accuracy and prevent overfitting. It builds several trees during training and averages their predictions for more reliable and robust results.

How it works:

Randomly selects subsets of features and data samples to train each tree.
Each tree makes its own prediction.
The final prediction is determined by majority vote (for classification) or averaging (for regression).
Advantages of Random Forests:

Reduces overfitting compared to a single decision tree
Handles large datasets with higher dimensionality
Robust to noise and missing data
