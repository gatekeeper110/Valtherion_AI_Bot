# Valtherion AI Bot (Final Version)

🚀 An ultra-intelligent, self-learning MT5 AI Expert Advisor designed for institutional-grade trading precision.

## 🔧 Features
- Smart Money Concept (SMC) AI entry logic
- ONNX model prediction engine
- Telegram alerts
- Google Sheets logging
- Auto-retraining (weekly + every 8 trades)
- Macro/news panic filter
- VPS resilience (auto-restart + watchdog)

## 🛠 Requirements
- MetaTrader 5
- Python 3.10+
- `onnxruntime`, `telebot`, `gspread`, etc.

## 📈 Setup
```bash
pip install -r requirements.txt
python ai_server.py
