# Summary of 57_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.01
- **explain_level**: 1

## Validation
 - **validation_type**: kfold
 - **k_folds**: 5
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

1.8 seconds

## Metric details
|           |    score |    threshold |
|:----------|---------:|-------------:|
| logloss   | 0.597188 | nan          |
| auc       | 0.624729 | nan          |
| f1        | 0.49697  |   0.323092   |
| accuracy  | 0.736842 |   0.539129   |
| precision | 0.777778 |   0.539129   |
| recall    | 1        |   0.00142412 |
| mcc       | 0.244559 |   0.323092   |


## Confusion matrix (at threshold=0.539129)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     161 |                       2 |
| Labeled as positive |                      58 |                       7 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)

[<< Go back](../README.md)
