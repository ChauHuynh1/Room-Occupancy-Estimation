# EEET2485_GroupProject

## Source:

Adarsh Pal Singh (IIIT Hyderabad, India): adarshpal.singh '@' alumni.iiit.ac.in
Dr. Sachin Chaudhari (IIIT Hyderabad, India): sachin.c '@' iiit.ac.in


## Data Set Information:

The experimental testbed for occupancy estimation was deployed in a 6m Ã— 4.6m room. The setup consisted of 7 sensor nodes and one edge node in a star configuration with the sensor nodes transmitting data to the edge every 30s using wireless transceivers. No HVAC systems were in use while the dataset was being collected.

Five different types of non-intrusive sensors were used in this experiment: temperature, light, sound, CO2 and digital passive infrared (PIR). The CO2, sound and PIR sensors needed manual calibration. For the CO2 sensor, zero-point calibration was manually done before its first use by keeping it in a clean environment for over 20 minutes and then pulling the calibration pin (HD pin) low for over 7s. The sound sensor is essentially a microphone with a variable-gain analog amplifier attached to it. Therefore, the output of this sensor is analog which is read by the microcontrollerâ€™s ADC in volts. The potentiometer tied to the gain of the amplifier was adjusted to ensure the highest sensitivity. The PIR sensor has two trimpots: one to tweak the sensitivity and the other to tweak the time for which the output stays high after detecting motion. Both of these were adjusted to the highest values. Sensor nodes S1-S4 consisted of temperature, light and sound sensors, S5 had a CO2 sensor and S6 and S7 had one PIR sensor each that were deployed on the ceiling ledges at an angle that maximized the sensorâ€™s field of view for motion detection.

The data was collected for a period of 4 days in a controlled manner with the occupancy in the room varying between 0 and 3 people. The ground truth of the occupancy count in the room was noted manually.

Please refer to our publications for more details.



## Attribute Information:

Date: YYYY/MM/DD
Time: HH:MM:SS
Temperature: In degree Celsius
Light: In Lux
Sound: In Volts (amplifier output read by ADC)
CO2: In PPM
CO2 Slope: Slope of CO2 values taken in a sliding window
PIR: Binary value conveying motion detection
Room_Occupancy_Count: Ground Truth


## Relevant Papers:

> - 1. Adarsh Pal Singh, Vivek Jain, Sachin Chaudhari, Frank Alexander Kraemer, Stefan Werner and Vishal Garg, â€œMachine Learning-Based Occupancy Estimation Using Multivariate Sensor Nodes,â€ in 2018 IEEE Globecom Workshops (GC Wkshps), 2018.
> - 2. Adarsh Pal Singh, 'Machine Learning for IoT Applications: Sensor Data Analytics and Data Reduction Techniques', Masters Thesis, [Web Link], 2020.



## Citation Request:

If you use this dataset in your research, please cite the following paper:
Adarsh Pal Singh, Vivek Jain, Sachin Chaudhari, Frank Alexander Kraemer, Stefan Werner and Vishal Garg, â€œMachine Learning-Based Occupancy Estimation Using Multivariate Sensor Nodes,â€ in 2018 IEEE Globecom Workshops (GC Wkshps), 2018.