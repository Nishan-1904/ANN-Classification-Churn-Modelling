
# 🧠 Customer Churn Prediction using Artificial Neural Network

This project aims to build a predictive model that identifies whether a bank customer is likely to leave (churn) or stay, based on various features like credit score, geography, age, tenure, balance, and more. The model is built using an Artificial Neural Network (ANN) and deployed via a Streamlit web application.

---

## 🔍 Problem Statement

Customer churn is a key metric in the banking sector as retaining existing customers is more cost-effective than acquiring new ones. This project helps banks proactively identify customers who are likely to leave, enabling timely retention efforts.

---

## 🚀 Project Highlights

- ✅ Built an ANN model using **TensorFlow** and **Keras**
- 📊 Visualized training metrics using **TensorBoard**
- ⚙️ Data preprocessing using **scikit-learn**
- 🌐 Deployed with **Streamlit** for interactive web-based predictions
- 📈 Achieved a model accuracy of **~87%**

---

## 🧾 Dataset

The dataset consists of 10,000 entries of bank customers with the following features:

- `CreditScore`, `Geography`, `Gender`, `Age`, `Tenure`, `Balance`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`
- Target variable: `Exited` (1 = customer left, 0 = customer stayed)

---

## 🛠️ Tech Stack

| Library       | Purpose                             |
|---------------|-------------------------------------|
| `TensorFlow`  | Building and training the ANN model |
| `Keras`       | High-level API for TensorFlow       |
| `scikit-learn`| Data preprocessing & evaluation     |
| `TensorBoard` | Training visualization              |
| `Streamlit`   | Model deployment                    |

---

## 📊 Model Architecture

- **Input Layer**: Accepts preprocessed numerical and encoded categorical features
- **Hidden Layers**: Two dense layers with ReLU activation functions
- **Output Layer**: Single node with sigmoid activation for binary classification

---

## ⚙️ How to Run Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/customer-churn-ann.git
   cd customer-churn-ann


2. **Create a virtual environment & install dependencies**

   ```bash
   python -m venv venv
   # For Windows:
   venv\Scripts\activate
   # For macOS/Linux:
   source venv/bin/activate

   pip install -r requirements.txt
   ```

3. **Run the Streamlit App**

   ```bash
   streamlit run app.py
   ```

---

## 📷 Screenshots
![image](https://github.com/user-attachments/assets/8763c8ba-8142-49ee-9b3d-8359b277618e)


![image](https://github.com/user-attachments/assets/02f8b4af-4bfe-4cd7-a068-47e617f0e32e)



---

## 📁 Repository Structure

```
customer-churn-ann/
│
├── data/                   # Dataset files
├── models/                 # Saved models and logs
├── app.py                  # Streamlit deployment script
├── churn_model.ipynb       # Model training notebook
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
└── screenshots/            # App and visualization screenshots
```

---

## 📌 Key Learnings

* Understanding and implementation of ANN for binary classification
* Handling categorical data and feature scaling
* Model evaluation using accuracy, confusion matrix
* Visualizing training performance using TensorBoard
* Deploying ML model using Streamlit with interactive UI

---





⭐ If you found this project useful, feel free to give it a star!



