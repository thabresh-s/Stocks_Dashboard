# Stocks Dashboard

### Table of Content

[Run the App](#run-the-app)   
[Source File](#source-file)  
[Ressources](#Ressources)   


## Run the App

For Linux and MacOS, if venv activate the Python environment:

``` source /path/to/{venv name}/bin/activate ```

Run the Streamlit server:  

``` streamlit run main.py ```

## Source File

The portfolio is stored in the JSON file in ``` ./ressources/stocks.json ```. The file follow this structure:

```json
[
    {   
        "name": "Air Liquide",
        "symbol":"AI.PA",
        "quantity":10,
        "price":120.7,
        "desired_percentage":10
    },
    {   
        "name": "Airbus",
        "symbol":"AIR.PA",
        "quantity":20,
        "price":55,
        "desired_percentage":15
    },
    ...
]
```

## Ressources 

### yfinance

[yfinance](https://github.com/ranaroussi/yfinance) library to fetch the stocks data.

``` pip install yfinance ```

### Streamlit

[Streamlit](https://streamlit.io) librairy to generate the webserver as well as the dashboard's assets

``` pip install streamlit ```