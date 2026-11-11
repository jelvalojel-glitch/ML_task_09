# Practical Work No. 9 — Support Vector Machine (SVM)

## Objective

To investigate the influence of kernel functions and hyperparameters C and gamma on the performance of an SVM classifier.

## Dataset

**Healthcare Stroke Prediction Dataset**

- File: `healthcare-dataset-stroke-data.csv`
- Number of records: 5110
- Target variable: `stroke`
- Problem type: Binary classification

## Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Implementation

1. Load and explore the dataset.
2. Separate features and target variable.
3. Split the dataset into training and testing sets.
4. Handle missing values.
5. Encode categorical features.
6. Scale numerical features using StandardScaler.
7. Create an SVM Pipeline.
8. Perform Grid Search with cross-validation.
9. Investigate the influence of C and gamma.
10. Visualize results using a heatmap.
11. Compare RBF and Linear SVM kernels.
12. Compare SVM with Random Forest and Gradient Boosting from previous practical works.
13. Visualize the decision boundary using the make_moons dataset.
14. Evaluate model performance and training time.

## Hyperparameters

The following parameters are investigated:

| Parameter | Values |
|---|---|
| C | 0.1, 1, 10, 100 |
| Gamma | scale, 0.01, 0.1, 1 |
| Kernel | RBF, Linear |

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Training time

## Results

The best hyperparameters are selected using Grid Search and cross-validation.

Model performance is evaluated on the test dataset and compared with previous classification models.

## Conclusion

The practical work demonstrates how SVM hyperparameters and kernel functions affect classification performance. It also evaluates whether SVM is an appropriate choice for the healthcare stroke prediction dataset, considering classification quality and computational time.
