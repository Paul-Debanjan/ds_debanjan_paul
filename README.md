# Trader Performance vs Bitcoin Market Sentiment

This project analyzes the relationship between trader performance (profitability, risk, volume, leverage)  
and the Bitcoin Fear & Greed Index. The goal is to uncover hidden patterns that can drive smarter trading strategies.

---

## Workflow
1. **Data Preparation**  
   - Load Fear & Greed Index and Hyperliquid trading history.  
   - Clean timestamps, map sentiment, normalize trading metrics.

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of sentiment states  
   - Correlation heatmaps  
   - Profitability across sentiment classes  

3. **Objective Analysis**  
   - Alignment/divergence of trading behavior with sentiment  
   - Risk, volume, leverage analysis  
   - Profit probability by sentiment  

4. **Reporting**  
   - All charts stored in `outputs/`  
   - Final PDF summary: `ds_report.pdf`

---

## How to Run
- Open Google Colab  
- Mount your repo or Google Drive  
- Run `notebook_1.ipynb` step by step  
- Outputs will be saved in `/outputs` and `ds_report.pdf`  

---

## Tools & Libraries
- Python (Pandas, NumPy)  
- Matplotlib, Seaborn (visualizations)  
- ReportLab (PDF report generation)  
- Google Colab (execution environment)

---

## Insights
- Trading performance shows biases under Extreme Fear/Greed.  
- Risk and volatility increase during high sentiment extremes.  
- Profitability can improve in Fear-dominated markets with cautious leverage.  

---

## Author
- Debanjan Paul  
- Repository maintained for Data Science assignment.
