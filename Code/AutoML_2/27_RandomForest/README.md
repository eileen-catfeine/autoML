# Summary of 27_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.7
- **min_samples_split**: 20
- **max_depth**: 7
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

10.0 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.541047 |  nan        |
| auc       | 0.700142 |  nan        |
| f1        | 0.522727 |    0.272091 |
| accuracy  | 0.758772 |    0.644474 |
| precision | 0.8125   |    0.644474 |
| recall    | 1        |    0        |
| mcc       | 0.320942 |    0.644474 |


## Confusion matrix (at threshold=0.644474)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     160 |                       3 |
| Labeled as positive |                      52 |                      13 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)

[<< Go back](../README.md)
