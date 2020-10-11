# Office_Data_Application

As we can measure and record environmental variables and meters in an office zone, this repository aims to use machine learning models for data prediction.

Also, this repository will try some applications with the prediction outcomes or some physical models.



## Office dataset 

The dataset is from a office zone in Taiwan.

There are some meters recording the environmental variables every minute.

Here release the resample data from July 2020 to September 2020 for further applications.

![image](https://github.com/JackyWeng526/Office_Data_Application/blob/main/Images/Data_table.PNG)



## Occupancy schedule

There is a occupancy detector in the office zone.

We can record the raw data and plot the human position.

Also, we can use machine learning tools with the occupancy data to predict the occupancy schedule.

The prediction may attribute to physical or hybrid models for CO<sub>2</sub> or thermal comfort control.

![image](https://github.com/JackyWeng526/Office_Data_Application/blob/main/Images/Occ_sensor.png)

![image](https://github.com/JackyWeng526/Office_Data_Application/blob/main/Images/Occ_prediction.png)



## CO<sub>2</sub> prediction

We also use machine learning tools to predict the trend of CO<sub>2</sub> concentration directly.

![image](https://github.com/JackyWeng526/Office_Data_Application/blob/main/Images/CO2_prediction.png)



## Thermal comfort application

The indoor thermal conditions are also investigated.

An estimated method of MRT prediction in limit circumstance is provided.

We aim to apply the estimated MRT to thermal comfort control referring to the psychrometric chart.

Also, for other thermal comfort indice applications, we apply PET to estimate the occupants' thermal sensation and comfort zone.

![image](https://github.com/JackyWeng526/Office_Data_Application/blob/main/Images/MRT_prediction.png)

![image](https://github.com/JackyWeng526/Office_Data_Application/blob/main/Images/Psychart_application.png)

![image](https://github.com/JackyWeng526/Office_Data_Application/blob/main/Images/PET_application.png)

**The code of psychrometric chart mostly refers to the study of Teitelbaum et al.[1].

## Reference
[1]

E. Teitelbaum, P. Jayathissa, C. Miller, F. Meggers, Design with Comfort: Expanding the psychrometric chart with radiation and convection dimensions. Energy and Buildings 209, 10 (2020).<br>
https://github.com/buds-lab/psychrometric-chart-makeover

[2]

Ladybug tools<br>
https://github.com/ladybug-tools/ladybug-legacy/blob/master/src/Ladybug_Thermal%20Comfort%20Indices.py

[3]

T.-P. Lin, A. Matzarakis, Tourism climate and thermal comfort in Sun Moon Lake, Taiwan. International Journal of Biometeorology 52, 281-290 (2008).

[4]

Occpancy detector: AMGU 4241<br>
https://na.industrial.panasonic.com/whats-new/infrared-array-sensor-grid-eye-unit-amgu4241
