# GeoStrength AI 

A machine learning project for predicting soil California Bearing Ratio (CBR) using geotechnical properties.

## Dataset
- 149 lateritic soil samples.
- Collected from highway projects in India.
- Seven input features: G, S, F, LL, PL, OMC and MDD.
- Target: CBR (%).

Source: MDPI Research Paper (2023).

### Models
- Linear Regression
- Random Forest
- Gradient Boosting

#### Model Performance

| Model | Mean R² | Mean RMSE |
| Linear Regression | 0.9717 | 0.8082 |
| Random Forest | 0.9215 | 1.3438 |
| Gradient Boosting | 0.9293 | 1.2508 |

Best-performing model: Linear Regression.

### Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn and Scikit-learn.

### Disclaimer
Trained on Indian soil data; predictions may vary across regions.

### Future Development
Web integration and further geotechnical applications.
