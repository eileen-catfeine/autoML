# AutoML Leaderboard

| Best model   | name                                                         | model_type     | metric_type   |   metric_value |   train_time |   single_prediction_time |
|:-------------|:-------------------------------------------------------------|:---------------|:--------------|---------------:|-------------:|-------------------------:|
|              | [1_Linear](1_Linear/README.md)                               | Linear         | logloss       |       0.573976 |         9.57 |                   0.1013 |
|              | [2_Default_LightGBM](2_Default_LightGBM/README.md)           | LightGBM       | logloss       |       0.546221 |         2.99 |                   0.0899 |
|              | [3_Default_Xgboost](3_Default_Xgboost/README.md)             | Xgboost        | logloss       |       0.558709 |         4.04 |                   0.0795 |
| **the best** | [4_Default_CatBoost](4_Default_CatBoost/README.md)           | CatBoost       | logloss       |       0.529719 |         4.7  |                   0.0295 |
|              | [5_Default_NeuralNetwork](5_Default_NeuralNetwork/README.md) | Neural Network | logloss       |       0.707808 |         2.15 |                   0.1295 |
|              | [6_Default_RandomForest](6_Default_RandomForest/README.md)   | Random Forest  | logloss       |       0.540084 |         7.23 |                   0.0996 |
|              | [11_LightGBM](11_LightGBM/README.md)                         | LightGBM       | logloss       |       0.543665 |         3.24 |                   0.09   |
|              | [7_Xgboost](7_Xgboost/README.md)                             | Xgboost        | logloss       |       0.55016  |         3.82 |                   0.0811 |
|              | [15_CatBoost](15_CatBoost/README.md)                         | CatBoost       | logloss       |       0.539806 |         8.15 |                   0.0378 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)