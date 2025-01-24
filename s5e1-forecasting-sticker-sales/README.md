# Forecasting Sticker Sales
For this challenge, you will be predicting multiple years worth of sales for various Kaggle-branded stickers from different fictitious stores in different (real!) countries. This dataset is completely synthetic, but contains many effects you see in real-world data, e.g., weekend and holiday effect, seasonality, etc.

## Evaluation
Submissions are evaluated using the [Mean Absolute Percentage Error (MAPE)](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_percentage_error.html).


## Files
* `train.csv` - the training set, which includes the sales data for each date-country-store-item combination.
* `test.csv` - the test set; your task is to predict the corresponding item sales (num_sold) for each date-country-store-item combination. 
    > Note the Public leaderboard is scored on the first year of the data, and the Private on the remaining.
* `sample_submission.csv` - a sample submission file in the correct format


## Citation
- Walter Reade and Elizabeth Park. [Forecasting Sticker Sales](https://kaggle.com/competitions/playground-series-s5e1), 2025. Kaggle. 

