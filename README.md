Here's the updated `README.md` file for your project, incorporating instructions on how to activate the virtual environment and run the project:

---

# 🩺 Medication Advisory System using Machine Learning

Welcome to the **Medication Advisory System using Machine Learning**! This system uses machine learning to predict diseases based on symptoms and recommends suitable treatments, designed to assist in rapid preliminary diagnosis.

---

## 📋 Project Overview

This project aims to create a machine learning model that can:

- 🧩 Predict diseases based on input symptoms
- 💡 Provide relevant medical recommendations
- 🧪 Offer a user-friendly interface for healthcare support

## 🚀 Key Features

- **Symptom-Based Disease Prediction:** Predicts potential diseases from a set of symptoms.
- **Machine Learning Models Implemented:** Support Vector Classifier (SVC), Random Forest, Gradient Boosting, K-Nearest Neighbors, and Multinomial Naive Bayes.
- **Model Evaluation Metrics:** Confusion Matrix and Accuracy Score.
- **Trained Model Persistence:** Save and load the model for future predictions.

## 🛠️ Setup and Installation

### Prerequisites

Ensure you have the following libraries installed:

```bash
pip install pandas scikit-learn numpy
```

### Files and Directories

- `Training.csv`: Training dataset with symptoms and respective diseases.
- `svc.pkl`: Saved model file for making predictions.

## 📂 Directory Structure

```plaintext
├── Training.csv                  # Dataset file
├── svc.pkl                       # Trained model file
├── README.md                     # Project documentation
├── venv                          # Virtual environment directory
└── main.py                       # Main script to run the project
```

## ▶️ How to Run the Project

1. **Navigate to the project folder**.
   - Right-click inside the folder and select **Open PowerShell**.

2. **Activate the virtual environment**:
   ```bash
   ./venv/Scripts/activate
   ```

3. **Run the main script**:
   ```bash
   python main.py
   ```

## 📊 Model Performance

The model was tested with various classifiers to find the best-performing one. Below are the models used:

- 🌐 **Support Vector Classifier (SVC)**
- 🌲 **Random Forest Classifier**
- 🔥 **Gradient Boosting Classifier**
- 📍 **K-Nearest Neighbors**
- 📈 **Multinomial Naive Bayes**

Each model's performance was evaluated using accuracy scores and confusion matrices.

## 📜 License

This project is licensed under the MIT License.

## 💡 Acknowledgements

Thank you to all contributors and the machine learning community for their resources and support!

--- 

Feel free to let me know if there’s anything else you'd like to add!
