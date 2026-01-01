# Trader Behavior vs Market Sentiment Analysis

This repository contains the submission for the Data Science assignment analyzing the relationship between trader behavior and Bitcoin market sentiment using historical trading data and the Fear & Greed Index.

---

## 📂 Project Structure

```
ds_bawa_chauhan/
├── notebook_1.ipynb # Main Google Colab notebook (core analysis)
├── notebook_2.ipynb # Optional (not used unless extended analysis added)
├── csv_files/ # Processed and intermediate datasets
│ ├── merged_data.csv
│ └── summary_metrics.csv
├── outputs/ # Saved charts and visualizations
│ ├── avg_pnl_by_sentiment.png
│ ├── avg_volume_by_sentiment.png
│ ├── winrate_by_sentiment.png
│ └── greed_risk_scatter.png
├── ds_report.pdf # Final summarized insights (1-page report)
└── README.md # Project overview and instructions
```

---

## ▶️ How to Run

- All analysis was performed using **Google Colab**
- Upload the provided CSV files to the Colab environment
- Run `notebook_1.ipynb` from top to bottom
- Required folders (`csv_files/`, `outputs/`) are auto-created within the notebook

---

## 📊 Analysis Overview

- Trader behavior is analyzed across **four market sentiment classes**:
  - Extreme Fear
  - Fear
  - Neutral
  - Greed
- Key metrics include profitability, trade volume, win rate, and risk exposure
- Visualizations and aggregated results are saved to the `outputs/` and `csv_files/` directories
- A secondary binary sentiment view is optionally derived for high-level comparison

---

## 📌 Data Sources & References

- **Historical Trader Data (Hyperliquid)**  
  Source: Provided via assignment (Google Drive link)

- **Bitcoin Fear & Greed Index**  
  Source: Provided via assignment (Google Drive link)

---

## ⚠️ Data Usage Disclaimer

All datasets used in this project are the property of their respective owners.  
They are used **strictly for educational, demonstration, and assignment purposes only**.

This project does not claim ownership of the data, nor does it intend any commercial use or redistribution.

---

## 📝 Notes

- This repository mirrors the exact structure used in the Google Colab submission
- All Colab notebooks are shared with **“Anyone with the link can view”** access
- The analysis emphasizes interpretability, reproducibility, and sentiment-aware insights
