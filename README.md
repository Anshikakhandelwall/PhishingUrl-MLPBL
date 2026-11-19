# 🔐 Phishing URL Detector
### Machine Learning-Based Phishing Website Detection with Explainable Predictions

A machine learning-powered web application designed to identify potentially malicious URLs and distinguish them from legitimate websites using URL-based features.

The system not only predicts whether a URL is **Phishing** or **Legitimate**, but also aims to provide understandable explanations of the factors influencing the prediction.

## 📌 Project Overview

Phishing is one of the most common cybersecurity threats, where attackers create fraudulent websites to steal sensitive information such as passwords, banking credentials, and personal data.

Traditional URL blacklists may struggle to identify newly created phishing websites.

The **Phishing URL Detector** addresses this challenge by applying machine learning techniques to analyze URL characteristics and identify potentially suspicious patterns.

The project focuses on building an accessible, interpretable, and practical phishing detection system.

## 🎯 Objectives

- Develop a machine learning model to classify phishing and legitimate URLs.
- Analyze URL characteristics associated with phishing attacks.
- Evaluate model performance using multiple classification metrics.
- Provide interpretable predictions to help users understand potential security risks.
- Build an interactive web application for real-time URL analysis.
- Promote cybersecurity awareness through understandable detection results.

## ✨ Key Features

**🔍 URL Classification**

Predicts whether a submitted URL is potentially phishing or legitimate.

**🧠 Machine Learning Detection**

Uses trained machine learning algorithms to recognize suspicious URL patterns.

**📊 Feature-Based Analysis**

Examines relevant URL characteristics to support phishing detection.

**💡 Explainable Predictions**

Provides insights into the factors contributing to the model's classification.

**🌐 Interactive Web Application**

Offers a simple interface where users can enter a URL and view prediction results.

**📈 Model Evaluation**

Evaluates detection performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Data Visualization | Matplotlib, Seaborn |
| Development Environment | Google Colab / Jupyter Notebook |
| Web Application | Streamlit |
| Version Control | Git, GitHub |

## 📂 Dataset

The project uses the **PhiUSIIL Phishing URL Dataset**, which contains examples of legitimate and phishing URLs along with features useful for classification.

The dataset supports the analysis of URL structure and other website-related characteristics.

**Dataset Source:** [PhiUSIIL Phishing URL Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/967/phiusiil+phishing+url+dataset)

## ⚙️ System Workflow

The phishing detection system follows these steps:

**Step 1 — URL Input**

The user enters a website URL into the Streamlit application.

**Step 2 — Feature Extraction**

Relevant URL characteristics are extracted and prepared for model processing.

**Step 3 — Data Preprocessing**

Input features are transformed according to the preprocessing steps used during model training.

**Step 4 — Machine Learning Prediction**

The trained classification model analyzes the features and predicts whether the URL is phishing or legitimate.

**Step 5 — Prediction Explanation**

The system presents the prediction alongside available information about influential URL characteristics.

**Step 6 — Result Display**

The user receives a classification result through the web interface.

## 📊 Model Evaluation

The machine learning model is evaluated using several performance metrics.

| Evaluation Metric | Purpose |
|---|---|
| Accuracy | Measures overall classification correctness |
| Precision | Measures the reliability of positive predictions |
| Recall | Measures the ability to identify phishing URLs |
| F1-Score | Balances precision and recall |
| Confusion Matrix | Shows correct and incorrect classifications |



## 🖥️ Web Application

The project includes a Streamlit-based interface for phishing URL detection.

Users can:

1. Enter a website URL.
2. Submit it for analysis.
3. View the predicted classification.
4. Examine the available explanation of the prediction.



### Prediction Results

*Insert screenshots showing phishing and legitimate URL predictions.*

<img width="648" height="148" alt="image" src="https://github.com/user-attachments/assets/839802a5-820b-4780-9f35-f14d9ea83345" />



## 🔮 Future Enhancements

- Integrate additional threat intelligence sources.
- Improve detection of newly emerging phishing techniques.
- Develop a browser extension for convenient URL checking.
- Introduce more detailed feature-level explanations.
- Evaluate model performance on newer and independently collected URLs.
- Strengthen detection against adversarially modified phishing URLs.

## ⚠️ Limitations and Disclaimer

This project is intended for educational, research, and cybersecurity awareness purposes.

Machine learning predictions are probabilistic and may contain false positives or false negatives. A URL classified as legitimate is not guaranteed to be safe.

Performance on a benchmark dataset may not represent real-world performance against newly created or previously unseen phishing attacks.

The detector should be used as an additional security aid rather than a replacement for established cybersecurity practices.

## 👩‍💻 Author

**Anshika Khandelwal**  
B.Tech — Computer Science Engineering (Artificial Intelligence & Machine Learning)

**Areas of Interest:** Machine Learning | Artificial Intelligence | Cybersecurity | Data Analytics

---

⭐ If you find this project useful, consider giving the repository a star!

*Building smarter and more understandable cybersecurity solutions using Machine Learning.*
