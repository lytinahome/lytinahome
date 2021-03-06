# Loss function in Regression Problem

## Distance Based function
#### L1 distance MAE
#### L2 distance RMSE
#### Huber distance
reference:
[Distance Based Function in Julia Library](http://juliaml.github.io/LossFunctions.jl/stable/losses/distance/)

# Loss function in Classification Problem
#### Cross Entropy
- \sum \sum y_i,c \log(y'_i,c)

## Margin Based function
Margin-based loss functions are particularly useful for binary classification. In contrast to the distance-based losses, these do not care about the difference between true target and prediction. Instead they penalize predictions based on how well they agree with the sign of the target.

#### 0-1 loss function
#### perceptron loss function
#### hinge loss function

reference:
[Margin Based Function in Julia Library](http://juliaml.github.io/LossFunctions.jl/stable/losses/margin/)
