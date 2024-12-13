## Q1) What is the Bias-Variance Tradeoff?

The bias-variance tradeoff is a concept that explains how well a model fits the data for prediction.

### Bias
- **Bias** refers to the difference between the average prediction of the model and the true value being predicted.
  - **Low bias**: The model is well-fitted to the data, leading to accurate predictions.
  - **High bias**: The model is poorly fitted to the data, resulting in inaccurate predictions. This is often a case of **underfitting**.

### Variance
- **Variance** refers to how much the model's predictions change when trained on different subsets of data.
  - **Low variance**: The model’s predictions are stable and do not fluctuate significantly.
  - **High variance**: The model is sensitive to specific training data, leading to large fluctuations in predictions. This is often a case of **overfitting**.

<img width="557" alt="image" src="https://github.com/user-attachments/assets/de0fdf81-5a0d-4932-9de4-7cfaa193faf0" />


## Q2) How to Address the Bias-Variance Tradeoff?

### If the Model is Underfitted (High Bias):
- **Fit a more complex model**: For example, use tree-based models or other algorithms capable of capturing complex relationships in the data.
- **Hyperparameter tuning**: Use techniques like cross-validation to optimize hyperparameters and improve model performance.

### If the Model is Overfitted (High Variance):
- **Apply regularization**: Use techniques such as:
  - **L1 regularization (Lasso)**: Helps by shrinking less important features to zero, effectively performing feature selection.
  - **L2 regularization (Ridge)**: Penalizes large coefficients to reduce model complexity.
- **Simplify the model**: Reduce model complexity by limiting the depth of a tree, the number of features, or using simpler algorithms.
- **Increase training data**: Adding more data helps the model generalize better.


