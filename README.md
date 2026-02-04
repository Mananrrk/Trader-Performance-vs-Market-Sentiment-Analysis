# Trader Performance vs Market Sentiment Analysis

This project analyzes how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and performance on the Hyperliquid platform. The analysis focuses on performance metrics, behavioral changes, trader segmentation, and actionable strategy insights.

---

## 🛠 Setup

### Requirements

The project is built using Python. To run the analysis, you will need the following libraries:

- **pandas**: Data manipulation and analysis
- **numpy**: Numerical computing
- **matplotlib**: Static visualizations
- **seaborn**: Statistical data visualization
- **scikit-learn**: Machine learning and clustering

You can install the required dependencies using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## 🚀 How to Run

1. **Download the Datasets**  
   Ensure you have both datasets provided in the assignment:
   - Bitcoin Market Sentiment (Fear/Greed)
   - Hyperliquid Historical Trader Data

2. **Storage**  
   Place the datasets anywhere on your local system (or Google Drive if using Google Colab).

3. **Open the Notebook**  
   Launch `analysis.ipynb`.

4. **Update Data Paths**  
   In the notebook section where data is loaded, copy the full path of both data files and paste them into the `read_csv()` function.

   **Example:**
   ```python
   sentiment = pd.read_csv("C:/Users/Name/Downloads/fear_greed.csv")
   trades = pd.read_csv("C:/Users/Name/Downloads/hyperliquid_trades.csv")
   ```
5. **Execute**  
   Run the notebook cells from top to bottom to:
   - Clean and align the datasets  
   - Generate performance and behavioral metrics  
   - Perform sentiment-based analysis  
   - Produce insights, strategy rules, and bonus models  
   - **Reproduce all results, tables, and charts used in the analysis**
## 📊 Output

The notebook produces a comprehensive suite of results, including:

- **Comparative Analysis**  
  Tables and charts comparing trader performance during Fear vs Greed regimes.

- **Trader Segmentation**  
  Categorization of traders based on their sensitivity to market sentiment.

- **Actionable Insights**  
  Specific strategy recommendations derived from historical behavioral patterns.

- **Advanced Modeling**  
  Optional predictive modeling and clustering results for future performance forecasting.

All results are fully reproducible through direct execution of the notebook.
## 📝 Notes

- **Granularity**  
  The analysis is performed at a daily granularity to align with the frequency of the Bitcoin Fear & Greed Index.

- **Scope**  
  Leverage-based analysis is excluded as the provided trader dataset does not contain leverage information.
## 👤 Author

**Manan Goyal**  
🔗 [GitHub](https://github.com/MananRRK)  
📧 mananmlzs@gmail.com  
📞 +91-7895296561
