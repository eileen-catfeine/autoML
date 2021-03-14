# Summary of 2_DecisionTree_KMeansFeatures

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

0.6 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 1.06261  |       nan   |
| auc       | 0.64068  |       nan   |
| f1        | 0.494297 |         0   |
| accuracy  | 0.723684 |         0.8 |
| precision | 0.541667 |         0.8 |
| recall    | 1        |         0   |
| mcc       | 0.245805 |         0   |


## Confusion matrix (at threshold=0.8)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     152 |                      11 |
| Labeled as positive |                      52 |                      13 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
