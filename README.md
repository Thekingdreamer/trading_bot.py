# 🚀 Trading Bot Algorítmico

Este es un modelo de trading algorítmico que opera en KuCoin, diseñado para generar un rendimiento anualizado del ~48% mediante estrategias basadas en análisis técnico.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Características Principales
- **Estrategia**: Cruce de medias móviles (MA-50/MA-200) + filtro RSI.
- **Gestión de riesgo**: Stop-loss dinámico basado en volatilidad (ATR).
- **Alertas**: Notificaciones en tiempo real via Telegram.
- **Backtesting**: Validación histórica con datos de OHLC.

## ⚙️ Requisitos
- Python 3.10 o superior.
- Bibliotecas:
  ```python
  python-kucoin == 2.3.1
  pandas == 2.0.3
  numpy == 1.24.3
  schedule == 1.2.0
  requests == 2.31.0

git clone https://github.com/tu-usuario/trading-bot.git
cd trading-bot

pip install -r requirements.txt
