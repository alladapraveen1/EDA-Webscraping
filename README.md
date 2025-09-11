# 📊 Web Scraping & Exploratory Data Analysis of Cryptocurrency

## 📌 Project Overview

This project focuses on **web scraping cryptocurrency market data** from [CoinMarketCap](https://coinmarketcap.com/) and performing **Exploratory Data Analysis (EDA)** to derive meaningful insights into market trends, volatility, and liquidity.

The workflow combines **data engineering (web scraping)** and **data science (EDA, visualization, and statistical analysis)** to uncover hidden patterns in the crypto market.

---

## 🎯 Problem Statement

The cryptocurrency market is vast, volatile, and rapidly evolving, making it challenging to:

* Identify **influential cryptocurrencies** (e.g., Bitcoin, Ethereum).
* Understand the **distribution and concentration of market capitalization**.
* Assess **liquidity** via 24h trading volumes.
* Measure **short-term volatility** using 24h/7d changes.
* Compare **stablecoins vs. non-stablecoins** in terms of market share.

---

## 🚀 Objectives

### 🔹 Web Scraping

* Automate data extraction using **Python (`requests`, `BeautifulSoup`)**.
* Handle **pagination & dynamic content** for complete data retrieval.
* Store data in **CSV/Excel** for further analysis.
* Preprocess & clean raw data for **analysis readiness**.
* Enable **periodic scraping** for real-time updates.

### 🔹 EDA

* Perform **descriptive statistics** (mean, median, variance, skewness, kurtosis).
* Conduct **univariate, bivariate, and multivariate analysis**.
* Visualize trends with **histograms, boxplots, scatter plots, heatmaps, bubble charts, and KDE plots**.
* Identify **market dominance** (Bitcoin, Ethereum, Stablecoins).
* Provide **insights & recommendations** for investors/analysts.

---

## 📂 Dataset Overview

Scraped from **CoinMarketCap API/Pagination**.

| Feature              | Description                      |
| -------------------- | -------------------------------- |
| `Name`               | Cryptocurrency name              |
| `Symbol`             | Short code (e.g., BTC, ETH)      |
| `Price`              | Current price                    |
| `Market Cap`         | Total market capitalization      |
| `24h Change (%)`     | % change in last 24h             |
| `7d Change (%)`      | % change in last 7 days          |
| `Volume 24h`         | Total trading volume in last 24h |
| `Circulating Supply` | Coins available for trading      |

---

## 📊 Key Insights

* **Price Distribution**: Positively skewed (majority of coins are low-priced, few like BTC/ETH are extremely high).
* **Market Dominance**:

  * Bitcoin: **57.4%**
  * Ethereum: **13.7%**
  * Others: **28.9%**
* **Correlation Analysis**:

  * Price ↔ Market Cap: **Strong (0.97)**
  * Market Cap ↔ Volume 24h: **Moderate (0.51)**
  * Price ↔ Volume 24h: **Weak-to-Moderate (0.40)**
* **Outliers & Speculation**: Some moderate-cap coins show disproportionately high trading volumes, suggesting short-term hype.

---

## 📈 Visualizations

* **Histogram + KDE** → Price distribution (right-skewed).
* **Boxplot** → Outlier detection in prices/volumes.
* **Scatter Plot** → Market Cap vs. Volume (clusters of low-cap coins, BTC/ETH as outliers).
* **Bubble Chart** → Market Cap vs. Price (Volume as bubble size).
* **Heatmap** → Correlation between Price, Market Cap, and Volume.

---

## 🛠️ Tech Stack

* **Python**

  * `requests`, `BeautifulSoup` → Web scraping
  * `pandas`, `numpy` → Data processing
  * `matplotlib`, `seaborn` → Data visualization

* **Jupyter Notebook** → Implementation

* **PowerPoint** → Project Presentation

---

## 📌 Future Work

* Add **time-series analysis** to track historical trends.
* Perform **clustering/segmentation** to group stablecoins, speculative, and emerging coins.
* Automate with **scheduled scraping** & database integration.

---

## 📜 Files in Repository

* `Webscraping on Coin Market Cap.ipynb` → Code for web scraping + EDA.
* `Web Scraping & Exploratory Data Analysis of Crypto Currency.pptx` → Project presentation.
* `README.md` → Project documentation (this file).

---

## 🙌 Author

**Praveen Allada**
📧 \[alladapraveen1@gmail.com/www.linkedin.com/in/alladavdapraveenkumar/www.linkedin.com/in/alladavdapraveenkumar]

---

👉 Would you like me to also include **sample code snippets** from your notebook (like scraping & visualization functions) inside the README, so it looks more hands-on for GitHub?
