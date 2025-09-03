### EMAIL SPAM CLASSIFIER

# DATASET
The data used in this project is from: https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

# Model
For this classifier i tried multiple model for classification, and then chose to go with XGBoost which gives higher balance of f1 score. 86%

### METRICS
    | Algorithm | Accuracy  | Precision |
    |-----------|-----------|-----------|
    | SVC       | 0.972921  | 0.974138  |
    | KN        | 0.900387  | 1.000000  |
    | NB        | 0.959381  | 1.000000  |
    | DT        | 0.935203  | 0.838095  |
    | LR        | 0.951644  | 0.940000  |
    | RF        | 0.971954  | 1.000000  |
    | AdaBoost  | 0.924565  | 0.840909  |
    | BgC       | 0.958414  | 0.862595  |
    | ETC       | 0.972921  | 0.982456  |
    | GDBT      | 0.952611  | 0.923810  |
    | XGB       | 0.972921  | 0.929688  |

