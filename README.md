# 🎬 Netflix Stock Price Prediction

## 📊 Project Overview
This project applies machine learning and deep learning techniques to predict **Netflix (NFLX)** stock prices using historical market data. The goal is to forecast future closing prices with high accuracy and analyze model performance across various algorithms including **LSTM**, **XGBoost**, and a **Hybrid Stacking Model**.

By leveraging time series analysis, the project explores patterns, trends, and the potential of ensemble learning in financial forecasting.

---

## 🧠 Objectives
- Perform data cleaning and feature engineering on historical Netflix stock data.  
- Implement and compare multiple models:
  - **LSTM (Long Short-Term Memory)**
  - **XGBoost Regressor**
  - **Hybrid Stacked Model (LSTM + XGBoost)**
- Evaluate model performance using metrics such as **RMSE**, **MAE**, and **R² Score**.  
- Interpret model results using **SHAP values** for explainability.

---

## ⚙️ Tools & Technologies
- **Python**
- **Pandas, NumPy, Scikit-learn**
- **TensorFlow / Keras**
- **XGBoost**
- **Matplotlib, Seaborn**
- **SHAP (Model Interpretability)**
- **Google Colab / Jupyter Notebook**

---

## 📈 Model Performance Summary

| Model              | RMSE     | MAE      | R² Score |
|--------------------|----------|----------|-----------|
| LSTM               | 0.0246   | 0.0204   | 0.9952    |
| XGBoost            | 0.0029   | 0.0021   | 0.9999    |
| Hybrid (Averaging) | 0.0125   | 0.0104   | 0.9988    |
| Stacked Model      | 0.0029   | 0.0021   | 0.9999    |

✅ **Best Model:** The **Stacked Model** achieved the highest accuracy, capturing both temporal dependencies (via LSTM) and non-linear patterns (via XGBoost).

---

## 🔍 Key Insights
- The **LSTM model** effectively captured time-based dependencies but slightly underperformed compared to ensemble models.  
- The **XGBoost model** handled feature interactions and noise robustly.  
- The **Hybrid Stacked Model** outperformed all, achieving near-perfect prediction accuracy (R² = 0.9999).  
- **SHAP analysis** helped identify which features most strongly influenced stock predictions.

---

## 🧩 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/Wawira-Muthoni/netflix-stock-price-prediction.git

2. Open the notebook in Google Colab or Jupyter Notebook.


3. Install dependencies:
pip install -r requirements.txt

4. Run all cells to reproduce results.



##📁 Dataset
Historical Netflix stock data was obtained from Yahoo Finance.
Time range: 2010–2024
Frequency: Daily closing prices

🏆 Key Learning Outcomes
-Applied time series forecasting using deep learning (LSTM).
-Learned model stacking and ensembling for performance improvement.
-Practiced model interpretability using SHAP.
-Enhanced data storytelling through visual analytics and performance comparison plots.



🧑‍💻 Author
Christine Wawira
📧 christineewawira@gmail.com
🔗 LinkedIn | GitHub

💡 Future Improvements

-Integrate real-time data streaming for live price prediction.

-Add sentiment analysis using financial news headlines.

-Deploy the model as a web app using Flask / Streamlit.



⭐ If you found this project insightful, consider giving it a star on GitHub! ⭐

---

Would you like me to make a **short version (1–2 paragraphs)** that you can paste directly as a **LinkedIn post caption** too?
   
