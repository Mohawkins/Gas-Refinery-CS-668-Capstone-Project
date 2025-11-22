# Gasoline-Prices-Increase-CS-668-Capstone-Project

## This is the template for the GitHub document of the CS 668 projects' course (Capstone Data Science Project) of the MS in Data Science at Pace University.

## Monica Hawkins

mh21492p@pace.edu

[🎬 Watch the demo video](https://drive.google.com/file/d/10Njw15ML6Mbobk9_7THzBzOO5fQvi8ar/view?usp=drive_link)


## Abstract 
  This research forecasts the gasoline price in U.S. and analyzes its managerial
implications by means of both univariate and multivariate time series forecasting
models. Gasoline price forecast is among the most difficulty time series variables
during its importance to the economy and extremely volatile nature. The average
regular gasoline price in U.S. reached $5.06 per gallon in the month of June 2022,
as opposed to $3.41 at the beginning of 2022, a 48% increase. While gasoline prices
had been rising over the first half of 2022 due to supply chain disruptions as a result
of global Covid 19 lockdowns and the Russia invasion of Ukraine since February
24, 2022, they then surprisingly came down in the second half of 2022 to $3.85 in
November 2022, which has caught many consumers and business organizations offguard. Both univariate time series forecasting models, such as exponential
smoothing and autoregressive integrated moving average, and multivariate time
series forecasting models, such as time series regression models, are used in this
research with the data for the period January 2002 through November 2022. We
find that the time series regression model with trend, season, GDP, CPI, and crude
oil price turns out the be the best forecasting model both on the training data and
the testing data, even with the testing data containing significant turning points.
Managerial implications and future research directions are also discusse

## Keywords 
 * Time Series Forecast, Gasoline Price, R Studio, ARIMA Models, Time Series Regression, Model Accuracy and Validation
            

## Research Question
   * How can we prevent the refinery from raising gas prices above 4.00
            
## Dataset
 This a U.S Natural Gas dataset that provide monthly summary of gas costs across the supple chain.  
           The dataset is available here:  https://www.eia.gov/dnav/ng/ng_pri_sum_dcu_nus_m.htm

## Methodolgy
Crude oil is located in regions that have been prone historically to political upheaval or have had their oil production disrupted due to political events. Several major oil price shocks have occurred at the same time as supply disruptions triggered by political events, most notably the Arab Oil Embargo in 1973-74, the Iranian revolution and Iran-Iraq war in the late 1970s and early 1980s, and Persian Gulf War in 1990. More recently, disruptions to supply (or curbs on potential development of resources) from political events have been seen in Nigeria, Venezuela, Russia, Iraq, Iran, and Libya.

 <img width="905" height="399" alt="image" src="https://github.com/user-attachments/assets/aa41e2bb-3355-4e2e-9fdc-dc47f4884124" />

* The chart plots the quarterly average crude oil price in real 2022 dollars per barrel over time.

     * X-axis: Time, represented by quarters (e.g., 1Q 1970, 4Q 2024).

     * Y-axis: Quarterly Average Crude Oil Price in real 2022 dollars, ranging from $0 to over $175 per barrel.

  Data Series: The gray line represents the price, specifically showing the West Texas 
  Intermediate (WTI) crude oil price and the Imported refiner acquisition cost of crude
  oil. Since they are plotted as a single line, they track each other closely.


  ## Results
 Forecast the average U.S. retail gasoline price to remain near $3.00 per gallon (gal) for the
remainder of 2025, resulting in an average 2025 price of $3.10/gal, a 6% decrease from 2024.
 In 2026, we forecast the average retail gasoline price to fall by 4% to just under $3.00/gal,
which would be the lowest annual average price since 2020. 

  <img width="662" height="356" alt="image" src="https://github.com/user-attachments/assets/7c3bde3b-f64a-40a6-ae03-effcad07fea7" />

  * Price of natural gas will average just over $13.80 per thousand cubic feet this winter, up 2% from last year.
  

  <img width="609" height="352" alt="image" src="https://github.com/user-attachments/assets/905f247f-4ec3-45e7-85e1-ff89fbf06fca" />


  ## Economic limitations

           * Production Shutdown: About 95% of the Gulf Coast's crude oil and gas production were shut down as Ida ravaged Louisiana, 
             according to energy research company S&P Global Platts. 

           *  Refinery: Louisiana’s 17 oil refineries account for nearly one-fifth of the nation’s refining capacity and 
              can process about 3.4 million barrels of crude a day, according to the Energy Information Administration. 
              Louisiana is the largest that hold gasoline.

     
      
     Working in Progess
    
 
   * <img width="780" height="521" alt="image" src="https://github.com/user-attachments/assets/6bdd752e-5db9-4e8b-a7b6-461c4197f8b1" />

  

  ## Reference
  
* He, Xin James. 2023. Forecasting Gasoline Price with Time Series Models. Communications of the IIMA 21, 1 (2023), Article 1. DOI:https://doi.org/10.58729/1941-6687.1440

* U.S. Energy Information Administration (EIA). n.d. What drives crude oil prices: Spot Prices. U.S. Energy Information Administration (EIA). Accessed 16 Nov 2025. https://www.eia.gov/finance/markets/crudeoil/spot_prices.php

* U.S. Energy Information Administration. 2025. Short-Term Energy Outlook (November 2025). U.S. Department of Energy.
  Retrieved November 17, 2025 from https://www.eia.gov/outlooks/steo/pdf/steo_text.pdf

*  Giberson, M. 2011. The Problem with Price Gouging Laws. Regulation, Spring 2011, Vol. 34, No. 1, 48–53. Retrieved
   November 21, 2025, from https://www.cato.org/regulation/spring-2011/problem-price-gouging-laws

*  Oil, gasoline prices head higher as Ida kicks hurricane season into a higher gear,” CNBC, Aug. 30, 2021. Retrieved Nov. 21, 2025, from https://www.cnbc.com/2021/08/30/oil-gasoline-prices-head-higher-as-ida-kicks-hurricane-season-into-a-higher-gear.html

* Sundby, A., Chau, N. B., Layne, R., Albert, V., & Dakss, B. 2021. Ida causes widespread damage and power outages along Louisiana coast. CBS News, August 31. Retrieved November 21, 2025 from https://www.cbsnews.com/live-updates/hurricane-ida-louisiana-damage-power-outages-2021-08-30/

* [1] Eric Morath. 2021. A Hurricane Ida economic impact: Louisiana’s 17 oil refineries account for one-fifth of U.S. capacity — and hundreds could be vulnerable to flooding. *Los Angeles Times*. Aug. 29, 2021. Retrieved Nov. 21, 2025 from https://www.latimes.com/business/story/2021-08-29/a-hurricane-ida-economic-impact#:~:text=Louisiana’s%2017%20oil%20refineries%20account,could%20be%20vulnerable%20to%20flooding.

            




    



