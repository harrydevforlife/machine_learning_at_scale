# K-Nearest Neighbors


## 1. k-NN
 - k-NN regression function for a data point x is:

 - k-NN classifacation function for 

 > Note: argmaxf(x) is x value for f(x) max

Quiz 1: k-NN for Classification 

 - If k = 1, line go over all point.
 - If k > 1, line go over center point (mean point).

Distance measures for discrete features
 
## 2. k-NN hyperparameters

- value of k
- feature nomalization
- distance measure
- weight the importance of different attributes

## 3. k-NN pros and cons

- pros
    - Simple to implement and interpret
    - No training (althought it is necessary to organize the traning data to find k efficently)
    - Can handle multi-classification problem naturally
- cons
    - Expensive computational cost to find NN
    - Requires all training data to be stored in the model
    - Performance can be affected by unbalanced data
    - Performance can be affected by multi-dimensional data

## 4. Improve k-NN efficiency


4.1. Some ways

    - Use special data structures like KD-Tree, Ball-Tree,..
    - Help to quickly find the k-NN
    - Reduce dimensionlity with feature selection/ extraction

    - Use prototype selection methods
        - Help reduce the amount of data 

    4.2. k-NN extentions Distance-weighted k-NN

    - Inverse of the squared distance between x and x(i).

## 5. k-NN and Bias-Variance trade-off

- Find a small point of test error. To improve error on test data.

## 6. Diagnostic bias/variance with learning curves

   - High bias
   - High variance 
   - Good bias-variance trade-off

6.1. Fixing bias-variance 

    - Increase the size of model (fix bias)
    - Collect more input features (fix bias)
    - Reduce or remove regularization (fix bias)
    - Collect more traning data (fix bias)
    - Use regularization (fix bias)
    - Reduce the number of features (select/extract) (fix bias)
    - Using ensemble models (fix bias)

## 7. Summary

- Use bias-variance trade-off to choose f(x) 

    >  Not too complicated but not too simple either.


## Aditional section
