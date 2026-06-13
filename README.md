# LJMU_MSDS_C27
## EXPLAINABLE PREDICTION OF DELIVERY TIMELINESS, DELAY SEVERITY AND OPERATIONAL RISK IN E-COMMERCE LOGISTICS USING MACHINE LEARNING MODELS AND SHAP BASED INTERPRETABILITY

This repository contains the implementation developed as part of the MSc Artificial Intelligence and Machine Learning dissertation at Liverpool John Moores University (LJMU).
The project uses the DataCo Smart Supply Chain dataset and develops a multi-task machine learning framework for addressing several logistics prediction problems. In addition to predictive performance, the framework incorporates Explainable Artificial Intelligence (XAI) techniques to provide interpretable insights that support operational decision-making.
---

## Dataset
Dataset: DataCo Smart Supply Chain Dataset

The dataset contains information related to customer orders, products, shipment details, delivery performance, and supply chain operations.
---

## Repository Structure

### Task 1 – Delivery Delay Classification
Objective
Predict whether an order will be delivered on time or late.

Models
 Logistic Regression
 Decision Tree
 Random Forest
 XGBoost
 LightGBM
 CatBoost
 Support Vector Machine (SVM)

Evaluation Metrics
 Accuracy
 Precision
 Recall
 F1-Score
 ROC-AUC
 Cross-Validation Performance

Explainability
 SHAP
 LIME

---

### Task 2 – Delay Duration Prediction
Objective
Predict the expected delivery delay duration using regression models.

Models
 Linear Regression
 Decision Tree Regressor
 Random Forest Regressor
 XGBoost Regressor
 LightGBM Regressor
 CatBoost Regressor
 Support Vector Regressor (SVR)

Evaluation Metrics
 Mean Absolute Error (MAE)
 Root Mean Squared Error (RMSE)
 R² Score
 Cross-Validation Metrics

Explainability
 SHAP
 LIME

---

### Task 3 – Operational Risk Prediction
Objective
Predict whether an order will be Low,Moderate or High Risk

Models
 Logistic Regression
 Decision Tree
 Random Forest
 XGBoost
 LightGBM
 CatBoost
 Support Vector Machine (SVM)

Evaluation Metrics
 Accuracy
 Precision
 Recall
 F1-Score
 ROC-AUC
 Cross-Validation Performance

Explainability
 SHAP
 LIME

---

### Task 4 – Order Processing Delay Prediction
Objective
Task predicts delay during the internal fulfilment stage before final delivery.

Models
 Logistic Regression
 Decision Tree
 Random Forest
 XGBoost
 LightGBM
 CatBoost
 Support Vector Machine (SVM)

Evaluation Metrics
 Accuracy
 Macro Precision
 Macro Recall
 Macro F1-Score
 Weighted F1-Score
 ROC-AUC
 Cross-Validation Performance

Explainability
 SHAP
 LIME
---

### Task 5 – Shipment Mode Prediction and Optimization
Objective
Predict the most suitable shipment mode for customer orders.

Shipment Classes
 First Class
 Same Day
 Second Class
 Standard Class

Models
 Logistic Regression
 Decision Tree
 Random Forest
 XGBoost
 LightGBM
 CatBoost
 Support Vector Machine (SVM)

Evaluation Metrics
 Accuracy
 Macro Precision
 Macro Recall
 Macro F1-Score
 Weighted F1-Score
 Per-Class F1 Scores
 ROC-AUC
 Cross-Validation Performance

Explainability
 SHAP
 LIME
---

## Explainable Artificial Intelligence (XAI)
To improve transparency and support decision-making, the following explainability techniques are employed throughout the framework:

 SHAP (SHapley Additive exPlanations)
 LIME (Local Interpretable Model-Agnostic Explanations)

These methods provide both global and local explanations for model predictions and help identify the factors influencing logistics outcomes.
---

## Tools and Libraries
 Python
 Pandas
 NumPy
 Scikit-learn
 XGBoost
 LightGBM
 CatBoost
 SHAP
 LIME
 Matplotlib
 Seaborn
---

## Author
Rakesh S Gautham
Student ID: 1196243
MSc Artificial Intelligence and Machine Learning
Liverpool John Moores University (LJMU)
March 2026
