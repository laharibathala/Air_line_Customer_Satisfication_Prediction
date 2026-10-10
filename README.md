# ✈️ Airline Passenger Satisfaction Prediction Using ANN

## 📌 Project Overview

This project aims to predict airline passenger satisfaction using an **Artificial Neural Network (ANN)**, a deep learning technique. The model analyzes passenger demographics, flight information, travel class, delays, and service ratings to classify passengers into two categories: **Satisfied** and **Neutral or Dissatisfied**.

The project uses Python for data preprocessing, exploratory data analysis (EDA), model development, training, and evaluation. A trained ANN model is also prepared for deployment through a **Streamlit web application**, allowing users to enter passenger details and obtain a satisfaction prediction.

## 🎯 Objectives

- Analyze airline passenger satisfaction data.
- Perform data cleaning and preprocessing.
- Handle missing values and encode categorical variables.
- Perform exploratory data analysis and visualization.
- Build and train an ANN classification model.
- Evaluate model performance using classification metrics.
- Develop an interactive Streamlit application for predictions.

## 📊 Dataset Description

- **Dataset:** Airline Passenger Satisfaction
- **Total Records:** 103,904
- **Original Columns:** 25
- **Target Variable:** `satisfaction`
- **Problem Type:** Binary Classification

The target variable contains two classes:
- Satisfied
- Neutral or Dissatisfied

The dataset includes passenger details, travel information, flight delays, and airline service ratings.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning Utilities:** Scikit-learn
- **Deep Learning:** TensorFlow, Keras
- **Web Application:** Streamlit
- **Development Environment:** Jupyter Notebook

## ⚙️ Project Workflow

1. Dataset loading and understanding
2. Data cleaning and missing-value handling
3. Categorical feature encoding
4. Exploratory Data Analysis (EDA)
5. Train-test split
6. Feature scaling using StandardScaler
7. ANN model development
8. Model training and validation
9. Model evaluation
10. Saving the trained model and preprocessing artifacts
11. Streamlit application development

## 🧠 ANN Model Architecture

The model uses the following architecture:

- Input layer
- Dense layer with 64 neurons and ReLU activation
- Dropout layer with a rate of 30%
- Dense layer with 32 neurons and ReLU activation
- Dropout layer with a rate of 20%
- Dense layer with 16 neurons and ReLU activation
- Output layer with 1 neuron and Sigmoid activation

### Model Training Configuration

- **Optimizer:** Adam
- **Loss Function:** Binary Crossentropy
- **Epochs:** 30
- **Batch Size:** 32
- **Validation Split:** 20%

## 📈 Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 96.14% |
| Test Loss | 0.0891 |

The model achieved **96.14% test accuracy** on the held-out test dataset.

## 🌐 Streamlit Application

The project includes a Streamlit interface designed to:

- Collect passenger and flight-service information.
- Process the input using the saved preprocessing artifacts.
- Generate an ANN-based satisfaction prediction.
- Display the predicted class and satisfied-class probability.

## 📁 Project Structure

```text
Airline-Passenger-Satisfaction-ANN/
│
├── app.py
├── ann_model.keras
├── scaler.pkl
├── feature_columns.pkl
├── arrival_delay_median.pkl
├── requirements.txt
├── README.md
└── notebook/
    └── airline_satisfaction.ipynb
```

*Adjust the structure to match the files you actually upload to GitHub.*

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Airline-Passenger-Satisfaction-ANN
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser.

## 🔮 Future Scope

- Perform hyperparameter tuning to improve model performance.
- Experiment with different ANN architectures.
- Analyze additional passenger and flight features.
- Compare ANN performance with other classification algorithms.
- Deploy the application using Streamlit Community Cloud or another hosting platform.

## ✅ Conclusion

This project demonstrates how deep learning can be applied to airline passenger satisfaction prediction. The ANN model achieved 96.14% test accuracy, and the Streamlit application provides an interactive interface for generating predictions.

The project combines data preprocessing, exploratory data analysis, neural network development, model evaluation, and web application deployment in an end-to-end data science workflow.

## 👩‍💻 Author

**B. Lahari**

Project: Airline Passenger Satisfaction Prediction Using ANN
