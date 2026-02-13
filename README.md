**Project Overview**

The objective of this project is to analyze the relationship between market psychological states (Fear/Greed) and actual trader behavior on the Hyperliquid decentralized exchange. By cross-referencing trading history with sentiment indices, the project uncovers patterns in risk management, bias, and profitability to inform smarter trading strategies.

**Data Sourcing and Pipeline**

* Trading Data: Utilized historical trading logs for accounts, including Trade IDs, Size in USD, Direction (Buy/Sell), and Closed PnL.

* Sentiment Data: Utilized the Fear & Greed Index for daily historical records of market sentiment scores and classifications ranging from "Extreme Fear" to "Extreme Greed".

* Preprocessing: Standardized timestamps and normalized dates to align high-frequency trading data with daily sentiment scores.

**Technical Stack**
* Language: Python

* Data Analysis: Pandas, NumPy

* Visualization: Matplotlib, Seaborn, Plotly

* Machine Learning: Scikit-Learn (K-Means Clustering)

* Dashboarding: IPyWidgets
  
**To get this project running on your local machine:**

* Clone the repository:

* Install dependencies:

* Run the analysis:
* Open the TraderPerformancevsMarketSentiment.ipynb notebook in Jupyter or Google Colab to see the full data pipeline and interactive dashboard.
