# Temperature-and-Vibration-Monitoring
Problem Statement:
Temperature and Vibration monitoring is crucial to industrial production processes. An undetected anomaly could cost millions. With an industrial temperature monitoring (Android/IoS application) system based on IoT technology, the production process can be tightly controlled.

Solution:
Interfacing MPU6050 (for the accelerometer and gyroscope applications) and LM35 (for temperature measurement) with WeMos D1, we have designed a system for monitoring the production process in industries for temperature and vibration measurement.

The data from both the sensors (that are the three vectors each of accelerometer and gyroscope, and the temperature) are uploaded to the cloud (here, ThingSpeak) where the data are compiled into graphs based on different fields (we have selected). Another graph was added to the cloud that was the 2D plot of the data from the MATLAB code.

The plots shown in the cloud are uploaded in a third-party application, Virtuino. In case of threshold, an email or SMS or a call is sent to the specified authority.
