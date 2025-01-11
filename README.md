# Feature Selection and Classification on Human Activity Recognition Dataset 📊

This project demonstrates:
1. **EDA and Preprocessing**: Understanding the dataset and handling redundant features.
2. **Feature Selection via Clustering**: Using KMeans to identify important features.
3. **Classification**: Applying Naive Bayes for activity prediction.

---

## 📂 Features of the Code

- **Dataset**: Human Activity Recognition using smartphones dataset from UCI ML repository.
- **EDA**: Basic exploratory analysis to understand the dataset structure and check for missing values.
- **Feature Reduction**: 
  - KMeans clustering identifies key features to reduce dimensionality.
  - Selected features are used for training a classifier.
- **Classification**:
  - Gaussian Naive Bayes (GNB) is used for model training and prediction.
  - Accuracy and training time are evaluated.

---

## 🛠️ Prerequisites

Install the required Python libraries:

```bash
pip install requests beautifulsoup4 numpy pandas matplotlib scikit-learn
