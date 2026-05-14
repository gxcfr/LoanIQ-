LoanIQ: Loan Approval Prediction System
This project implements a machine learning-based system to predict loan approvals using various classification algorithms. It evaluates model performance through metrics like precision, recall, and accuracy to determine the most effective approach for financial risk assessment.

Project Structure
The repository contains the following core files:

LoanIQ.ipynb: The main Jupyter Notebook containing data exploration, model training, and evaluation.
loan_approval_data.csv: The dataset used for training and testing the classification models.

Model Performance & Evaluation
The system evaluates three primary machine learning models: Logistic Regression, K-Nearest Neighbors (KNN), and Naive Bayes.

1. Logistic Regression Model
This model achieved the highest overall accuracy in this project.

Accuracy: 0.875

Precision: ~0.790

Recall: ~0.803

F1 Score: ~0.796

2. Naive Bayes Model
The Naive Bayes model performed competitively, closely following Logistic Regression in accuracy.

Accuracy: 0.865

Precision: ~0.783

Recall: ~0.770

F1 Score: ~0.776

3. K-Nearest Neighbors (KNN) Model
The KNN model showed lower performance metrics compared to the other two classifiers.

Accuracy: 0.755

Precision: 0.62

Recall: ~0.508

F1 Score: ~0.558

Conclusion
While accuracy is a standard metric, the Precision score is critical in a loan approval context to minimize "False Positives"—instances where a high-risk loan is incorrectly approved.

Logistic Regression remains the top performer, delivering the highest precision of 0.79. This ensures that when the system predicts a loan should be approved, it is correct approximately 79% of the time, offering the best reliability for risk management.

Naive Bayes follows closely with a precision of 0.78, making it a viable alternative for maintaining high standards in approval accuracy.

KNN lagged significantly in this area, with a precision of only 0.62, indicating a higher likelihood of approving potentially risky loans.
