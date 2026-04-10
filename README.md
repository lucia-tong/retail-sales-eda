# Retail Sales EDA — Istanbul Shopping Centers

An exploratory data analysis (EDA) of nearly 100,000 sales transactions across shopping malls in Istanbul (2021–2022). Developed as part of the Master’s in Data & AI — Nuclio Digital School.

## Key Features

* Revenue Calculation: Computes the total income generated across all sales transactions.
* Leaderboard Identification: Pinpoints the highest-grossing shopping centers and product categories.
* Peak Activity Tracking: Identifies the specific date with the highest sales volume and the top-spending customer.
* Market Share Analysis: Calculates the percentage distribution of sales by category.
* Temporal Trends: Analyzes the peak day of the week for sales for each individual shopping mall.

## Project Structure

```
retail/
├── data/
│   └── datos_ventas_centros_comerciales.csv  # Dataset 
├── retail.ipynb                    # Notebook 
└── README.md                                
```

## Installation & Usage

```bash
pip install pandas jupyter
jupyter notebook retail.ipynb
```

## Key Insights

* Total Revenue: ~1.49 billion.
* Top Performing Mall: Mall of Istanbul.
* Leading Category: Clothing (accounting for 34.5% of total revenue).
* Highest Price Point: Found within the Toys category.
* Average Basket Size: 3 units per transaction.

## Tech Stack

Python · Pandas · Jupyter Notebook
