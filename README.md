# Tesla-Model-3-Cabin-Pressure-Diagnostics
This project is for exploring the measure of pressure over a time/distance given inputs of accelration with G forces, location and barometric presssure in hPa

## Background
I purchased a 2018 Tesla Model 3 in 2022 and began to notice complaints from passengers having ear discomfort during trips greater than 30 minutes. After reading references to features of Tesla's having biodefense modes in other models, It prompted the thought that there may be a cabin air pressure differential causing these symptoms and sought ways to collect data to support or disprove my hypothesis. 


## Methods:

Data will be collected with a smart device capable of tracking:
* Acceleration with G-Forces
* Location data
* Barometric pressure.
* Time

Data will also be collected in increments of variable length, but with the intention of meeting 15-minute, 45-minute and possibly 60-minute collection periods to compare results across different time intervals as patterns may present themselves differently as the car acclimates to external and internal environmental variables such as heat, cooling and the expansion or contraction that follows, as well as heating and cooling effects on car seals. 

Finally, I will be using the following software to assist in my research:
* Python 3.10
* Matplotlib
* Pandas/Numpy/Scikit
* Jupyter Notebooks
* Pyphox for android <= Collection platform

-------------------------------------------
## Initial Results and associated parameters

### Out Data:
On 31 July 2022 I measured 1016 hPa ambient barometric pressure (1.- bar) outside the vehicle and proceeded to close the car with air recirulation engaged (*ON*). I noticed a slight pressure adjustment throughout the trip which lasted approximately 7-minutes. 

### Return Data:
Following a brief pause, I disengaged the air recirculation feature (*OFF*) and returned to the origin of the trip with no deviations and no major interruptions except for a brief pause at a red light lasting no more than 1-minute.

### Findings:
* The constants in this Trip's test were the vehicle, driver/driving style, break regression mode, trip route and colletion platform.
* The variables in this Trip's test were the air recirculation mode (*ON/OFF*) and time. Its also worth noting that because of traffic the distance may vary but only slightly (+/-400 meters).

In *figure 1.* below you will notice that when both data sets are superimposed there is a noticable mirrored pattern. This could indicate a correlation between terrain and pressure, or possible between acceleration and pressure.

![Figure 1: Trip data showcasing data mirror effect.](https://user-images.githubusercontent.com/67482591/182064678-569c0be4-1082-4815-9eca-25782f9f9cd5.png)

### Way Ahead:
The next trip will include a minimum of 40-minutes of collected data per leg (out and back) and parameters to support acceleration with g-forces, location, and barometric pressure hPa. 

The next body of data will hopefully illuminate any connection between the acceleration based data points barometric pressure. 
Factors outside of our control are precise measurements of discomfort for passengers. 

These tests will use the same individual for consistency while testing the current parameters before possibly expanding to other individuals.


