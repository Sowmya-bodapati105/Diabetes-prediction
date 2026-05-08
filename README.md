# Diabetes Prediction App 🩺

A Machine Learning web application built with **Streamlit** that predicts whether a patient is likely to have diabetes based on medical parameters.
The model is trained using the **Gaussian Naive Bayes Algorithm** with preprocessing using **StandardScaler**.

---

## 🚀 Features

* User-friendly Streamlit interface
* Predicts diabetes risk instantly
* Uses Machine Learning pipeline
* Probability score for prediction
* Data preprocessing with StandardScaler
* Model saved using Pickle

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Scikit-learn
* Pandas
* NumPy
* Pickle

---

## 📂 Project Structure

```bash
├── app.py                  # Streamlit web app
├── diabetes_model.pkl      # Saved trained model
├── diabetes.csv            # Dataset
├── train_model.py          # Model training script
├── requirements.txt        # Required libraries
└── README.md               # Project documentation
```

---

## 📊 Dataset

The project uses the famous **Pima Indians Diabetes Dataset**.

### Features Used

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

### Target

* `0` → Non-Diabetic
* `1` → Diabetic

---

## ⚙️ Model Training

The model pipeline includes:

1. **StandardScaler**

   * Normalizes feature values

2. **Gaussian Naive Bayes**

   * Classification algorithm based on probability

---
## 🧠 Example Prediction

Input:

```text
Glucose = 150
BMI = 32.5
Age = 45
```

Output:

```text
Patient is likely diabetic
Risk: 0.82
```
---
## 📦 Requirements

Example `requirements.txt`

```text
streamlit
pandas
numpy
scikit-learn
```
## 🔮 Future Improvements

* Add deployment using Streamlit Cloud
* Improve UI design
* Add more ML algorithms
* Show model accuracy and metrics
* Add data visualization charts
---
## 👩‍💻 Author

Developed by **Venkata Sowmya PadmaSri**
---
## ⭐ If You Like This Project

Give this repository a ⭐ on GitHub!
