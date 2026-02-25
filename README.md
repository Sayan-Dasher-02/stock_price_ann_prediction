# 📈 **Stock Price Prediction Dashboard** ✨

**Real-time stock forecasting** with **Deep Learning** + **live yfinance data** in a beautiful Streamlit dashboard.

***

## 🚀 **Complete Environment Setup** (5 Minutes)

### **Step 1: Create Virtual Environment**
```bash
# Windows
python -m venv stock_env

# Mac/Linux  
python3 -m venv stock_env
```

### **Step 2: Activate Environment**
```bash
# Windows
stock_env\Scripts\activate

# Mac/Linux
source stock_env/bin/activate
```

**✅ You'll see `(stock_env)` in your terminal**

### **Step 3: Install Everything**
```bash
pip install streamlit==1.38.0 tensorflow==2.17.0 yfinance==0.2.40 plotly==5.22.0 pandas==2.2.2 numpy==1.26.4 scikit-learn==1.5.1
```

### **Step 4: Run App**
```bash
cd stock_price_ann_prediction
Streamlit run stock_price_prediction.py
```

**🎉 Opens:** `http://localhost:8501`

***

## 📦 **requirements.txt** (Copy & Save)
```txt
streamlit==1.38.0
tensorflow==2.17.0
yfinance==0.2.40
plotly==5.22.0
pandas==2.2.2
numpy==1.26.4
scikit-learn==1.5.1
```

***

## 📁 **Project Structure**
```
📂 Stock-Prediction/
│
├── stock_price_prediction.py    # 🎯 Main app
├── requirements.txt             # 📦 Dependencies  
├── README.md                   # 📖 This file
└── stock_env/                  # 🐍 Virtual env (git ignore)
```

***

## 🎮 **Dashboard Features**

| **Control** | **What You Get** |
|-------------|------------------|
| 🏢 **Company** | AAPL, MSFT, TSLA, GOOGL... |
| 📅 **60 Days** | Historical training data |
| 🔮 **1-5 Days** | Future price predictions |
| 🔄 **Auto-refresh** | Live updates every 30s |

***

## 📊 **Live Results**
```
🍎 AAPL Prediction:
┌─────────────────────────────┐
│ Last Close:   $225.43       │
│ Next Open:    $227.12 +0.8% │
│ Next Close:   $228.76 +1.5% │
└─────────────────────────────┘
```

**Charts:** Candlestick + Volume + Correlation Heatmap

***

## ☁️ **Deploy to Cloud**

```bash
# Streamlit Cloud (FREE)
1. Push to GitHub
2. Connect: share.streamlit.io
3. Deploy → ✅ Live in 2 mins
```

***

## 🧹 **Deactivate Environment**
```bash
deactivate
```

***

## 🎯 **One-Line Summary**
```bash
python -m venv stock_env && source stock_env/bin/activate && pip install -r requirements.txt && streamlit run stock_price_prediction.py
```

<div align="center">
**💾 Copy ALL above → `README.md` → GitHub → Portfolio Ready! 🚀**
</div>

***

**✅ Virtual env + exact commands + cloud deploy = Production Ready!**  
**Made for Sayan Mondal's MCA Final Year Project ✨**
