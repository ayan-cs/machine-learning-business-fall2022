# Assignment-1

## 1. Use [Carseats data](https://www.kaggle.com/huhao05133/carseats) to predict the sales based on select predictors following the steps:
- Step 1: Do exploratory analysis and comment on the findings.
- Step 2: You have learnt several ML algorithms so far, please use appropriate ML algorithms to fit model(s) to the data and choose the best model for prediction stating reason.

### Discussion

- Total number of instances = **400**
- Number of predictors = **10**
- Response variable = **Sales**
- Categorical features = **ShelveLoc**, **Urban** and **US**

PCA is applied on the dataset for the ease of visualization.

![Visualization in 3D](https://github.com/ayan-cs/mlb-msl7380-fall2022/blob/assignment_1/Image%20resources/q1_overall_viz.png)

#### Regression Outputs

![Linear Regression Output](https://github.com/ayan-cs/mlb-msl7380-fall2022/blob/assignment_1/Image%20resources/q1_linreg.png)

![Decision Tree Regressor Output](https://github.com/ayan-cs/mlb-msl7380-fall2022/blob/assignment_1/Image%20resources/q1_dtree.png)

---

## 2. Use the data given [here](https://www.kaggle.com/iabhishekofficial/mobile-price-classification) to predict the price range of mobiles based on select predictors following the steps:
- Step 1: Do exploratory analysis and comment on the findings.
- Step 2: You have learnt several ML algorithms so far, please use appropriate ML algorithms to fit model(s) to the data and choose the best model for prediction stating reason.

### Discussion

- Total number of instances = **2000**
- Number of Predictors = **20**
- Number of Classes = **3**
- Number of Categorical features = **6**

PCA has been applied for the ease of visualization of the dataset in 2D and 3D respectively.

![2D Visualization](https://github.com/ayan-cs/mlb-msl7380-fall2022/blob/assignment_1/Image%20resources/q2_overall_viz_2d.png)

![3D Visualization](https://github.com/ayan-cs/mlb-msl7380-fall2022/blob/assignment_1/Image%20resources/q2_overall_viz_3d.png)

#### Classification Outputs

Three classification algorithms have been applied using different hyperparameters and the best algorithm has been retained for the final prediction. The final prediction of the Test set is as below,

![3D Visualization of Prediction](https://github.com/ayan-cs/mlb-msl7380-fall2022/blob/assignment_1/Image%20resources/q2_prediction.png)