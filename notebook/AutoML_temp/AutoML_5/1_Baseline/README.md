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

0.9 seconds

### Metric details
|           |            1 |    2 |    3 |   accuracy |    macro avg |   weighted avg |   logloss |
|:----------|-------------:|-----:|-----:|-----------:|-------------:|---------------:|----------:|
| precision |     0.691578 |    0 |    0 |   0.691578 |     0.230526 |       0.47828  |  0.799228 |
| recall    |     1        |    0 |    0 |   0.691578 |     0.333333 |       0.691578 |  0.799228 |
| f1-score  |     0.817672 |    0 |    0 |   0.691578 |     0.272557 |       0.565484 |  0.799228 |
| support   | 15241        | 4928 | 1869 |   0.691578 | 22038        |   22038        |  0.799228 |


## Confusion matrix
|              |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 1 |            15241 |                0 |                0 |
| Labeled as 2 |             4928 |                0 |                0 |
| Labeled as 3 |             1869 |                0 |                0 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
