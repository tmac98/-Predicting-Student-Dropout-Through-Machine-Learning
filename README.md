# 🎓 Predicting Student Dropout Using Machine Learning

## 📌 Project Overview  

This project applies **supervised learning** to predict student dropout risk based on **academic performance, attendance, and engagement metrics**. Using **XGBoost and Neural Networks**, the model identifies key factors influencing student retention, enabling **educational institutions to intervene early** and reduce dropout rates. The analysis leverages **feature importance rankings** and **model evaluation metrics** to provide actionable insights for improving student success.  

---

## 📊 Key Features  

✔️ **Data Preprocessing**: Cleaned and standardized student records, handling missing values and categorical variables.  
📈 **Predictive Modelling**: Implemented **XGBoost** and **Neural Networks** to classify students as likely to **drop out or complete their courses**.  
📌 **Feature Importance Analysis**: Identified the most **influential predictors** of student dropout.  
🛠️ **Hyperparameter Tuning**: Optimized model parameters to improve **recall and precision**.  
📊 **Performance Comparison**: Evaluated models based on **accuracy, recall, precision, and AUC scores**.  

---

## 📈 Results & Insights  

🚀 **ContactHours was the strongest predictor of dropout**, highlighting the importance of student engagement.  
📌 **UnauthorisedAbsenceCount and CreditWeightedAverage ranked above AttendancePercentage**, reinforcing the impact of unapproved absences and academic struggles.  
📊 **Adding attendance metrics improved recall**, enabling better identification of at-risk students.  
🤖 **XGBoost provided the best precision**, making it ideal for **minimizing false positives**.  
🧠 **Neural Networks achieved the highest recall**, ensuring more at-risk students were flagged.  

| Model  | Accuracy | Precision | Recall | AUC  |  
|--------|----------|-----------|--------|--------|  
| **XGBoost (No Attendance)**  | 94.01% | 99.65% | 93.95% | 0.9443 |  
| **Neural Network (No Attendance)**  | 92.95% | 99.67% | 92.80% | 0.9404 |  
| **XGBoost (With Attendance)**  | **95.81%** | **99.78%** | **95.75%** | **0.9624** |  
| **Neural Network (With Attendance)**  | **96.43%** | **99.69%** | **96.50%** | **0.9589** |  

✔️ **Key Takeaway:**  
📌 **Educational institutions should track both attendance and academic performance to improve retention strategies.**  

---

## 📂 Project Files  

- 📄 **Google Colab Notebook**: [Predicting Student Dropout Through Machine Learning Notebook](./Predicting_Student_Dropout_Through_Machine_Learning_Notebook.ipynb) 
- 📑 **Business Report**: [Predicting Student Dropout Through Machine Learning Report](./Predicting%20Student%20Dropout%20Through%20Machine%20Learning%20Report.pdf)

---

## 🛠 Technologies Used  

🐍 **Python**: Pandas, NumPy, Scikit-Learn, TensorFlow, Matplotlib, Seaborn  
🤖 **Machine Learning**: XGBoost, Neural Networks (Keras)  
📊 **Data Visualisation**: Feature importance plots, box plots, model performance charts  
🔍 **Optimization**: GridSearchCV, Keras Tuner  

---

## 🔮 Future Improvements  

📊 **Explore time-series analysis** to monitor student engagement trends over time.  
📈 **Enhance model interpretability** with SHAP values for better dropout intervention insights.  
🖥️ **Deploy an interactive dashboard** for universities to monitor and act on student risk predictions.  

---


