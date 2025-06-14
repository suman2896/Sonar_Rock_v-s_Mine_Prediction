# Sonar Rock vs Mine Prediction 🧭

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Jupyter-lightgrey.svg)](https://jupyter.org/)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)]()

A machine learning project that classifies underwater objects—rocks or naval mines—based on SONAR data using logistic regression.

---

## 🔍 Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Model](#model)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Evaluation](#evaluation)  
- [Future Work](#future-work)   
- [Contributing](#contributing)  

---

## 📌 Overview

This project aims to classify whether a given SONAR signal has bounced off a rock or a mine. It uses a logistic regression model trained on the UCI SONAR dataset. This implementation demonstrates preprocessing, model training, evaluation, and prediction steps, making it a good educational example of binary classification.

---

## 📊 Dataset

- **Source:** UCI Machine Learning Repository  
- **Samples:** 208 instances  
- **Features:** 60 numerical attributes representing signal energy at different frequencies  
- **Label:** `R` for Rock, `M` for Mine  
- **Format:** CSV

---

## 🧠 Model

- **Algorithm Used:** Logistic Regression  
- **Reason:** Simple and interpretable algorithm for binary classification  
- **Libraries:**  
  - pandas  
  - numpy  
  - scikit-learn  
- **Steps:**  
  - Load and explore dataset  
  - Preprocess and encode labels  
  - Train/test split  
  - Train logistic regression model  
  - Evaluate and test accuracy

---

## ⚙️ Installation

1. Clone the repository

   `git clone https://github.com/suman2896/Sonar_Rock_v-s_Mine_Prediction.git`

2. Navigate to the project directory

   `cd Sonar_Rock_v-s_Mine_Prediction`

3. Install dependencies

   `pip install -r requirements.txt`

   Or manually:

   `pip install pandas numpy scikit-learn`

---

## 🚀 Usage

1. Open the notebook:

   `jupyter notebook rock_mine_detection.ipynb`

2. Follow the step-by-step instructions to:

   - Load and inspect the dataset  
   - Train the model  
   - Evaluate on test data  
   - Try predictions with your own custom inputs

---

## 📐 Evaluation

- **Train/Test Split:** 75% training, 25% testing  
- **Accuracy:** ~80% (may vary slightly on each run)  
- **Metrics Used:**  
  - Accuracy  
  - Confusion Matrix  
  - Precision & Recall  
  - F1 Score

---

## 🔭 Future Work

- Test additional classifiers (e.g., SVM, KNN, Random Forest)  
- Add hyperparameter tuning (GridSearchCV)  
- Improve visualizations (ROC curve, confusion matrix heatmap)  
- Deploy the model using Streamlit or Flask for web-based prediction

---


## 🤝 Contributing

Contributions are welcome! Follow these steps:

1. Fork this repository  
2. Create a new branch (`git checkout -b feature/my-feature`)  
3. Make your changes and commit (`git commit -m 'Add new feature'`)  
4. Push to the branch (`git push origin feature/my-feature`)  
5. Create a new Pull Request


