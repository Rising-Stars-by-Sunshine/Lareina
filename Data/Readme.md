# Data
![flowchart](flowchart3.png)
*Figure: Flowchart of the dataset’s structure from [markmap.js](https://markmap.js.org/)*
## Description and why related to research
-  The "selected World Bank commodity price data" dataset on Kaggle includes monthly commodity prices from the World Bank's "pink sheet." Applications such as data collection, indexing, cointegration, inflation adjustments, and general economic analysis can all benefit from this data collection. The dataset focuses on nominal prices in USD and includes a wide range of goods. A few of the dataset's most important variables are the prices of crude oil (Brent, Dubai Fateh), coffee (Arabica and Robustas), tea (from Colombo, Kolkata, and Mombasa/Nairobi auctions), and sugar (from the United States, the European Union, and the world under the International Sugar Agreement).
-  This dataset is especially relevant to my study on predicting global sugar prices and identifying key events that affect sugar prices. It offers a thorough historical record of sugar prices, documenting fluctuations under various economic scenarios and world events. In-depth analysis, prediction models, and patterns or trends that could affect sugar prices around the world can be investigated using this dataset. Incorporating other commodities like oil, coffee, and tea can also provide light on broader economic issues that may affect sugar pricing. All things considered, the dataset is a useful resource for comprehending and forecasting global sugar price fluctuations within the framework of a larger commodity market.

## Data Source
[kaggle](https://www.kaggle.com/datasets)
## Data Dictionary
| Variable        | Meaning                        | Data Type | Unit | Range |
|-----------------|--------------------------------|-----------|------|-------|
| Date            | Date of the recorded sugar price| Date      | 1   | 1960-1-1 to 2022-12-1  |
| sugar_eu        | Europe sugar price              | Numeric   | $/kg    | 0.112215 to 0.783171    |
| sugar_us        | United States sugar price       | Numeric   | $/kg   | 0.116845 to 1.263247     |
| sugar_world     | World sugar price               | Categorical | $/kg  | 0.028700 to 1.237700    |


## Citation
-  Singh, U. (2023, May). Global Commodity Prices: Monthly Data (1960-2022). Www.kaggle.com. https://www.kaggle.com/datasets/utkarshx27/select-world-bank-commodity-price-data
