# PROJECT TITLE - Density Based Traffic Signal System

* In previous post, we built an Atmega 328 Traffic Light Controller and in this post, you are going to learn about how to make an density based traffic light controller using Atmega 328. The main purpose of this project is, if there will be no traffic on the other signal, one shouldn’t wait for that signal. The system will skip that signal and will move on the next one.

* Atmega 328 is the main part of this project and it will be used to read from ultrasonic sensor HC-SR04 and calculate the distance. This distance will tell us if any vehicle is near the signal or not and according to that the traffic signals will be controlled.

* The main task was to avoid use of delay because we have to continuously read from the ultrasonic sensors and also at the same time, we have to control signals which requires the use of delay function.


