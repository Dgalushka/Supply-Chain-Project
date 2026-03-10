# Supply Chain Analysis & Demand Forecasting

## Overview
Analysis of 180,000+ supply chain transactions to identify 
inventory inefficiencies and forecast weekly order demand. 
Built a demand forecasting model achieving ~5% mean error, 
applicable to replenishment planning and stock optimisation.

## Dataset
DataCo Supply Chain Dataset - 180,519 orders across multiple 
regions, product categories, and shipping modes (2015–2018).

## What's Inside
- **Data cleaning & preparation** - handling nulls, duplicates, 
  column standardisation, outlier removal
- **Exploratory Data Analysis** - delivery performance, regional 
  trends, order patterns over time
- **ABC Inventory Analysis** - categorised 118 products by revenue 
  contribution (A/B/C), identifying that 7 products drive ~77% 
  of total revenue
- **Demand Forecasting** - Facebook Prophet model on weekly order 
  data, achieving MAE of ~122 units (~5% of mean weekly demand)

## Key Results
| Metric | Value |
|--------|-------|
| Model | Facebook Prophet |
| MAE | 122 units/week |
| Mean weekly demand | ~2,485 units |
| Relative error | ~4.9% |

## Tech Stack
Python · Pandas · Prophet · Scikit-learn · Plotly · Seaborn

<img width="1288" height="560" alt="image" src="https://github.com/user-attachments/assets/9fab773b-9406-4126-908d-ecc61fe04111" />

## Next Steps
- Investigate 2018 demand drop and retrain model on post-drop data
- Build classification model for late delivery / fraud prediction
