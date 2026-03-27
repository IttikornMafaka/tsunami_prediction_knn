# 🌍 Earthquake Tsunami Prediction using KNN

## 📌 Project Overview

This project aims to analyze earthquake data and predict whether an earthquake will generate a tsunami using the K-Nearest Neighbors (KNN) algorithm.

The model is trained on real-world earthquake data and focuses on identifying patterns between earthquake characteristics (e.g., magnitude, depth, location) and tsunami occurrence.

---

## 🎯 Objectives

* Analyze earthquake data (EDA)
* Identify relationships between earthquake features and tsunami occurrence
* Build a classification model using KNN
* Evaluate model performance using multiple metrics

---

## 📊 Dataset

The dataset contains information about earthquake events, including:

* Magnitude
* Depth
* Latitude & Longitude
* Significance (sig)
* MMI (Modified Mercalli Intensity)
* Tsunami (target variable: 0 = No, 1 = Yes)

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Selected relevant features
* Handled missing values
* Applied feature scaling (StandardScaler)

### 2. Model

* Algorithm: K-Nearest Neighbors (KNN)
* Tuned different values of K to find optimal performance

### 3. Train/Test Split

* 80% training / 20% testing

---

## 📈 Model Performance

| Metric              | Score |
| ------------------- | ----- |
| Accuracy            | 0.83  |
| Precision (Tsunami) | 0.77  |
| Recall (Tsunami)    | 0.82  |
| F1-score            | 0.79  |

### 🔍 Key Insight

* The model achieves good overall performance with balanced precision and recall.
* Recall is emphasized due to the importance of detecting tsunami events.
* Some misclassifications occur in medium-magnitude earthquakes.

---

## 📊 Visualization

* Scatter plots (magnitude vs depth)
* Histogram & boxplot for distribution analysis
* Confusion matrix for model evaluation
* Misclassification visualization

---

## 🧠 Conclusion

The results indicate that earthquake features such as magnitude and depth have predictive power for tsunami occurrence.

Although the model performs well (83% accuracy), overlapping patterns in the data suggest that additional features may further improve prediction performance.

---

## 🚀 Future Improvements

* Try other models (e.g., Decision Tree, Random Forest)
* Feature engineering (e.g., distance from coast)
* Hyperparameter tuning
* Use larger datasets

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib 

---
