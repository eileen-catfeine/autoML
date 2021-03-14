# Summary of 10_DecisionTree_BoostOnErrors

[<< Go back](../README.md)


## Decision Tree
- **n_jobs**: -1
- **criterion**: entropy
- **max_depth**: 2
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
| logloss   | 0.537526 |  nan        |
| auc       | 0.657905 |  nan        |
| f1        | 0.490566 |    0        |
| accuracy  | 0.745614 |    0.49876  |
| precision | 0.64     |    0.49876  |
| recall    | 1        |    0        |
| mcc       | 0.296212 |    0.402462 |


## Confusion matrix (at threshold=0.49876)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     154 |                       9 |
| Labeled as positive |                      49 |                      16 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
