
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
├── main.py                       # Main script to run the project
└── images                        # Folder to store screenshots/images
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

## 🖼️ Project Images

### Disease Prediction Interface
![image](https://github.com/user-attachments/assets/1c597142-77b3-4d86-a368-07f6a0ad9a09)
![image](https://github.com/user-attachments/assets/c8e7d8b8-cad3-4b7b-92e0-b053ba1022ef)
![image](https://github.com/user-attachments/assets/93b3bf99-5454-4cd3-80b8-25780b6b109c)
![image](https://github.com/user-attachments/assets/a8e0dee4-bbde-4150-826b-5d9968dfe392)
![image](https://github.com/user-attachments/assets/aba53524-a0cb-4ca2-a849-b2203a59aafb)
![image](https://github.com/user-attachments/assets/228d7c6d-0b8b-4382-bacb-5f632103494d)
![image](https://github.com/user-attachments/assets/abcb65e1-ee1a-4ec7-b307-6a6d9e01a0e6)
![image](https://github.com/user-attachments/assets/e2118e26-29ae-49be-a46a-e1090026748b)
![image](https://github.com/user-attachments/assets/17491423-d9ca-4771-826e-7db651b6297f)
![image](https://github.com/user-attachments/assets/15344371-4c97-4f4c-ba76-333277a4ad43)
![image](https://github.com/user-attachments/assets/2c77c307-ccd1-4cee-82d3-d4d38a9bae06)









*Add more images as needed, describing each feature or result.*

## 📜 License

This project is licensed under the MIT License.

## 💡 Acknowledgements

Thank you to all contributors and the machine learning community for their resources and support!

---
