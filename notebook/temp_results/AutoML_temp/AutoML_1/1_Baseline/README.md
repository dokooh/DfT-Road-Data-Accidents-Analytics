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

1.9 seconds

### Metric details
|           |            1 |    2 |    3 |   accuracy |    macro avg |   weighted avg |   logloss |
|:----------|-------------:|-----:|-----:|-----------:|-------------:|---------------:|----------:|
| precision |     0.690671 |    0 |    0 |   0.690671 |     0.230224 |       0.477026 |  0.800515 |
| recall    |     1        |    0 |    0 |   0.690671 |     0.333333 |       0.690671 |  0.800515 |
| f1-score  |     0.817037 |    0 |    0 |   0.690671 |     0.272346 |       0.564304 |  0.800515 |
| support   | 15221        | 4942 | 1875 |   0.690671 | 22038        |   22038        |  0.800515 |


## Confusion matrix
|              |   Predicted as 1 |   Predicted as 2 |   Predicted as 3 |
|:-------------|-----------------:|-----------------:|-----------------:|
| Labeled as 1 |            15221 |                0 |                0 |
| Labeled as 2 |             4942 |                0 |                0 |
| Labeled as 3 |             1875 |                0 |                0 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
