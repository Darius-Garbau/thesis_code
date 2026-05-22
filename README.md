Decoding clinical intuition: An Explainable AI approach to predicting multi-factorial nutritional deficiencies.

This thesis explores the prediction of multiple nutritional deficiencies simultaneously using a multi-label classification approach. Three machine learning models were trained and compared: 
Random Forest, XGBoost, and MLP. Each model was evaluated using 5-fold cross-validation across metrics including Macro F1, Macro Recall, Subset Accuracy, Macro Precision, and Hamming Loss.
To explain the predictions, SHAP was applied to all three models using TreeExplainer for Random Forest and XGBoost, and KernelExplainer for MLP. The resulting feature importance rankings were 
compared against clinical frameworks, ESPEN and WHO, using Spearman rank correlation, in order to assess how well data-driven explanations align with established clinical knowledge 
and whether the models uncover novel risk factors not currently prioritized by clinical guidelines.
