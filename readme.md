# Phoenix Confidence Indicator

## Overview

The **Phoenix Confidence Indicator** is a comprehensive trading tool designed to help traders identify market trends, reversals, and momentum. Based on the renowned Phoenix Ascending methodology, this indicator combines multiple technical analysis components into a single, actionable confidence score. It provides clear visual cues for potential buy and sell signals directly on the chart, making it an essential tool for traders of all levels.

## Key Features

- **Confidence Score**: Ranges from 0 to 100, color-coded to indicate:
  - **Green (≥ 70)**: Strong buy conditions.
  - **Red (≤ 30)**: Strong sell conditions.
  - **Yellow (30-70)**: Neutral or uncertain market conditions.
- **Buy/Sell Arrows**: Green upward arrows for buy opportunities, red downward arrows for sell opportunities.
- **Components**:
  - **Trend Confidence Index (TCI)**: Measures deviation from exponential moving averages.
  - **Money Flow (MF)**: Tracks buying and selling pressure based on volume.
  - **Williams %R (Willy)**: Momentum indicator for overbought and oversold conditions.
  - **Composite Strength Index (CSI)**: Combines RSI and TSI for trend strength.
  - **Energy Line**: A smoothed measure of market momentum.
  - **LSMA (Least Squares Moving Average)**: Trend-following calculation to smooth signals.
- Fully customizable input parameters to adapt to different trading styles and timeframes.

---

## How to Use

### 1. **Add the Indicator to TradingView**
1. Open [TradingView](https://www.tradingview.com/).
2. Navigate to the **Pine Script Editor** at the bottom of the page.
3. Copy the code from the `PhoenixConfidenceIndicator.pine` file in this repository.
4. Paste the code into the Pine Script Editor.
5. Click **Save** and then **Add to Chart**.

### 2. **Interpreting the Indicator**
- **Confidence Score**:
  - Check the score displayed on a separate pane below the chart.
  - Use the thresholds to determine market sentiment:
    - **≥ 70**: Bullish (strong buy conditions).
    - **≤ 30**: Bearish (strong sell conditions).
    - **30-70**: Neutral or no clear trend.
- **Buy/Sell Arrows**:
  - **Green Arrow**: Potential buy signal (score ≥ 85).
  - **Red Arrow**: Potential sell signal (score ≤ 15).

### 3. **Customization**
The indicator includes several adjustable inputs for personalization:
- RSI length, smoothing factors, LSMA length, and more.
- Enable or disable the Stochastic RSI component.

---

## Input Parameters

| Parameter            | Description                                   | Default Value |
|----------------------|-----------------------------------------------|---------------|
| `Phx Master (n1)`    | Main calculation period for TCI and TSI.      | 9             |
| `Phx Time 1 (n2)`    | Period for smoothing Williams %R.            | 6             |
| `Phx Time 2 (n3)`    | Period for Money Flow calculation.           | 3             |
| `LSMA Length (n4)`   | Lookback period for LSMA.                    | 32            |
| `RSI Length`         | Length for RSI calculations.                 | 14            |
| `Stochastic RSI`     | Enable/disable Stochastic RSI.               | Disabled      |
| `Stoch %K`           | Smoothing period for %K in Stochastic RSI.   | 3             |
| `Stoch %D`           | Smoothing period for %D in Stochastic RSI.   | 3             |

---

## Example Chart

Here’s an example of how the Phoenix Confidence Indicator looks in action:

![Phoenix Confidence Indicator Example](https://your-image-link-here)  
*(Replace with a screenshot of the indicator applied to a chart)*

---

## License

This project is licensed under the **[Mozilla Public License 2.0](https://mozilla.org/MPL/2.0/)**.

---

## Contributing

We welcome contributions to improve this indicator. Please submit a pull request or open an issue if you find a bug or have suggestions for enhancements.

---

## Disclaimer

The Phoenix Confidence Indicator is designed as a trading tool to assist in decision-making. It should not be used as the sole basis for any financial decision. Always perform your own analysis and consider market conditions. Trading carries inherent risks, and past performance is not indicative of future results.
