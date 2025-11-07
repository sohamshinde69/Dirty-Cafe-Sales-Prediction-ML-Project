# Dirty-Cafe-Sales-Prediction-ML-Project

A complete data cleaning and machine learning project built using a real-world inspired café sales dataset containing missing, `UNKNOWN`, and `ERROR` values.

<br>
<br>
<h1>Attribute Information:</h1>
<br>
<br>
| Transaction_ID : string / integer : Unique identifier for each transaction record. Ensures every sale is traceable and prevents duplication. |
<br>
<br>
|  Transaction Date : datetime : The date of the transaction. Used for time-based analysis (e.g., daily sales trends). this column is dropped  |
<br>
<br>
|  Item  : categorical : The name of the product sold (e.g., Coffee , Sandwich , Salad , Cake , Juice , Smoothie , Cookie , Tea). May contain errors such as `UNKNOWN` or `ERROR`. |
<br>
<br>
| Quantity : numeric (int) : Number of units sold for that transaction. Some entries may be missing or marked `UNKNOWN`. |
<br>
<br>
| Price Per Unit : numeric (float) : Price per item . Used to compute total sales. May contain errors such as `UNKNOWN` or `ERROR`. |
<br>
<br>
| Total_Spent : numeric (float) : Calculated as `Quantity × Unit_Price`. Represents total value of the transaction. May contain errors such as `UNKNOWN` or `ERROR`. |
<br>
<br>
| Payment_Method : categorical : Payment type used (e.g., Cash, Card, Digital wallet). May help analyze customer preferences. May contain errors such as `UNKNOWN` or `ERROR`. |
<br>
<br>
| Location : categorical : location /method of sale eg(Takeaway , In-store ). |
<br>
<br>
<h2>Note:</h2> 
<br>

> Some columns contained invalid or missing values such as `ERROR` and `UNKNOWN`.
> These were cleaned using probabilistic imputation , mode and median replacement to ensure accurate analysis.
<br>
<br>
<h1>Libraries</h1>
<br>
Pandas
<br>
Numpy
<br>
Seaborn
<br>
Matplotlib
<br>
Sci-kit Learn
<br>
<br>
<h1>Algorithm</h1>
<br>
HistGradientBoosting Regressor (using it beacuse HistGradientBoostingRegressor is the only model that supports category dtype )
<br>
R2 score: 0.911
<br>
MAE: 0.742
<br>
RMSE: 1.749
<br>
<br>
<h2>Download link </h2>
https://www.kaggle.com/d
