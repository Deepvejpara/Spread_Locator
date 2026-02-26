## 📊 Project Title: Transactional Data Analysis & Statistical Modeling
#### 📝 Project Overview

This project involves a comprehensive analysis of a financial transaction dataset. The goal was to perform Exploratory Data Analysis (EDA), understand the distribution of transaction values, and apply statistical concepts like Q-Q Plots and Probability Distributions to determine the nature of the data.
---
#### 📂 Dataset Description

The analysis was performed on dataset.csv, which contains simulated transaction records:
|Field Name |	Data Type	| Description|
|---|---|---|
|transaction_id	|UUID	|Unique identifier for each transaction record.|
|customer_id	|String	|Unique identifier for the customer.|
|transaction_amount|	Float|	The monetary value of the transaction.|
|transaction_date	|Date	|The date when the transaction occurred.|
|transaction_count|	Integer	|Number of transactions associated with the entry.|
|region	|String|	Geographical area (North, South, East, West).|
|transaction_status	|String	|Status of the payment (Success or Fail).|
---
#### 🛠️ Tech Stack & Tools

   * 🐍 Programming: Python (Jupyter Notebook)

   * 🧪 Libraries: Pandas, Matplotlib, Seaborn, Scipy

   *  📊 Concepts: Statistical Distributions, Quantile-Quantile (Q-Q) Plots

---
#### 🚀 Key Features & Analysis

    * 📈 Statistical Theory: Detailed explanation of probability distributions and their "shapes" in the data.

    * 🔍 Data Validation: Using Q-Q Plots to compare dataset quantiles against theoretical distributions to check for normality.

    * 🧹 Data Handling: Loading and inspecting transactional data for regional and status-based trends.

    * 📉 Visualization: Graphical representation of data spread and outliers using Python-based plotting tools.
---
#### 💡 Key Insights & Findings

    * Distribution Analysis: By utilizing the Spread Locator notebook, the project identifies whether the transaction amounts follow a Normal, Skewed, or Uniform distribution.

    * Regional Performance: Analysis of the region and transaction_status columns allows for identifying which areas have higher failure rates.

    * Probability Mapping: The use of Q-Q plots helps confirm if the financial data is reliable for further predictive modeling.
