# AutoML Leaderboard

| Best model   | name                                                         | model_type     | metric_type   |   metric_value |   train_time |
|:-------------|:-------------------------------------------------------------|:---------------|:--------------|---------------:|-------------:|
|              | [1_Baseline](1_Baseline/README.md)                           | Baseline       | logloss       |       0.803537 |         2.14 |
|              | [2_DecisionTree](2_DecisionTree/README.md)                   | Decision Tree  | logloss       |       0.697166 |        28.08 |
| **the best** | [3_Default_Xgboost](3_Default_Xgboost/README.md)             | Xgboost        | logloss       |       0.627087 |        30.8  |
|              | [4_Default_NeuralNetwork](4_Default_NeuralNetwork/README.md) | Neural Network | logloss       |       0.649007 |        39.25 |
|              | [5_Default_RandomForest](5_Default_RandomForest/README.md)   | Random Forest  | logloss       |       0.680462 |        13.81 |
|              | [Ensemble](Ensemble/README.md)                               | Ensemble       | logloss       |       0.627087 |         0.94 |

### AutoML Performance
![AutoML Performance](ldb_performance.png)

### AutoML Performance Boxplot
![AutoML Performance Boxplot](ldb_performance_boxplot.png)