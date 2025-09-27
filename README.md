# AI-Based-Wildfire-Prediction-System
This project focuses on predicting wildfire risk in India using NASA’s MODIS (Moderate Resolution Imaging Spectroradiometer) satellite data.By applying Machine Learning (ML),the system identifies whether a region is at low, medium, or high risk of wildfire. Performs data preprocessing, cleaning, and visualization. Compares model performances 
# Wildfire Prediction using MODIS Data 🌍🔥

## 📌 Introduction
This project predicts wildfire risk in India using NASA FIRMS MODIS satellite data and Machine Learning / Deep Learning models.  
The system allows users to input a city name and get the probability of wildfire risk.

---

## 🚀 Features
- Data preprocessing and visualization
- ML models: KNN, Random Forest, SVM, Logistic Regression
- Deep Learning models: ANN, LSTM
- Interactive Streamlit app for predictions
- Accuracy comparison of models

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn
- Streamlit
- NASA FIRMS MODIS Dataset

---

## 📊 Results
- Best Accuracy: **87% with Random Forest**
- Visualizations: Heatmaps, Feature Importance, Model Performance

---

## 🔮 Future Scope
- Real-time satellite data integration
- Regional fire spread simulation
- Mobile app deployment

---

## ▶️ Run Locally
```bash
# Clone the repository
git clone https://github.com/<your-username>/wildfire-prediction-ml.git
cd wildfire-prediction-ml

# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
streamlit run app/app.py
