# ✈️ Flight Price Prediction – Project Report

**Objective**  
Predict flight ticket prices using machine learning to help customers and airlines in decision-making.

---

### 📊 Dataset  
- Features: Airline, Source, Destination, Total_Stops, Duration, Route, Additional_Info  
- Target: Price  

---

### ⚙️ Preprocessing  
- Converted Duration → minutes  
- Extracted Departure/Arrival hours  
- Encoded categorical features (Airline, Source, Destination, Stops)  
- Scaled numerical values  

---

### 🔍 EDA Highlights  
- Non-stop flights are costliest  
- Airline strongly affects price  
- Duration and Stops are major predictors  

---

### 🤖 Models Tried  
- Linear Regression (baseline)  
- Decision Tree, KNN  
- Random Forest ✅ (best)  
- Gradient Boosting (good but slower)  

---

### 📈 Results  
- **Random Forest Regressor** → Best accuracy (highest R², lowest RMSE)  
- Gradient Boosting close second  

---

### 📝 Insights  
- Fewer stops → higher prices  
- Some airlines consistently more expensive  
- Flight duration correlates with price  

---

### 🚀 Future Work  
- Try XGBoost / LightGBM  
- Build Flask/Streamlit app  
- Add real-time dynamic pricing  

---

**Tools Used**: Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn  
