# covid-19-market-analysis

## About The Project
This project aims to analyse the impact of the virus on S&P 500 companies, Gold and Treasury.

A list of S&P 500 companies that is already in a table form is extracted and converted into dataframe.
```
url = 'https://en.wikipedia.org/wiki/List_of_S%26P_500_companies'
stocks_df = pd.read_html(url, header=0)[0]
stocks_df.head()
```
![](Images/list%20of%20s%26p500%20companies%20df.PNG)

With Covid-19 more deadly than any previous pandemic, investors had been jittery and sent S&P 500 tumbling down in March.

![](Images/march%20crash.png)

As part of the explanatory data analysis, a box and whisker plot was done to show the centre and spread of a distribution of the various GICs sectors. It was evident that health care sector displayed the highest outliers (highest positive percentage change in stock prices). The surge in its share price could be due to the reports on the positive data of the early stage of the coronavirus vaccine trials.

![](Images/GICS%20Sector%20box%20plot.png)

The U.S. data was extracted from FRED (Federal Reserve Economic Data) using web datareader. We could see that the U.S. unemployment rate soars to 14.7 percent, the worst since the Depression era.

![](Images/US%20labor%20market%20chart.png)

## Built With
* Python
* Google Sheets
* Google Finance
* Yahoo Finance
