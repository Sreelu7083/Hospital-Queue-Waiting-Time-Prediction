# Hospital-Queue-Waiting-Time-Prediction
# Hospital Queue & Waiting Time Prediction using Machine Learning

## 📌 Project Overview
Long waiting times in hospitals lead to patient dissatisfaction and inefficient resource utilization.  
This project focuses on **analyzing hospital queue behavior and predicting patient waiting time** using machine learning techniques. By predicting waiting time in advance, hospitals can better manage queues and improve service efficiency.

---

## 🎯 Objectives
- Analyze hospital queue data
- Predict patient waiting time accurately
- Understand the relationship between queue length and waiting time
- Compare machine learning models for performance

---

## 🏥 Problem Statement
Hospitals often experience unpredictable patient queues, resulting in long waiting times. Manual estimation of waiting time is unreliable.  
This project uses **machine learning-based regression models** to analyze queue conditions and predict patient waiting time.

---

## 📂 Dataset Description
The dataset contains hospital queue-related attributes representing patient arrival and service timings.

### Columns Used:
- **arrival_time** – Time when the patient arrives at the hospital queue  
- **start_time** – Time when the patient’s service begins  
- **finish_time** – Time when the service is completed  
- **wait_time** – Time the patient waits before service (**target variable**)  
- **queue_length** – Number of patients waiting in the queue  

The dataset effectively captures hospital queue dynamics, making it suitable for waiting time prediction.

---

## 🛠️ Technologies Used
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔄 System Approach
1. **Data Collection** – Hospital queue timing data  
2. **Data Preprocessing** – Handling missing values and feature preparation  
3. **Exploratory Data Analysis** – Understanding patterns through visualization  
4. **Model Training** – Applying regression models  
5. **Evaluation** – Comparing actual and predicted waiting times  
6. **Result Interpretation** – Identifying the best-performing model  

---

## 🤖 Machine Learning Models Used
- Linear Regression (Baseline Model)  
- Random Forest Regressor (Final Model)  

---

## 📊 Evaluation Metrics
As this is a regression problem, the following metrics were used:
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

---

## 📈 Visualizations
- Distribution of waiting time  
- Waiting time vs queue length  
- Correlation heatmap  
- Actual vs predicted waiting time  
- Feature importance analysis  

---

## 🧪 Results
- Random Forest Regressor outperformed Linear Regression  
- Lower MAE and RMSE values indicate better prediction accuracy  
- Actual vs predicted visualizations show strong alignment  

---

## ✅ Conclusion
The project successfully predicts hospital waiting time based on queue-related features.  
The Random Forest model effectively captures non-linear relationships in hospital queue data, helping improve patient flow and operational efficiency.

---

## 🔮 Future Scope
- Integration with real-time hospital systems  
- Deployment as a web or mobile application  
- Expansion to multiple hospital departments  
- Use of advanced time-series models for prediction  

---

Author:
Sreelakshmi.M.R
