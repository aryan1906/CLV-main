# Customer Lifetime Value (CLV) Forecasting

This project forecasts **Customer Lifetime Value (CLV)** using both **probabilistic modeling** and **machine learning**, providing insights into customer behavior, revenue forecasting, and strategic segmentation.

---

## 📌 Project Overview

Customer Lifetime Value (CLV) helps businesses understand how much revenue they can expect from customers over time.  
This notebook explores two approaches:

1. **Probabilistic Model (Lifetimes Library)**  
   - Uses customer transaction history to model repeat purchases and churn.  
   - Great for long-term strategic planning.  

2. **Machine Learning Model (XGBoost)**  
   - Predicts spend more accurately using transaction-level features.  
   - Best for short-term tactical forecasting.  

---

## 🔑 Key Insights

### 1. Revenue Forecast
- Predicted **£4.5M revenue** over the next **6 months**.  
- Top 10 customers expected to generate between **£36k–£129k** each.

### 2. Customer Segmentation
- **Top-Tier (25%)**: ~£2,349 average CLV (6 months).  
- **Mid-Tier (50%)**: ~£327 average CLV.  
- **Low-Tier (25%)**: ~£82 average CLV.  

### 3. Profiling High-Value Customers
- **Geography**: Majority located in the **United Kingdom**.  
- **Product Preferences**:  
  - Low-value customers buy widely.  
  - High-value customers prefer **specific, higher-margin categories** (e.g., *Regency Cake Stand*).  

---

## 📊 Model Comparison

| Model              | RMSE   | MAE  | Best For |
|--------------------|--------|------|----------|
| Lifetimes (BG/NBD) | ~3182  | ~434 | Strategic CLV estimation |
| XGBoost            | ~2640  | ~364 | Short-term financial forecasting |

- **XGBoost** → More accurate for predicting short-term spend.  
- **Lifetimes** → Better at long-term value estimation and ranking customers.  

---

## 🚀 Strategic Recommendations
- **Targeted Marketing**: Focus campaigns on mid-tier UK customers to push them into top-tier.  
- **Product Promotion**: Double down on high-margin categories favored by top-tier buyers.  
- **Forecasting**: Use XGBoost for **short-term budgeting**, Lifetimes for **long-term strategy**.  

---

## 🛠️ Tech Stack
- **Python**
- **lifetimes** (BG/NBD + Gamma-Gamma models)
- **XGBoost**
- **pandas, numpy, matplotlib, seaborn**
- **Jupyter Notebook**

---


---

## 📈 Future Work
- Add deep learning models (RNNs/Transformers) for CLV prediction.  
- Integrate demographic & behavioral features for richer profiling.  
- Automate pipeline for real-time CLV updates.  

---

## ✍️ Author
Project developed for **Customer Analytics & Forecasting** use case.  
Feel free to contribute or suggest improvements via issues or pull requests.


## 📂 Project Structure
