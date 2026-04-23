# Heart Disease Prediction App

A Machine Learning web application that predicts the likelihood of heart disease using multiple classification models and provides an interactive interface using Gradio.

---

## Features

* Multiple ML models:

  * Logistic Regression
  * Random Forest
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors (KNN)
* Model comparison using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
  * ROC AUC
* Automatic best model selection
* ROC Curve visualization
* Confusion Matrix
* Feature Importance analysis
* Interactive UI using Gradio

---

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Gradio
* Joblib

---

## Project Structure

```
heart-disease-prediction/
│
├── app.py
├── requirements.txt
├── HeartDiseaseTrain-Test.csv
├── model_comparison.png
├── roc_curve.png
├── confusion_matrix.png
├── feature_importance.png
└── README.md
```

---

## Installation and Setup

### 1. Clone the repository

```
git clone https://github.com/YOUR_USERNAME/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the application

```
python app.py
```

---

## Usage

* Select a model from the dropdown
* Enter patient details
* Click the Predict button
* View prediction results along with probability and model performance

---

## Output

The application generates:

* Model comparison chart
* ROC curve
* Confusion matrix
* Feature importance graph

---

## Objective

To build a machine learning system that compares multiple models, selects the best-performing model, and provides real-time predictions through a user-friendly interface.

---

## Future Improvements

* Deploy as a web application using platforms like Hugging Face or Render
* Add more datasets for improved accuracy
* Enhance user interface and user experience
* Integrate deep learning models

---

## Author

Your Name

---

## License

This project is for educational purposes.
