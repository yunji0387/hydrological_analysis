# Hydrological Data Analysis for Cedar Lake near Oleson Point, Manitoba
> Conducted using Manitoba Hydro's dataset

<a id="table-of-contents"></a>
## Table of Contents
<details close>
<summary><b>Sections Overview</b></summary>

- [Hydrological Data](#data)
- [Introduction](#intro)
- [Basic Data Summary](#data_summary)
- [Time Series Analysis](#time_series)
- [Arima Model Forecast](#arima_forecast)
- [Conclusion and Future Directions](#conclusion)

</details>

<a id="data"></a>
## Hydrological Data
- Date Range: 2022 Sep 22nd to 2023 Sep 28th
- **Dataset Source:** [Manitoba Hydro's Hydrological Data](https://www.hydro.mb.ca/hydrologicalData/static/stations/05KL701/station.html?v=20230928053337)
    
[Back to Table of Contents](#table-of-contents)

<a id="intro"></a>
## Introduction
In this study, we conduct a preliminary analysis and forecast using the hydrological data from Cedar Lake near Oleson Point station, provided by Manitoba Hydro.

[Back to Table of Contents](#table-of-contents)

<a id="data_summary"></a>
## Basic Data Summary
![data_summary](./images/data_summary.png)
*Figure: Summary statistics of the dataset showcasing various metrics for each variable.*

![correlation_matrix](./images/correlation_graph.png)
*Figure: Correlation matrix indicating relationships between different variables.*

[Back to Table of Contents](#table-of-contents)

<a id="time_series"></a>
## Time Series Analysis
In this section, we visualize the various hydrological parameters to understand their behavior over time.

![water_level_time_series](./images/water_level_time_series.png)
*Figure: Time series plot showcasing the variation in water levels over the specified period.*

![water_temperature_time_series](./images/water_temperature_time_series.png)
*Figure: Time series plot indicating the fluctuations in water temperature over time.*

![air_temperature_time_series](./images/air_temperature_time_series.png)
*Figure: Time series plot of air temperature variations throughout the period.*

![precipitation_time_series](./images/precipitation_time_series.png)
*Figure: Precipitation levels plotted against time, indicating rainfall patterns.*

![relative_humidity_time_series](./images/relative_humidity_time_series.png)
*Figure: Time series representation of relative humidity levels.*

![atmospheric_pressure_time_series](./images/atmospheric_pressure_time_series.png)
*Figure: Atmospheric pressure trends plotted over time.*

[Back to Table of Contents](#table-of-contents)

<a id="arima_forecast"></a>
## Arima Model Forecast 
The ARIMA model, known for its capability to predict based on autoregression, differencing, and moving average components, has been employed to forecast various hydrological parameters.

![arima_water_level_forecast](./images/arima_water_level_forecast.png)
*Figure: ARIMA-based forecast for water levels.*

![arima_water_temperature_forecast](./images/arima_water_temperature_forecast.png)
*Figure: ARIMA-based prediction for water temperature.*

![arima_air_temperature_forecast](./images/arima_air_temperature_forecast.png)
*Figure: Future air temperature trends using the ARIMA model.*

![arima_precipitation_forecast](./images/arima_precipitation_forecast.png)
*Figure: ARIMA model's forecast of precipitation patterns.*

![arima_relative_humidity_forecast](./images/arima_relative_humidity_forecast.png)
*Figure: Predicted relative humidity trends using ARIMA.*

![arima_atmospheric_pressure_forecast](./images/arima_atmospheric_pressure_forecast.png)
*Figure: Atmospheric pressure predictions based on the ARIMA model.*

[Back to Table of Contents](#table-of-contents)

<a id="conclusion"></a>
## Conclusion and Future Directions
The ARIMA forecasts provide valuable insights into the future behavior of various hydrological parameters. For further refinement, one could consider ensemble methods or deep learning models. Ongoing monitoring and periodic data update will also be crucial to ensure the forecasts remain relevant.

[Back to Table of Contents](#table-of-contents)
