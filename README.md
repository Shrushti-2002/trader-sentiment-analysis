📊 Trader Behavior Analysis Based on Market Sentiment

📌 Project Overview

This project analyzes how market sentiment, represented by the Fear & Greed Index, impacts trader performance and behavior using historical trading data. The goal is to understand whether trader profitability, activity, and risk-taking behavior vary across different sentiment regimes such as Fear and Greed.

This analysis was completed as part of a Data Science Intern assignment and focuses on producing actionable insights rather than predictive modeling.

📁 Datasets Used

1️⃣ Historical Trading Data ([historical_data.csv](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing))

Contains detailed trade-level information including:

Trader account

Trade size and direction

Execution timestamps

Closed profit and loss (PnL)

2️⃣ Market Sentiment Data ([fear_greed_index.csv](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing))

Contains daily market sentiment indicators:

Sentiment value

Sentiment classification (Fear, Greed, Extreme Fear, Extreme Greed)

Date

🧹 Data Preparation

Converted timestamps to datetime format

Aggregated trade data at a daily level

Merged trading data with sentiment data using date as the key

Validated data for missing values and inconsistencies

📈 Analysis Performed

1️⃣ Trader Performance vs Market Sentiment

Compared Closed PnL distributions across sentiment regimes

Observed higher volatility during Fear periods and improved performance during Greed phases

2️⃣ Trading Activity by Sentiment

Calculated average number of trades per day under each sentiment classification

Found increased activity during Greed and Extreme Greed periods

3️⃣ Risk-Taking Behavior

Analyzed average position size as a proxy for leverage

Identified risk-off behavior during Fear and larger positions during Greed

📊 Visualizations

The following visualizations were created to support the analysis:

Boxplot: Closed PnL vs Market Sentiment

Bar Chart: Average Trades per Day vs Sentiment

Bar Chart: Average Position Size vs Sentiment

These charts highlight how trader behavior adapts to changing market conditions.

💡 Key Insights

Trader profitability is more stable during Greed phases and more volatile during Fear periods

Trading frequency increases when market sentiment is positive

Traders reduce position sizes during Fear, indicating defensive behavior

🛠️ Tools & Technologies

Python

Pandas

Matplotlib

Google Colab

📌 How to Run the Project

Clone the repository

Install required libraries:

pip install pandas matplotlib

Open and run the Jupyter Notebook to reproduce the analysis and visualizations
