# Large-Scale Anomaly Detection in Transaction Data (China Dataset)

## 📌 Project Overview

This project presents an **advanced Machine Learning and Data Analysis pipeline** for detecting anomalies in a large-scale transactional dataset collected from China.

The primary objective is to distinguish between **normal and suspicious behavior** by leveraging statistical analysis, feature engineering, and supervised/unsupervised Machine Learning models.

The project emphasizes the full data science workflow: from raw data exploration to feature vector construction, model training, evaluation, and visualization of results.

---

## 📊 Dataset Description

- The dataset is a **large-scale, real-world transactional dataset** originating from China.
- It contains a high volume of records with multiple behavioral and transactional attributes.
- Due to its size, the dataset is processed in **Google Colab** rather than stored locally.
- The dataset is highly complex and potentially imbalanced, making it suitable for anomaly detection tasks.

---

## 🔎 Exploratory Data Analysis (EDA)

A deep **data-driven analysis** was performed to understand the structure and behavior of the dataset:

- Distribution analysis of key features
- Identification of outliers and rare events
- Correlation analysis between variables
- Detection of imbalanced class behavior (normal vs anomaly)
- Statistical summary of transactional patterns

📌 Extensive **visualizations** were used, including:
- Histograms and density plots
- Boxplots for outlier detection
- Heatmaps for feature correlations
- Class distribution charts

These visualizations were essential for understanding hidden structures in the data.

---

## 🧠 Feature Engineering & Feature Vector Construction

A key part of the project is the transformation of raw data into a **structured feature vector representation** suitable for Machine Learning models.

This process included:

- Converting raw transactional attributes into numerical representations
- Encoding categorical variables
- Scaling and normalization of features
- Construction of a **feature vector space** representing each transaction
- Enhancing signal-to-noise ratio for anomaly detection

The resulting feature space enabled the model to better capture patterns of suspicious behavior.

---

## 🤖 Machine Learning Pipeline

The project applies Machine Learning techniques to classify transactions as:

- Normal behavior
- Anomalous / suspicious behavior

### Data Split Strategy:
- **80% training set**
- **20% test set**

### Models applied:
- Supervised classification models (e.g., Random Forest / Logistic Regression)
- Anomaly detection approaches (depending on experiment setup)

### Objective:
To learn a decision boundary that separates normal patterns from rare anomalous behavior in a high-dimensional feature space.

---

## 📈 Model Evaluation

Model performance was evaluated using standard classification metrics:

- Accuracy
- Precision
- Recall (critical for anomaly detection)
- F1-score

Special emphasis was placed on:
- Reducing **false negatives** (missed anomalies)
- Ensuring robustness on unseen test data

---

## 📊 Visualization of Results

Visualization played a key role in interpreting model behavior:

- Confusion matrix analysis
- Feature importance plots
- Distribution comparison between predicted classes
- Visualization of anomaly separation in feature space

These visual tools helped validate the model’s ability to distinguish between normal and suspicious transactions.

---

## 🧰 Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Google Colab

---

## 🚀 How to Run

1. Open the project notebook in Google Colab
2. Install dependencies if needed:
```bash
pip install -r requirements.txt
