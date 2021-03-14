# Summary of 2_DecisionTree

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: gini
- **max_depth**: 4
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **shuffle**: True
 - **stratify**: True
 - **k_folds**: 5

## Optimized metric
logloss

## Training time

0.7 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.997019 |  nan        |
| auc       | 0.645588 |  nan        |
| f1        | 0.494297 |    0        |
| accuracy  | 0.736842 |    0.666667 |
| precision | 0.6      |    0.666667 |
| recall    | 1        |    0        |
| mcc       | 0.245805 |    0        |


## Confusion matrix (at threshold=0.666667)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     153 |                      10 |
| Labeled as positive |                      50 |                      15 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
