# Structural Alignment Profiling (Natural Disaster Detection)
## Introduction
Natural disaster like Earthquakes, floods, tornados etc. are common in various parts of the world, which result in loss of many lives. So it is essential to capture and interpret the physical indicators of such events in order to provide timely warnings.
## Idea
- Our solution can be used in cities comprising of skyscrapers. We will measure the relative vertical tilt of different parts of the building, using gyroscope and accelerometer. 
- All the sensors will be calibrated to be in sync with each other. In normal conditions, the difference in readings of each sensor will be negligible. These initial values along with some experimental data will be used to set a threshold value. 
- All the sensors will send data to a local master device, which will interpret any anomalies in the readings. If the building experiences vibrations or unusual tilt, the readings among sensors will be relatively different. 
- If this mismatch in readings crosses the pre-defined threshold, appropriate warnings messages will be broadcasted across suitable media. 
## Scalability
This idea can be scaled to work for multiple buildings in the same vicinity. The local master devices installed in each building will be in sync with each other.
