# Covid19-New-Cases

# Covid
-COVID-19, short for "Coronavirus Disease 2019," is an infectious disease caused by the novel coronavirus SARS-CoV-2. It was first identified in December 2019 in the city of Wuhan, Hubei province, China. COVID-19 has since spread globally, leading to a pandemic as declared by the World Health Organization (WHO) in March 2020.

# Description
- Create a deep learning model using LSTM neural network to predict new cases in Malaysia using the past 30 days of number cases.

# About the Dataset:
Dataset used from https://github.com/MoH-Malaysia/covid19-public

There are 2 dataset were used:-
1. cases_malaysia_train.csv(680 rows and 31 columns)
2. cases_malaysia_test.csv(100 rows and 31 columns)

For this project is to predict 'cases_new' column based on past 30 days. There are a few missing data nad symbol was found. Data cleaning process was applied.

# Deep learning model wit LSTM

![image](https://github.com/aimandnsh/Covid19-New-Cases/assets/150990001/911ceb23-e52d-4b77-84be-9ba2b9a13faa)

![image](https://github.com/aimandnsh/Covid19-New-Cases/assets/150990001/d55ed656-17d4-4291-b941-490588077a39)

# Result

![image](https://github.com/aimandnsh/Covid19-New-Cases/assets/150990001/11318b27-8415-4207-8fa0-53786a8acac2)

By using the LSTM model created above, able to achieve 0.17% for Mean Absolute Percentage Error (MAPE).

![image](https://github.com/aimandnsh/Covid19-New-Cases/assets/150990001/da33822c-a100-47f1-b753-137fafc6c4e8)

