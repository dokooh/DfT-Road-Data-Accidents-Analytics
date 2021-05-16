# Summary of Ensemble

[<< Go back](../README.md)


## Ensemble structure
| Model             |   Weight |
|:------------------|---------:|
| 3_Default_Xgboost |        1 |

### Metric details
|           |            1 |           2 |           3 |   accuracy |    macro avg |   weighted avg |   logloss |
|:----------|-------------:|------------:|------------:|-----------:|-------------:|---------------:|----------:|
| precision |     0.782281 |    0.660222 |    0.911498 |   0.776568 |     0.784667 |       0.765945 |  0.478772 |
| recall    |     0.938521 |    0.32569  |    0.64473  |   0.776568 |     0.636314 |       0.776568 |  0.478772 |
| f1-score  |     0.853308 |    0.436201 |    0.755249 |   0.776568 |     0.681586 |       0.751721 |  0.478772 |
| support   | 15241        | 4928        | 1869        |   0.776568 | 22038        |   22038        |  0.478772 |


## Confusion matrix
|              |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 1 |            14304 |              825 |              112 |
| Labeled as 2 |             3318 |             1605 |                5 |
| Labeled as 3 |              663 |                1 |             1205 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
