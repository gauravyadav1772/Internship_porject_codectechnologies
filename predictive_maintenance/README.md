# 🔧 Machine Predictive Maintenance Classification

**Author:** Gaurav Yadav  
**Technologies:** Python · Scikit-learn · Streamlit · Pandas · Joblib  

This application is designed to **predict machine failure for predictive maintenance** using machine learning. It utilizes a synthetic dataset with 10,000 data points and 14 features. The application is built using a **Random Forest Classifier** to determine whether the machine will fail based on input parameters.

---

## 🚀 Live Application

👉 [Click here to view the deployed Streamlit app](https://predictive-maintenance-using-machine-learning.streamlit.app/)

---

## 📓 Google Colab Notebook

👉 [Open the Google Colab notebook for this project](#) <!-- Replace # with actual link -->

---

## 📊 Kaggle Dataset

👉 [View the dataset used in this project](#) <!-- Replace # with actual link -->

---

## 📁 Dataset Description

The dataset consists of the following features:

- **UID**: Unique identifier ranging from 1 to 10000  
- **productID**: Product quality variant (L, M, or H) + serial number  
- **air temperature [K]**: Random walk around 300 K (std dev = 2 K)  
- **process temperature [K]**: Air temperature + 10 K + random walk (std dev = 1 K)  
- **rotational speed [rpm]**: Based on power of 2860 W with noise  
- **torque [Nm]**: Normally distributed around 40 Nm (σ = 10), no negative values  
- **tool wear [min]**: Increases based on product quality (H/M/L → +5/3/2 min)  
- **machine failure**: Label indicating if the machine failed (target variable)

> ⚠️ **Important:** The dataset contains two target columns. Avoid using one of them as a feature to prevent **data leakage**.

---

## 🛠️ How to Use the Application

1. **Install Python** on your system (if not already installed).
2. Install required packages:

```bash
pip install streamlit pandas scikit-learn
🧭 Application Workflow
Launch the app in your browser.

Fill in the form fields (product ID, air temperature, torque, etc.)

Click "Predict Failure".

View the model's prediction (Failure / No Failure).

🧪 Model Details
Model Type: Random Forest Classifier

Why Random Forest? It handles both numerical and categorical features well, is resistant to overfitting, and provides high accuracy.

Serialization: The trained model is saved using joblib for reuse in the Streamlit application.

⚙️ Dependencies
Python 3.x

Streamlit

Pandas

Scikit-learn

Joblib

📚 About the Dataset
This synthetic dataset closely mimics real-world predictive maintenance scenarios. It includes a variety of operating conditions, product variants, and failure types. The goal is to help model real machine behavior and preemptively detect failures for maintenance optimization.

⚠️ Disclaimer
This project uses synthetic data intended for educational and demonstration purposes. While it simulates realistic behavior, results may not generalize to real-world industrial machinery. Use with caution for any production-level applications.

👨‍💻 Author
Gaurav Yadav
B.Tech - Mechanical Engineering
Dr B R Ambedkar National Institute of Technology, Jalandhar
📧 gauravyadav.nitj@example.com <!-- Replace with actual email if desired -->
🔗 LinkedIn <!-- Optional: Add LinkedIn profile link -->

📄 License
This project is open-source and available under the MIT License.

yaml
Copy code

---

✅ *Just paste this into your `README.md` file on GitHub*  
🔁 Replace any placeholder links (`#`) with your actual Colab, Kaggle, or LinkedIn links.  
Let me know if you want a badge section or screenshots section added!
