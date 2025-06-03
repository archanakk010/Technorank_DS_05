# Enhancing Bank Marketing Model Performance through Feature Engineering and Selection

This project aims to predict whether a client will subscribe to a term deposit using data from a Portuguese banking institution. It involves preprocessing, feature engineering, feature selection, and training of various classification models. Emphasis is placed on improving performance through ensemble models and hyperparameter tuning.

---

##  Overview

This project focuses on predicting whether a bank client will subscribe to a term deposit based on various demographic and campaign-related features. Using the Bank Marketing dataset, the analysis includes comprehensive exploratory data analysis, feature engineering, feature selection, and the application of multiple machine learning models.

---

##  Objective

- Improve model accuracy and generalization using robust preprocessing and feature selection.
- Apply and compare multiple classification algorithms.
- Optimize the best-performing model using hyperparameter tuning.
- Interpret and visualize results using key evaluation metrics like Accuracy, Precision, Recall, F1-Score, and ROC AUC.

---

##  Dataset Source

- [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

---

##  Libraries Used


- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- 

##  Result

Among all the models tested, the **Gradient Boosting Classifier** demonstrated the **highest test accuracy (0.9047,)** and **ROC AUC (0.9232)**, indicating strong predictive power. After applying **hyperparameter tuning**, its performance was further enhanced **highest test accuracy ( 0.9058,)**, confirming it as the most effective model for this classification task.

---

##  Conclusion

The project highlights the importance of proper data preprocessing, feature selection, and model tuning in building high-performing machine learning models. Ensemble methods, particularly **Gradient Boosting**, outperformed other models due to their ability to reduce bias and variance. Hyperparameter tuning played a critical role in optimizing model performance, making the final model both accurate and reliable for real-world predictions.


