# MLP-MNIST-Digit-Classification
MNIST Handwritten Digit Classification using Multilayer Perceptron
<br>

### Hyper-parameters
>hidden layer sizes: (80,30,10)
>activation: tanh
>solver: sgd
>alpha: 1e-4
>verbose: 10
>random state: 1
>initial learning rate: 0.1
>batch size: 200
>maximum iterations: 50
<br>

### Classification Report

>### Train Data
>              precision    recall  f1-score   support
>
>           0       1.00      1.00      1.00      5923
>           1       1.00      1.00      1.00      6742
>           2       1.00      1.00      1.00      5958
>           3       1.00      1.00      1.00      6131
>           4       1.00      1.00      1.00      5842
>           5       1.00      1.00      1.00      5421
>           6       1.00      1.00      1.00      5918
>           7       1.00      1.00      1.00      6265
>           8       1.00      1.00      1.00      5851
>           9       1.00      1.00      1.00      5949
>
>    accuracy                           1.00     60000
>   macro avg       1.00      1.00      1.00     60000
>weighted avg       1.00      1.00      1.00     60000
>
>
>### Test Data
>              precision    recall  f1-score   support
>
>           0       0.98      0.99      0.99       980
>           1       0.99      0.99      0.99      1135
>           2       0.98      0.98      0.98      1032
>           3       0.96      0.98      0.97      1010
>           4       0.98      0.98      0.98       982
>           5       0.97      0.97      0.97       892
>           6       0.99      0.98      0.98       958
>           7       0.97      0.97      0.97      1028
>           8       0.97      0.96      0.97       974
>           9       0.97      0.96      0.97      1009
>
>    accuracy                           0.98     10000
>   macro avg       0.98      0.98      0.98     10000
>weighted avg       0.98      0.98      0.98     10000
