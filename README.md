# YULU-Business-Case-Hypothesis-Testing

Yulu, India's pioneering micro-mobility service provider, has embarked on a mission to
revolutionize daily commutes by offering unique, sustainable transportation solutions.
However, recent revenue setbacks have prompted Yulu to seek the expertise of a consulting
company to delve into the factors influencing the demand for their shared electric cycles,
specifically in the Indian market.

From Yulu's Perspective:
● Strategic Expansion: Yulu's decision to enter the Indian market is a strategic move to
expand its global footprint. Understanding the demand factors in this new market is
essential to tailor their services and strategies accordingly.
● Revenue Recovery: Yulu's recent revenue decline is a pressing concern. By analyzing the
factors affecting demand for shared electric cycles in the Indian market, they can make
informed adjustments to regain profitability.

Column Profiling:
● datetime: datetime
● season: season (1: spring, 2: summer, 3: fall, 4: winter)
● holiday : whether day is a holiday or not
● workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
● weather:
o 1: Clear, Few clouds, partly cloudy
o 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
o 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain +
Scattered clouds
o 4: Heavy Rain + Ice Pellets + Thunderstorm + Mist, Snow + Fog
● temp: temperature in Celsius
● atemp: feeling temperature in Celsius
● humidity: humidity
● windspeed: wind speed
● casual: count of casual users
● registered: count of registered users
● count: count of total rental bikes including both casual and registered

What is expected?
The company wants to know:
● Which variables are significant in predicting the demand for shared electric cycles in the
Indian market?
● How well those variables describe the electric cycle demands.
