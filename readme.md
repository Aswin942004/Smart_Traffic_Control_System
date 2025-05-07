<p align="center">
 <img height=200px src="./traffic-signal.jpg" alt="Traffic Signal Timer">
</p>

<h1 align="center">A Smart Traffic Control System</h1>

<div align="center">

[![Python version](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![License: Apache 2](https://img.shields.io/badge/License-Apache-yellow.svg)](https://www.apache.org/licenses/LICENSE-2.0)

<h4>A Smart Traffic Control System using OpenCV uses real-time video processing to detect and count vehicles at intersections. It dynamically adjusts signal timings to optimize traffic flow and reduce congestion.</h4>

</div>

-----------------------------------------
## Team Member Name

 1. Aswin A
 2. Sreejith MS
 3. Mohamed Afsar S

### Inspiration

* Traffic congestion is becoming one of the critical issues with the increasing population and automobiles in cities. Traffic jams not only cause extra delay and stress for the drivers but also increase fuel consumption and air pollution. 

* According to the [TomTom Traffic Index](https://www.tomtom.com/en_gb/traffic-index/ranking/), 3 of the top 10 countries facing the most traffic congestion are in India viz. Mumbai, Bengaluru, and New Delhi.  People are compelled to spend hours stuck in traffic jams, wasting away their precious time commuting. Current traffic light controllers use a fixed timer and do not adapt according to the real-time traffic on the road.

* In an attempt to reduce traffic congestion, we developed an improved traffic management system in the form of a Computer Vision-based traffic light controller that can autonomously adapt to the traffic situation at the traffic signal. The proposed system sets the green signal time adaptively according to the traffic density at the signal and ensures that the direction with more traffic is allotted a green signal for a longer duration of time as compared to the direction with lesser traffic. 

------------------------------------------
### Implementation Details

This project can be broken down into 3 modules:

1. `Vehicle Detection Module` - This module is responsible for detecting the number of vehicles in the image received as input from the camera. More specifically, it will provide as output the number of vehicles of each vehicle class such as car, bike, bus, truck, and rickshaw.

2. `Signal Switching Algorithm` - This algorithm updates the red, green, and yellow times of all signals. These timers are set bases on the count of vehicles of each class received from the vehicle detection module and several other factors such as the number of lanes, average speed of each class of vehicle, etc. 

3. `Simulation Module` - A simulation is developed from scratch using [Pygame](https://www.pygame.org/news) library to simulate traffic signals and vehicles moving across a traffic intersection.

Read more about object detection model used, working of the algorithm, and development of simulation [here](./Adaptive_Traffic_Signal_Timer_Implementation_Details.pdf).

------------------------------------------
### Demo

* `Vehicle Detection`

<p align="center">
 <img height=400px src="./![image](https://github.com/user-attachments/assets/d81971c6-5f5b-4c1c-83d6-e2199e248c20)" alt="Vehicle Detection">
</p>

<br> 

* `Signal Switching Algorithm and Simulation`

<p align="center">
    <img src="./Demo.gif">
</p>

------------------------------------------
### Prerequisites

1. [Python 3.7](https://www.python.org/downloads/release/python-370/)
2. [Microsoft Visual C++ build tools](http://go.microsoft.com/fwlink/?LinkId=691126&fixForIE=.exe.) (For Windows only)

------------------------------------------
