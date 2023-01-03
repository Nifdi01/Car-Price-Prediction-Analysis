# Car-Price-Prediction-Analysis
## Linear Regession-based model for predicting vehicle prices
### Notebook
The notebook covers the concepts, such as data cleaning, analysis, visualization, and Machine Learning. 
This notebook uses the below listed libraries:
1. Pandas
2. Matplotlib
3. Seaborn
4. Scikit-learn
### Dataset
The dataset contains information about used cars. This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression in Machine Learning. <br />
[You can find the link for the dataset in here](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)

### Model
The purpose of the model is to accuractely predict the car prices from a given dataset. <br>
For the prediction part [LinearRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) model of Scikit-learn library was used. The errors of the model were calculated using [Mean Squared Error](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html), [Mean Absolute Error](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html#sklearn.metrics.mean_absolute_error), and [R2 Score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2_score.html#sklearn.metrics.r2_score)

### Results
The accuracy of the model is roughly 83 percent and the Mean Squared Error is 3.49 <br>
<img src="https://user-images.githubusercontent.com/87927314/210312022-ae06d780-30f6-4a4c-a1a5-7bc6fd187c0d.png" width="220" height="70">

The graph of the model in regards to actual car prices:

<img src="https://user-images.githubusercontent.com/87927314/210313067-77dc690a-25a4-4618-9257-5b26ed6c3a58.png" width="400" heigh="400">

### Credits
[The AI and DS Channel](https://www.youtube.com/@TheAIDSChannel)
