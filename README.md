# Customer Data Analysis

This project is designed to help a company predict usage, sales and stock changes by utilizing time series data.
The project will contain the following:
  1. Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
  2. An evaluation of how the company’s stock price correlates to its Google Search traffic.
  3. A Prophet forecast model that can predict hourly user search traffic.
  4. A plot of a forecast for the company's future revenue.

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, HvPlot, Pathlib, Pystan, Prophet, Holoviews, Datetime, Numpy, Matplotlib
- **Framework:** JupyterLab, can also use VS Code
- **Operating Systems:** Microsoft Windows
---

## *Installation Guide*

****
- **1:** Install Jupyter Labs and run it from the terminal. Make sure that you make sure you have an up-to-date version of Python
 [Install and run JupyterLab:](https://jupyter.org/install)
- **2:** Copy URL of this repo
- **3:** Clone folder to this repo and open in jupyter labs
- **4:** Ensure that you have the imports correctly identified to download

---

## *Usage*

**Jupyter Lab**
- Running the code can be done in one of two ways:
    1. You can click the "play" button at the very top of the notebook.
    2. You can click shift + enter on each block of code to run each batch of code as you go through it. 
<img width="350" alt="run preview" src=https://github.com/supersilver1978/bitcoin_arbitrage/blob/main/Resources/run.png>

  ### *Final Product*

Trends: We were able to find trends in the current data by slicing search traffic by day of week, time of day and daily.
<img width="685" alt="date search" src="https://github.com/supersilver1978/customer_data_analysis/assets/126728866/4d2b2cff-9c8f-43bc-9093-b98e04a68f74">
<img width="713" alt="day of week" src="https://github.com/supersilver1978/customer_data_analysis/assets/126728866/8c5ad84e-5e4a-49c2-ba93-95685bc86a11">
<img width="706" alt="hour of day" src="https://github.com/supersilver1978/customer_data_analysis/assets/126728866/c8e1b87b-c856-4d71-abc2-8073e4887997">
<img width="713" alt="yearly" src="https://github.com/supersilver1978/customer_data_analysis/assets/126728866/29ac1fe0-3d93-45b7-ae7d-d02e23cfc5c4">

Forecasting: We then used the forecasting model to plot revenue and forecast it.
<img width="561" alt="daily_revenue" src="https://github.com/supersilver1978/customer_data_analysis/assets/126728866/9d5b90c1-6763-46f3-89c7-0c55e437a3e4">
<img width="758" alt="revenue_forecasting" src="https://github.com/supersilver1978/customer_data_analysis/assets/126728866/ad43091b-7fcd-45dc-9a96-c47df4b149c4">

Our forecasting models included ranges with average, upper and lower estimates.
<img width="592" alt="yhat" src="https://github.com/supersilver1978/customer_data_analysis/assets/126728866/366e7cdd-a780-4a82-b37f-f0caa74a1c09">

## *Contributor*

- Michelle Silver
- supersilver1978@hotmail.com

---

## *License*

This software is licensed under GNU General Public License v3.0. See the [LICENSE](https://github.com/djohnst914/Loan_Qualifier_New_Feature/blob/main/LICENSE) file for details. 
