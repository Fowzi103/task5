Task 5: Decision Trees and Random Forests – Heart Disease Prediction

Objective
The objective of this task is to apply Decision Tree and Random Forest classifiers on a heart disease dataset to predict whether a person has heart disease based on clinical features. This task focuses on:
- Training tree-based models
- Visualizing decision trees
- Evaluating overfitting
- Comparing ensemble learning with a single tree
- Interpreting feature importance

Concepts Learned
- Decision Tree Classifier
- Random Forest Classifier
- Overfitting and tree depth control
- Feature importance
- Cross-validation for model evaluation

Dataset
- Dataset name: `heart.csv`

Tools & Libraries Used
- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (sklearn)

Steps Performed

1. **Loaded the dataset** and explored its structure using `pandas`.
2. **Performed EDA** (checked for nulls, understood class distribution).
3. **Split the data** into training and testing sets.
4. **Trained a Decision Tree Classifier** and visualized it using `plot_tree`.
5. **Evaluated model accuracy** and checked for overfitting by comparing train vs test performance.
6. **Pruned the tree** using `max_depth` to control complexity and reduce overfitting.
7. **Trained a Random Forest Classifier** and compared it with the Decision Tree.
8. **Interpreted feature importances** from the Random Forest.
9. **Evaluated using cross-validation** to check model stability.

Model Performance

| Model               | Accuracy (Test Set) |
|--------------------|---------------------|
| Decision Tree       | ~77%                |
| Pruned Decision Tree| ~81%                |
| Random Forest       | ~85%+               |

