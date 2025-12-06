# Gasoline-Prices-Increase-CS-668-Capstone-Project

## This is the template for the GitHub document of the CS 668 projects' course (Capstone Data Science Project) of the MS in Data Science at Pace University.

## Monica Hawkins

mh21492p@pace.edu

[🎬 Watch the demo video](https://drive.google.com/file/d/10Njw15ML6Mbobk9_7THzBzOO5fQvi8ar/view?usp=drive_link)

## Gasoline Price Increase Poster

https://github.com/Mohawkins/Gasoline-Prices-Increase-CS-668-Capstone-Project/blob/main/Gasoline_Price_Poster.jpg



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
Managerial implications and future research directions are also discussed



## Keywords 
 * Time Series Forecast, Gasoline Price, R Studio, ARIMA Models, Time Series Regression, Model Accuracy and Validation
            

## Research Question
   * How can we prevent the refinery from raising gas prices above 4.00
            
## Dataset
 This a U.S Natural Gas dataset that provide monthly summary of gas costs across the supple chain.  
           The dataset is available here:  https://www.eia.gov/dnav/ng/ng_pri_sum_dcu_nus_m.htm

## Methodology
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


  ## Economic Limitations
  
      
  
    
 
 *   <img width="780" height="521" alt="image" src="https://github.com/user-attachments/assets/6bdd752e-5db9-4e8b-a7b6-461c4197f8b1" />

   Hurricane Katrina in late August, we are reminded of just how important gasoline, diesel fuel,
   and other petroleum products are to the economy. Although hundreds of miles from the Gulf Coast, the Fifth
   District region quickly experienced gasoline shortages and soaring prices because of the damage 
   to oil production and refining facilities caused by the storm.

   
   Louisiana’s 17 oil refineries account for nearly one-fifth of the nation’s refining capacity 
           and can process about 3.4 million barrels of crude a day, according to the Energy Information Administration
           Louisiana is the largest that hold gasoline.


 <img width="440" height="288" alt="image" src="https://github.com/user-attachments/assets/ff2243fb-3108-43b2-b1ca-a1faddad3cbc" />

 Increase:  Within a month after Katrina’s landfall, another major storm, Hurricane Rita, pounded Louisiana and Texas.
             Ten days after Rita came ashore, retail gasoline prices were back above $3.00 per gallon.

             
  ## Conclusions
  * Following the substantial gasoline price increases seen during the spring, summer, and periods of national disaster, consumers are increasingly considering alternatives—most notably, new energy vehicles (NEVs). The significant increase in gasoline prices has the potential to drive consumers toward the adoption of new energy vehicles. However, the reduction in government subsidies may impede consumer behavior toward switching, and the inadequate charging infrastructure in China may also act as a barrier to consumer adoption. The combination of these factors could potentially impact consumer decision making. This study is helpful in analyzing the mechanisms that may affect consumers’ switching to new energy vehicles and in understanding and predicting the changing trends of consumers’ switching intention to new energy vehicles under the impact of multiple factors, which may provide effective countermeasures for the future formulation of relevant policy measures to accelerate the development of new energy vehicles. The SCT modeling results showed that personal factors had a significant positive impact on consumers’ willingness to switch from owning no vehicle or owning a traditional gasoline vehicle to adopting a new energy vehicle. Some variables related to environmental factors had a negative impact on the switching intention.

  * <img width="606" height="367" alt="image" src="https://github.com/user-attachments/assets/d6b67475-753d-4e17-baa3-3e6dcad72b7e" />





 
           
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

* Lacy, R. 2005. Hurricane Katrina Disrupts District Economy. Region Focus, Fall 2005, Federal Reserve Bank of Richmond, 51–59. Retrieved from https://www.richmondfed.org/-/media/RichmondFedOrg/publications/research/econ_focus/2005/fall/pdf/economic_developments.pdf

* CHEN, LONG, XIAOKUN LIU, AND PENG JING. 2023. Do Unprecedented Gasoline Prices Affect the Consumer Switching to New Energy Vehicles? An Integrated Social Cognitive Theory Model. Sustainability 15, 10, Article 8030 (May 2023), 19 pages. DOI: https://doi.org/10.3390/su15108030







 


            




    



