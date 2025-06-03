# Machine Learning

Model Used: RandomForestRegressor  
Features: CO, CO₂, NO₂, SO₂, O₃, PM2.5, PM10  
Target: AQI  

R² Score: ~0.91  
Mean Squared Error (MSE): ~63.6  

The model demonstrated high accuracy in predicting AQI using pollutant levels, with PM10 as the most impactful feature.

```python
from sklearn.ensemble import RandomForestRegressor

model = RandomForestRegressor()
model.fit(X_train, y_train)
y_pred = model.predict(X_test)
global-air-quality-2024/
├── Air_Quality_Analysis.ipynb
├── Air_Quality.csv
├── README.md
└── images/
