# 🛡️ Fraud Detection AI – K-Means Clustering

An **industry-style AI pipeline** that demonstrates how unsupervised machine learning can be used to detect **suspicious transactions** using **K-Means clustering**, deployed with an interactive **Streamlit web app**.

This project simulates a real-world workflow:
**Raw Data → Data Cleaning → Model Training → Model Persistence → Web Deployment**

---

## 🚀 Features

- 📊 Synthetic transaction dataset with **noise, missing values, duplicates**
- 🧹 Data cleaning (duplicates removal + median imputation)
- 🤖 Unsupervised learning using **K-Means Clustering**
- 📐 Feature scaling with **StandardScaler**
- 💾 Model & scaler persistence using **joblib**
- 🌐 Interactive **Streamlit UI** for real-time predictions
- ⚠️ Automatic identification of **suspicious transaction clusters**

---

## 🧠 ML Concept Used

- **Algorithm:** K-Means Clustering (Unsupervised Learning)
- **Why K-Means?**
  - No labeled fraud data required
  - Detects abnormal patterns via clustering
- **Fraud Logic:**
  - Cluster with the **highest transaction amount centroid** is treated as *suspicious*

---

## 📁 Project Structure
├── fraud_dataset.csv # Raw dataset (auto-generated)
├── fraud_dataset_cleaned.csv # Cleaned dataset
├── fraud_kmeans_model.pkl # Trained KMeans model
├── scaler.pkl # StandardScaler
├── app.py # Streamlit application
├── README.md # Project documentation


---

## 🛠️ Tech Stack

- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Streamlit**
- **Joblib**

---

## ▶️ How to Run Locally

### 1️⃣ Clone the repository
git clone https://github.com/Anaamalikhan/Fraud-Detection-ai.git
cd fraud-detection-ai
🧪 Input Features
Feature	Description
Amount	Transaction amount
Items	Number of items purchased
Distance_km	Delivery distance in kilometers 
📌 Prediction Output

Normal Transaction ✅

Suspicious Transaction ⚠️

Based on cluster assignment using K-Means.

📸 UI Preview

Dataset preview (raw & cleaned)

Interactive input fields

One-click fraud risk prediction

💡 Use Cases

E-commerce fraud detection

Transaction monitoring systems

AI/ML portfolio project

Demonstrating unsupervised learning in interviews

🔮 Future Improvements

Add visualization of clusters

Use Isolation Forest / DBSCAN

Add real dataset integration

Deploy on cloud (AWS / Streamlit Cloud)

👨‍💻 Author

**Mohammed Anam Ullah**
AIML Student | Aspiring AI Engineer / AI Product Manager

