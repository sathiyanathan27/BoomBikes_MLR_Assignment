# BoomBikes_MLR_Assignment
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- **Project Background:** This project aims to develop a predictive model for the demand of shared bikes in the American market. The model will be built using a dataset that includes various factors affecting daily bike demands. By understanding these factors and their influence on bike demand, the management of BoomBikes can make informed decisions to enhance their business strategy, improve customer satisfaction, and increase revenue post-COVID-19 lockdown.

- **Business Problem:** Bike-sharing systems provide a convenient, affordable, and eco-friendly transportation option for short trips within urban areas. These systems typically involve a network of bike docks where users can rent and return bikes. BoomBikes, a US-based bike-sharing provider, has faced a significant decline in revenue due to the COVID-19 pandemic. As lockdowns are lifted and normalcy returns, BoomBikes aims to understand the factors influencing bike demand to prepare for an expected surge in usage. By contracting a consulting company, BoomBikes intends to leverage data analytics to predict future bike demand accurately.

- **Dataset:**The service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Conclusions
So the rental count/Demand for bikes depends on the variables:yr,temp,hum,windspeed,season_summer,season_winter,mnth_July,mnth_September,weekday_Sunday, weathersit_Light Snow, weathersit_Mist & Cloudy

And the Best fit line's equation is as below
<br></br>
cnt= 0.223 +0.228(yr) +0.599(temp) -0.176(hum) -0.190(windspeed) +0.083(season_summer)+0.134(season_winter) -0.044(mnth_July) +0.092(mnth_September) -0.042(weekday_Sunday) -0.234(weathersit_Light Snow ) -0.051(weathersit_Mist & Cloudy)


## Technologies Used
- **Python:** 3.11.7


## Contact
Created by [@sathiyanathan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
