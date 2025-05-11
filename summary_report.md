
# Smart Factory Energy Forecasting Summary

## Dataset Overview
- Observations: 16857
- Features: 31
- Target: equipment_energy_consumption

## Modeling Results
|                  |    RMSE |     MAE |         R2 |
|:-----------------|--------:|--------:|-----------:|
| RandomForest     | 173.822 | 71.644  |  0.0636671 |
| LinearRegression | 178.041 | 74.3331 |  0.0176638 |
| XGBoost          | 184.443 | 85.3992 | -0.0542548 |

## Best Model: XGBoost
- Used for final prediction
- Feature importance plotted above

## Files Produced
- final_predictions.csv: Contains actual vs predicted energy consumption on test set
