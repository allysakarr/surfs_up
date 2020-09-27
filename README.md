# surfs_up
# Overview 
My example is that I want to open a surf shop in Hawaii. In order to do this, I need to do some analysis for an investor, called W. Avy, to determine which months are the most optimal for the surf shop business.

## Purpose
The purpose of this project is to analyze the temperatures from a weather dataset to build off the previous analysis. This analysis will be specfically for the months of June and December, which are the primary summer and winter months, respectively. From this data, W. Avy will have the information necessary to determine the predicted best months of business for the shop.

# Results
After using SQL Alchemy to filter out the temperatures for all of the months of June and all the months of December, the following were printed:

![JuneTemps.png](https://github.com/allysakarr/surfs_up/blob/master/JuneTemps.png?raw=true)
![DecTemps.png](https://github.com/allysakarr/surfs_up/blob/master/DecTemps.png?raw=true)

The following differences should be noted:
* The June Temperatures seem to be overall higher, especially when looking at 25%, 50% and 75% percentiles. These have an average of 4 degrees difference.
* The December temperatures have a particularly low minimum temperature of 56 degrees compared to June temperatures low of 64 degrees. 
* The average temperatures of the months of both June and December are 74.94 and 71.04 respectively. However, the standard deviation of the temperatures in the month of June is 3.25, which is slightly less than that of the temperatures in the month of December, which is 3.75. 

# Summary
This analysis shows that June would be the warmest month and probably the most ideal for surfing in terms of temperature. December is slightly colder, but the mininum temperature is substantially lower than that of June, meaning that when it is chilly during December, it could be considered too cold. The standard deviation of the temperatures in the month of December is also slightly higher, meaning that during the months of December, the temperature is likely to be more variable.

The months of June have higher temperatures and more consistent temperatures. According to this analysis, I would conclude that the June months would be the more ideal months of business for the surf shop if we are purely looking at the temperature data. 
