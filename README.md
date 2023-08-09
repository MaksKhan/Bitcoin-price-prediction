# Bitcoin-price-prediction
HSE Bootcamp
# 🔉 Task
We had price of Bitcoin for every day since 2022. The task was to predict price for next week (July 2023).

 # 🔍 EDA 
 ## Plot with trends
 ![image](https://github.com/MaksKhan/Bitcoin-price-prediction/assets/72515541/7b22fc5f-7026-4169-8e6a-48e98c754dfa)

## 🍭 Price plot
Actual price, seasonality and other
![image](https://github.com/MaksKhan/Bitcoin-price-prediction/assets/72515541/6fb220c1-00ca-4f3f-967b-53d0e19bf0c9)

## ✍️ Detecting anomalies
Actually, there were too many anomalies, but these are the most influencing
![image](https://github.com/MaksKhan/Bitcoin-price-prediction/assets/72515541/961820cc-b468-4595-a60e-c2d5501081db)

# Training
## 🔱 How to train?
Backtest is something like cross-validation for timeseries. We predict validation data on first step and then we can use it on the second step

![image](https://github.com/MaksKhan/Bitcoin-price-prediction/assets/72515541/95488afc-dcc2-49ed-8f97-7a3b20b2f527)

## 🤖 Model
I was using ETNA library from Tinkoff. This library was designed special for timeseries tasks. Main advantages are simplicity and confidence in the absence of leakage.

🎯  Baseline is simple NaiveModel 

![image](https://github.com/MaksKhan/Bitcoin-price-prediction/assets/72515541/4daae9b3-a2ed-4d25-b649-0acfbc4e8255)
Result of Backtest

![image](https://github.com/MaksKhan/Bitcoin-price-prediction/assets/72515541/bea4f57c-b2c4-4f02-9c3a-967511fb6138)
More useful to think about errors.

# 📣 Result
💀 The competition took place in August 2023. However test data was from July 2023 (month before). So everyone could just find real price of Bitcoin and easily make submission.
And so many refused to continue to participate
