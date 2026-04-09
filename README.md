# Confusion Matrix & AUC Calculation from Scratch 📊
This project was developed as the Machine Learning course Master's Lab project, focused on understanding and implementing fundamental classification evaluation metrics from scratch. Instead of relying solely on built-in scikit-learn functions, we manually calculated the Confusion Matrix, Classification Report (Precision, Recall, F1-Score, Specificity, Accuracy), and AUC-ROC curves to gain a deeper understanding of how these metrics work internally.

The project uses a Random Forest classifier on a mobile phone price classification dataset to predict price ranges (0-3) based on device specifications.

# Project Objectives 🎯
- Implement a Random Forest classifier using One-vs-Rest strategy for multiclass classification
- Calculate Confusion Matrix manually using nested loops and matrix operations
- Derive Classification Report metrics from scratch: Accuracy, Precision, Recall (Sensitivity), Specificity, F1-Score
- Compute AUC-ROC curves manually by iterating over thresholds and calculating TPR/FPR
- Validate custom calculations against scikit-learn's built-in functions
- Visualize results using heatmaps and ROC curves

# Libraries Used 🛠️
- **pandas:**	Data manipulation and analysis
- **numpy:**	Numerical operations and matrix calculations
- **scikit-learn**	Random Forest model, data preprocessing, validation
- **matplotlib:**	ROC curve plotting
- **seaborn:**	Confusion matrix heatmap visualization

# Lessons Learned 💡
- **Deep understanding of evaluation metrics:** Implementing metrics from scratch revealed the mathematical relationships between TP, FP, TN, FN and derived metrics.
- **Multiclass evaluation challenges:** One-vs-Rest strategy is essential for extending binary metrics to multiclass problems.
- **Threshold impact on ROC:** Different probability thresholds change the trade-off between TPR and FPR significantly.
- **Validation is crucial:** Comparing custom implementations with sklearn's built-in functions confirmed our calculations were correct.
- **Visualization aids interpretation:** Heatmaps and ROC curves provide intuitive understanding of model performance across classes.
- **Class imbalance effects:** Some classes (especially class 1 and 2) showed lower precision and recall, indicating room for improvement.

 # License 📝
  This project is for educational purposes as part of a Master's lab assignment.

# Contact ✉️
 • **Email:** wissambadia4@gmail.com
 • **LinkedIn:** [Badia Ouissam Lakas](linkedin.com/in/badia-ouissam-lakas-a66a28214) 
