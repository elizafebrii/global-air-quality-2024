# Global Air Quality (2024) Analysis

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project presents a data analysis of air quality across 6 major global cities in the year 2024.  
The analysis is conducted using Python in a Jupyter Notebook and is based on real-world air quality measurements.

## Project Overview

Air pollution causes around 7 million premature deaths annually (WHO).  
This project investigates:

- Variations in air quality across cities and months  
- PM2.5 and PM10 trends  
- Pollution levels during specific time periods  
- City-by-city comparisons to highlight pollution disparities  
- Feature correlation with AQI  
- Machine learning to predict AQI  

## Dataset

- **Source**: [Kaggle – Global Air Quality (2024)](https://www.kaggle.com/datasets/youssefelebiary/air-quality-2024)  
- **Cities Analyzed**: London, Delhi, Sydney, Dubai, Cairo, Brasília  
- **Records**: 52,000+  
- **Parameters Tracked**:
  - PM2.5  
  - PM10  
  - CO  
  - CO₂  
  - NO₂  
  - SO₂  
  - O₃  
  - AQI (European Standard)

## Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  
- Scikit-learn  
- Jupyter Notebook  

## Key Insights

- **Delhi** showed the highest levels of PM2.5 and PM10 throughout 2024  
- **Cairo** and **Dubai** experienced frequent spikes in SO₂ and NO₂  
- **London** and **Sydney** had consistently low AQI levels  
- **PM2.5** had the strongest correlation with AQI  
- Machine learning revealed that **PM2.5** and **NO₂** were the top predictors of poor air quality  

## Machine Learning Results

| Model              | R² Score | MAE   | RMSE  |
|-------------------|----------|-------|-------|
| Linear Regression | 0.62     | 15.3  | 19.7  |
| Random Forest     | 0.88     | 7.2   | 10.1  |
| Decision Tree     | 0.80     | 9.4   | 12.5  |

**Random Forest Regressor** performed best overall in predicting AQI.

## Author

**Eliza Febriana** 
