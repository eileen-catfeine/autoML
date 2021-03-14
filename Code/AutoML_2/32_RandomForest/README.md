# Summary of 32_RandomForest

[<< Go back](../README.md)


## Random Forest
- **n_jobs**: -1
- **criterion**: gini
- **max_features**: 0.8
- **min_samples_split**: 50
- **max_depth**: 3
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

6.5 seconds

## Metric details
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.531179 |  nan        |
| auc       | 0.718263 |  nan        |
| f1        | 0.540541 |    0.341637 |
| accuracy  | 0.75     |    0.439853 |
| precision | 0.653846 |    0.476432 |
| recall    | 1        |    0        |
| mcc       | 0.342478 |    0.419609 |


## Confusion matrix (at threshold=0.439853)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     149 |                      14 |
| Labeled as positive |                      43 |                      22 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)

[<< Go back](../README.md)
