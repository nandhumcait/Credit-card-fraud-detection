Credit Card Fraud Detection

Data inception:
In this project, I used a credit card transactions dataset containing over 280,000 records. 
The data includes anonymized features (V1 to V28) generated through PCA, along with Amount and Time. 
Each transaction is labeled as fraudulent (1) or not fraudulent (0). Since the dataset is highly imbalanced, 
careful preprocessing and evaluation were necessary to build an effective fraud detection model.

This project uses **Logistic Regression** to detect fraudulent credit card transactions. The dataset is highly imbalanced, so proper scaling and evaluation are applied.

- Loaded and explored the dataset
- Scaled features using StandardScaler
- Trained a Logistic Regression model
- Evaluated using accuracy, confusion matrix, and classification report

Results
- Accuracy: ~99%
- Evaluation includes precision, recall, and F1-score
- Confusion matrix visualized using Seaborn

Tools
- Python, pandas, scikit-learn, matplotlib, seaborn
