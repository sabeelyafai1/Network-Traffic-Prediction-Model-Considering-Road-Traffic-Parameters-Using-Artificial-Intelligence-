# Network-Traffic-Prediction-Model-Considering-Road-Traffic-Parameters-Using-Artificial-Intelligence

This project presents an advanced AI-driven prediction framework designed to estimate **network traffic flow** by integrating **road traffic parameters** and traditional **network traffic features**.  
Unlike previous studies that evaluate road traffic and network traffic *independently*, this work simultaneously considers both domains to improve prediction accuracy.

The proposed hybrid model, **RF-GRU-NTP (Random Forest – Gated Recurrent Unit – Network Traffic Prediction)**, uses machine learning and deep learning techniques to forecast traffic across V2V (Vehicle-to-Vehicle), V2R (Vehicle-to-Road), and combined V2V+V2R environments.

---

## ⭐ Short Description

This study develops a prediction model capable of analyzing and forecasting network traffic by examining the determinants that influence road traffic conditions.  
The RF-GRU-NTP model operates in three prediction modes:

1. **V2V Traffic Prediction** – Traffic expected to use vehicle-to-vehicle communication  
2. **V2R Traffic Prediction** – Traffic expected to use vehicle-to-road communication  
3. **Hybrid V2V + V2R Prediction** – Traffic expected to utilize both communication paths  

The Random Forest algorithm first selects the most important features from a dataset containing V2V and V2R parameters.  
Then, the refined features are fed into a GRU-based deep learning model to forecast network traffic flow.

Experimental results show that the proposed model outperforms traditional prediction methods in terms of **accuracy, efficiency, and execution time**.

---

## 🎯 Main Purpose / Problem Solved

Previous research typically focuses on **either** road traffic prediction or network traffic forecasting—**not both together**.  
This project solves that gap by creating a model capable of predicting network traffic behavior based on **real-time road traffic dynamics**, allowing:

- More accurate network planning  
- Better optimization of vehicular communication  
- Enhanced performance in intelligent transportation systems (ITS)

---

## 🛠️ Tech Stack

### **Programming Language**
- Python

### **Frameworks & Modules**
- TensorFlow  
- Scikit-Learn  
- Pandas  
- NumPy  
- Matplotlib

### **Algorithms Used**
- **Machine Learning Models:**  
  - Random Forest  
  - Decision Tree  
  - Support Vector Machine (SVM)

- **Deep Learning Models:**  
  - CNN  
  - RNN  
  - GRU  
  - LSTM  

### **Deployment**
- Flask Web Framework

---

## 🚀 Features

- Hybrid Random Forest + GRU prediction architecture  
- Feature selection using Random Forest  
- Time-series forecasting using GRU networks  
- Support for V2V, V2R, and combined traffic modeling  
- High accuracy and reduced runtime compared to existing methods  
- Flask-based deployment for real-time usage  
- Data visualization for network and road traffic trends  

--
### **Results**



<img width="587" height="370" alt="classification report" src="https://github.com/user-attachments/assets/439df6e4-49ca-4586-9c6e-890dac184afa" />


Classification Reports


<img width="457" height="237" alt="exc time" src="https://github.com/user-attachments/assets/69afb916-fe25-4aaf-a729-837d0332fcdc" />

Execution Time

