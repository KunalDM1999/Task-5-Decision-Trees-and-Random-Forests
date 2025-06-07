# Task-5-Decision-Trees-and-Random-Forests

1. Data and Target:
Dataset has 2000 samples and 21 numerical features related to mobile phone attributes (e.g., battery power, RAM, screen size). The target variable is price_range, a multiclass label with 4 classes (0 = low cost to 3 = high cost).

2. Train-Test Split:
Performed a fixed random split on the dataset to create training and testing subsets, ensuring all target classes are present.

3. Models Trained:
Decision Tree and Random Forest classifiers were trained to predict the price range.

4. Overfitting Analysis:
Analyzed overfitting in Decision Tree by varying max_depth to find the best depth balancing train and test accuracy.

5. Feature Importance:
Extracted feature importance from both models to identify which features most influence the target prediction.

6. Feature Reduction:
Removed features with very low importance (importance < 0.01) and retrained models on the reduced feature set.

7. Evaluation Metrics:
Used accuracy, precision, recall, F1-score, and confusion matrix to evaluate models on both training and test data.

8. Hyperparameter Tuning:
Applied best hyperparameters for each model (Decision Tree and Random Forest) based on previous tuning results.

9.Cross-validation:
Used cross-validation to validate model stability and performance consistency.

10. Tools and Libraries Used:
Pandas, Scikit-learn (models, metrics, train_test_split, RandomizedSearchCV), Matplotlib, and Seaborn for visualization.
