# RSI Signal Strength Evaluation Method

This repository contains a Pine Script implementation and analysis of an RSI-based signal strength evaluation method applied to cryptocurrency markets.

The study compares four different RSI-based approaches in order to evaluate signal quality and trading performance:

1. Classical RSI  
2. Stochastic RSI (StochRSI)  
3. Stochastic RSI combined with a signal strength evaluation method (without Stop Loss and Take Profit)  
4. Stochastic RSI combined with a signal strength evaluation method (with Stop Loss and Take Profit)

The proposed method aims to distinguish between strong and weak RSI signals, reduce false signals, and improve overall trading robustness.

---

## Implemented Approaches

### 1. Classical RSI
The standard Relative Strength Index using fixed overbought and oversold levels (70/30).  
Signals are generated solely based on RSI threshold crossings.

### 2. Stochastic RSI (StochRSI)
A momentum-based extension of RSI that increases sensitivity to short-term price movements.  
This approach generates more frequent signals but is also more prone to noise.

### 3. Signal Strength Method (Without Stop Loss / Take Profit)
This approach combines Stochastic RSI with additional signal strength criteria in order to filter weaker signals.  
No explicit risk management rules are applied.

### 4. Signal Strength Method (With Stop Loss / Take Profit)
The full version of the proposed method.  
In addition to signal strength evaluation, Stop Loss and Take Profit levels are applied to manage risk and improve trade outcome stability.

---

## Markets and Data

The methods were tested on the following cryptocurrency markets:
- Bitcoin (BTC)
- Ethereum (ETH)
- Litecoin (LTC)

The analysis covers multiple market periods, including bullish, bearish, and ranging market conditions.

---

## How to Use in TradingView

1. Open **TradingView**
2. Go to **Pine Editor**
3. Copy the Pine Script code from this repository
4. Paste it into the Pine Editor
5. Click **Add to chart**
6. Adjust indicator parameters if needed

The script can be used both for visual signal analysis and strategy testing.

---

## Purpose of the Project

The main objective of this project is to evaluate whether RSI signal strength classification and risk management techniques can improve trading signal quality compared to classical RSI-based approaches.

This work was developed as part of an academic research project focusing on technical indicator evaluation in cryptocurrency markets.

---

## Disclaimer

This script is provided for educational and research purposes only.  
It does not constitute financial advice. Trading cryptocurrencies involves significant risk.
