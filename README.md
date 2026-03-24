# 📈 HalfTrend Indicator

Professional HalfTrend indicator implementation for technical analysis and trend following.

## 🎯 Features

- ✅ Accurate trend detection
- ✅ Minimal lag
- ✅ Support/Resistance levels
- ✅ Multi-timeframe support
- ✅ Alert system
- ✅ Customizable parameters

## 📋 Requirements

- TradingView (Pine Script v5)
- MetaTrader 4/5
- Or Python 3.8+

## 🔧 Installation

### TradingView

1. Open Pine Editor
2. Copy code from src/halftrend.pine
3. Save and add to chart

### Python

 + "`" + @"
bash
git clone https://github.com/CostaJr007/halftrendis.git
pip install -r requirements.txt
 + "`" + @"

## 💡 Usage

### Python Example

 + "`" + @"
python
from halftrend import HalfTrend
import pandas as pd

data = pd.read_csv('price_data.csv')
ht = HalfTrend(atriod=2, amplitude=3)
signals = ht.calculate(data)
 + "`" + @"

## ⚙️ Parameters

| Parameter | Description | Default |
|-----------|-------------|---------|
| atriod | ATR period | 2 |
| amplitude | Trend amplitude | 3 |
| dev | Standard deviations | 2 |

## 📊 Trading Signals

| Signal | Description | Action |
|--------|-------------|--------|
| 🟢 Bullish | Trend turns up | Buy |
| 🔴 Bearish | Trend turns down | Sell |

## 📄 License

MIT License

## 👤 Author

**CostaJr007**

---
⭐ *"Indicador dos deuses"* - May your trades be profitable!