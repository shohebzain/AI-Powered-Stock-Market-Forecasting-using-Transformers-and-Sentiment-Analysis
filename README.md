# AI-Powered Stock Market Forecasting

Transformer-based stock prediction with technical indicators and sentiment analysis.

## Quick Start

**Terminal 1 — Backend API**
```bash
cd backend
pip install -r requirements.txt
python main.py
```

**Terminal 2 — Frontend**
```bash
cd frontend
npm install
npm run dev
```

Open **http://localhost:5173** (API proxied to port 8000).

## StockVision AI

| Component | Description |
|-----------|-------------|
| [frontend/](frontend/) | React dashboard UI |
| [backend/](backend/) | FastAPI · yfinance · ML forecasts · sentiment |

See [frontend/README.md](frontend/README.md) and [backend/README.md](backend/README.md).

## Project Assets

- `apple_stock_data.csv` — Historical stock data.
- `*.h5` / `*.keras` — Trained LSTM and Transformer models.

## Disclaimer

For educational purposes only. Not financial advice.
