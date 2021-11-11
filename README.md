# README

This repo serves as the code implementation (python part) of the project assigned in the module Internet of Things ELEC0130.

# Description

The objective of the project is to bring an IoT based building management system (BMS) to the Hursley House to constantly monitor the environmental conditions such as climate, lightning and so on. There records can then be used to calculate the energy consumption or predict the usage condition of the building. In this project, we focus on the forecast of occupancy status of each room based on the temperature, humidity and light level recorded by the sensors. Although this “occupancy” information can be provided by the room booking system according to booking schedule, that is so say a room will appear to be “occupied” if a specific event has been scheduled to take place in that room, the records are completely independent from the sensor readings. By comparison of the forecast and true status, many insights could be provided. For example, is it efficient enough to predict the room activities merely based on the environmental sensor readings? Which attributes are most valuable in such prediction?

# Results

|   Model   | Train Accuracy | Test Accuracy | Elapsed Time |
| :-------: | :------------: | :-----------: | :----------: |
| LinearSVM |     87.2%      |     87.2%     |   00:10:15   |
|    RF     |     99.9%      |     93.9%     |   00:27:19   |

# Having problems?

If you run into problems, please either file a github issue or send an email to uceewta@ucl.ac.uk.
