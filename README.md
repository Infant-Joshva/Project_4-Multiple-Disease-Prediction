# 🩺 Multiple Disease Prediction System

Multiple Disease Prediction is an advanced Data Science project that leverages machine learning to predict the likelihood of multiple diseases, including **Kidney Disease, Liver Disease, and Parkinson’s Disease**. The system aims to support early diagnosis, assist healthcare providers in decision-making, and reduce the time and cost of traditional diagnostics. The project integrates data preprocessing, machine learning model training, evaluation, and visualization using Streamlit and Power BI.

---

## 🔧 Tech Stack

![Python](https://img.shields.io/badge/Python-3.8%2B-gray?logo=python&logoColor=white&labelColor=3776AB)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-gray?logo=pandas&logoColor=white&labelColor=150458)
![Plotly](https://img.shields.io/badge/Plotly-Visualizations-gray?logo=plotly&logoColor=white&labelColor=11557c)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-gray?logo=numpy&logoColor=white&labelColor=013243)
![SciPy](https://img.shields.io/badge/SciPy-Statistical%20Analysis-gray?logo=scipy&logoColor=white&labelColor=8C5E9C)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-ML%20Models-gray?logo=scikit-learn&logoColor=white&labelColor=f89939)
![Google%20Colab](https://img.shields.io/badge/Google%20Colab-Notebook-gray?logo=google-colab&logoColor=white&labelColor=f9ab00)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-gray?logo=streamlit&logoColor=white&labelColor=FF4B4B)
![Power%20BI](https://img.shields.io/badge/Power%20BI-Dashboard-gray?logo=power-bi&logoColor=white&labelColor=F2C811)

---

## 📁 Project Structure

```
📂 multiple-disease-prediction
|
├── 📁 app/                           # Streamlit application code
│   └── streamlit_app.py
|
├── 📁 data/
│   ├── 📁 raw/                       # Original/raw datasets
│   │   ├── kidney_disease.csv
│   │   ├── liver_disease.csv
│   │   └── parkinsons_disease.csv
│   │
│   ├── 📁 cleaned/                   # Cleaned/preprocessed datasets
│   │   ├── kidney_disease_cleaned.csv
│   │   ├── liver_disease_cleaned.csv
│   │   └── parkinsons_disease_cleaned.csv
│
├── 📁 models/                        # Trained ML models (saved as pickle files)
│   ├── kidney_model.pkl
│   ├── liver_model.pkl
│   └── parkinsons_model.pkl
|
├── 📁 notebooks/                     # google colab notebooks for EDA & modeling
│   ├── Kidney_Disease_Prediction.ipynb
│   ├── Liver_Disease_Prediction.ipynb
│   ├── Parkinsons_Prediction.ipynb
│
├── 📁 video/                         # Project demo video
│   └── project_demo.mp4
│
├── requirements.txt                  # Python dependencies
├── README.md                         # Project documentation
├── .gitignore                        # Ignore unnecessary files in git
└── LICENSE                           # Open-source license for project

```

---

## 🚀 How to Run

1. Clone the repository  
```bash
git clone https://github.com/Infant-Joshva/Project_4-Multiple-Disease-Prediction.git
cd Project_4-Multiple-Disease-Prediction
```

2. Install dependencies  
```bash
pip install -r requirements.txt
```

3. Run the Streamlit app  
```bash
streamlit run app/main.py
```
---

## 📊 Features

- **Multi-Disease Prediction**: Predicts Kidney, Liver, and Parkinson’s disease probability based on user-provided symptoms, demographics, and test results.  
- **Data Preprocessing**: Handles missing values, encodes categorical features, and scales numerical data to improve model accuracy.  
- **Machine Learning Models**: Trained using Logistic Regression, Random Forest, and XGBoost for robust predictions.  
- **Interactive Streamlit App**: Users can input personal health data and instantly receive disease probability and risk level.
- **Model Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC, MAE, RMSE.  
- **Scalable & Secure**: Designed to handle multiple users and ensure privacy of sensitive health data.  
- **Visual Insights**: Graphs and charts showing feature importance, probability distributions, and high-risk patient identification.  

---

## 📷 App Screenshots

### 📄 Overview
![Overview](https://github.com/user-attachments/assets/b6c2c291-4391-4ab5-a391-218a24d2b536)

---

### 🩸 Kidney Disease
![Kidney Disease](https://github.com/user-attachments/assets/51bc480c-1aaa-4f22-ba7b-22a170b37a78)

---

### 🧬 Liver Disease
![Liver Disease](https://github.com/user-attachments/assets/833e25f0-f1ae-4933-bc4e-622d2de230da)

---

### 🧩 Parkinsons Disease
![Parkinsons Disease](https://github.com/user-attachments/assets/9fd546a0-059c-4419-b136-ef07664d5679)

---

## 📚 Insights

- Patients with abnormal test results have higher predicted disease probabilities.  
- Multi-disease prediction enables prioritizing early diagnosis and treatment.  
- Visualizations improve interpretability of model results and risk analysis.  
- Healthcare providers can monitor trends across patient populations and identify high-risk groups.  

---

## 👤 Author

**Your Name**  
📧 infantjoshva2024@gmail.com  
🐙 [GitHub](https://github.com/Infant-Joshva)  
🔗 [LinkedIn](https://www.linkedin.com/in/infant-joshva)

---

## ⭐ Give a Star!

If you find this project useful, please give it a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
