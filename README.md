# b3_stocks_data

This is a project for a portfolio of studies in Python and Data Science

## Goal
Return data from historical quotations and current cotation of a list of shares on the B3 stock exchange.


# USAGE

1.  Create a virtual env and install packages from requirements.txt

2. At the root folder of the project create a .env file like the example below:

```
SRC_PATH=c:\PATH\TO\YOUR\LOCAL\PROJECT\b3_stocks_data
STOCKS=ITUB4,PETR4,KBLN4,KNCR11,KNRI11
```
3. Download the historical dataset from the [B3's web site](https://www.b3.com.br/pt_br/market-data-e-indices/servicos-de-dados/market-data/historico/mercado-a-vista/series-historicas/) that you want to analyze

4. Place the Zip files, compressed, into **historical_data\dataset**