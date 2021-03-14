# Summary of 10_DecisionTree

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
| logloss   | 0.523332 |  nan        |
| auc       | 0.658943 |  nan        |
| f1        | 0.486891 |    0        |
| accuracy  | 0.763158 |    0.498513 |
| precision | 0.703704 |    0.498513 |
| recall    | 1        |    0        |
| mcc       | 0.339847 |    0.498513 |


## Confusion matrix (at threshold=0.498513)
|                     |   Predicted as negative |   Predicted as positive |
|:--------------------|------------------------:|------------------------:|
| Labeled as negative |                     155 |                       8 |
| Labeled as positive |                      46 |                      19 |

## Learning curves
![Learning curves](learning_curves.png)

[<< Go back](../README.md)
