# Analyzing Correlation Between Stocks and Cryptocurrencies
This project analyzes the correlation between major tech stocks (AMZN, AAPL, MSFT, NVDA, META) and two cryptocurrencies (BTC/USD and ETH/USD) over the course of 2023. The analysis compares linear relationships using Pearson correlation and monotonic relationships using Spearman correlation.

**📊 Stock and Cryptocurrency Correlation Analysis**
Welcome to the Stock and Cryptocurrency Correlation Analysis project! This repository explores the relationship between tech-heavy stocks like Apple and Microsoft and major cryptocurrencies like Bitcoin and Ethereum over the course of the year 2023. We use  statistical techniques like Pearson correlation and Spearman correlation to find out whether these assets move together and how they behave during different market conditions.

**🚀 Objective**
The aim of this project is to determine if there is a positive correlation between the stock market (Nasdaq) and major cryptocurrencies (Bitcoin, Ethereum) over a given period. This will help us understand if they react similarly to global events or move independently.

**🔍 Data Sources**
Stock Data: S&P 500, Nasdaq, and big tech stocks (AAPL, MSFT, AMZN, etc.) sourced via Alpaca API.
Crypto Data: Bitcoin (BTC), Ethereum (ETH) through the Alpaca API.
📅 Timeframe
The analysis covers the year of 2023 of bi-monthly data

**🛠 Preprocessing**
Aligning Timeframes: Adjusting stock market hours and 24/7 crypto data for accurate comparisons.
Handling Missing/Outlier Data: Filling in gaps of NaN's with the start data 
Data Transformation: We transformed the raw prices into daily returns and even tested log returns to minimize the effects of volatility.

**📊 Statistical Methods**
Pearson Correlation: Measures the linear relationship between stock and crypto returns. Is Bitcoin moving in sync with the S&P 500? Let’s find out!
Spearman Correlation: Helps when the relationship is non-linear. Great for handling volatile crypto markets.


**🖥 How to Use**
Clone the repo:

bash
Copy code
git clone https://github.com/yourusername/stock-crypto-correlation.git
cd stock-crypto-correlation
Install the requirements:

bash
Copy code
pip install -r requirements.txt
Run the analysis and generate visualizations:

Pearson/Spearman correlations
Rolling correlations
Heatmaps, scatter plots, and more!

**📈 Key Insights**
Bitcoin & Ethereum: A strong correlation of 0.88 shows these cryptos tend to move together.
Tech Stocks & Crypto: Weak correlations, with Microsoft (MSFT) showing the "strongest" connection to Bitcoin.


**🔮 Potential Insights**
Sector-Specific Correlations: Tech stocks show more correlation with cryptos than energy or finance stocks.
Divergence in Volatility: Stocks and crypto may decouple during times of market turmoil.
Crypto as a Safe Haven?: Does crypto serve as a hedge during stock market downturns?

**🛠 Features**
Pearson and Spearman correlation analysis.
Rolling correlations over time.

**✍️ Future Work**
Explore longer timeframes to see if patterns hold.
Look into sectoral correlations (tech vs. finance vs. crypto).
Compare with other asset classes like bonds or commodities.

**🤝 Contributing**
Feel free to fork the repository, open issues, or submit pull requests if you'd like to contribute or extend the project.

**🙌 Acknowledgements**
Data powered by the Alpaca API.
