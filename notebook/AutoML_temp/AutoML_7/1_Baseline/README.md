# Summary of 1_Baseline

[<< Go back](../README.md)


## Baseline Classifier (Baseline)
- **n_jobs**: -1
- **num_class**: 3
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

1.0 seconds

### Metric details
|           |            1 |    2 |    3 |   accuracy |    macro avg |   weighted avg |   logloss |
|:----------|-------------:|-----:|-----:|-----------:|-------------:|---------------:|----------:|
| precision |     0.691442 |    0 |    0 |   0.691442 |     0.230481 |       0.478092 |  0.799602 |
| recall    |     1        |    0 |    0 |   0.691442 |     0.333333 |       0.691442 |  0.799602 |
| f1-score  |     0.817577 |    0 |    0 |   0.691442 |     0.272526 |       0.565307 |  0.799602 |
| support   | 15238        | 4926 | 1874 |   0.691442 | 22038        |   22038        |  0.799602 |


## Confusion matrix
|              |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 1 |            15238 |                0 |                0 |
| Labeled as 2 |             4926 |                0 |                0 |
| Labeled as 3 |             1874 |                0 |                0 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
