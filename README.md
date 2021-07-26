## python-api-challenge
# Python API Homework - What's the Weather Like?

# Background
Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. So let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?"
Now, we know what you may be thinking: "Duh. It gets hotter..."
But, if pressed, how would you prove it?

# Considerations
Some units of measurements have been converted from Imperial to Metric for this project

# Obervations and Analysis for WeatherPy

The analysis shows that in the Southern Hemisphere the temperature rises relatively linearly as we approach the equator (Latitude of 0), there is a strong positive correlation between the temperature and the latitude is with an r-value of 0.814. Meanwhile in the Northern Hemisphere the temperature also rises somewhat linearly as we approach the equator, however it is only a moderately strong negative correlation between the temperature and the latitude with an r-value of 0.603. Therefore, we can infer that the temperature as we approach the equator rises, and we have more confidence in this data in the Southern Hemisphere than we do in the Northerm Hemisphere. It is worth considering the effect that the seasons are having on this data.

The findings from the data also shows that in both the Northern and Southern Hemisphere, the Humidity and cloudiness are relatively evenly distributed for the 500 cities around the world. There is no condfidence that the data shows any linear distribution in the Northern and Southern Hemispheres, with r-values of 0.041 and -0.173 for cloudiness respectively, and -0.011 and -0.140 for humidity respectively. With all r-values within 0.2 of 0, it clear that the data is not linearly distributed for either the Nothern and Southern Hemispheres. Again it is worth considering the effect that the seasons have on the humidity and cloudiness of any particular location, this is likely more of a bearing on these

Finally, the data shows that wind speed in both the Northern and Southern Hemispheres are also evenly distributed, with little to no evidence that latitude has any effect on the wind speed. The r-value for the linear regression for the Northern Hemisphere is -0.02 and -0.05 in the Southern Hemisphere. It is more likely that the wind speeds of any particular city would be more affected by the terrain, the rotation of the Earth, and the air pressure of a given location. While temperature does play a part on wind speed, it should be noted that the data gathers was discussing only the maximum temperature of the city itself, and wind speed is affected by changes in temperature, rather than max temperature. Without surrounding area data, and minimum temperature data, and wind direction data, it is hard to make any conclusions regarding the correlation between wind speed and latitude.
