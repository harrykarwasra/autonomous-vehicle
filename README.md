# ANoRC : AutoNomous RC-Car 

In this repository we would be sharing our demo code of our Capstone Project. The project is inspired by MIT RACECAR and is a working application of the course on [**UDACITY** : Self DRiving Car NanoDegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013)
Firstly we would be applying Computer Vision and Deep Learning(Lane Detection, Streering angle movement prediction, etc.). 
Secondly, Use of [Sensor Fussion](https://towardsdatascience.com/sensor-fusion-90135614fde6) through which we will be filtering out the data from the array of sensors  for recognising the and analysing the environment. 

## How a self driving car works? 

According to Udacity, Driverless Cars has 5 Core Components on which it works. It includes :
### 1. Computer Vision
Computer Vision helps us in showing how the world around us is like. It looks for the colours and gradiet to identify the lanes and the roads. Then we train a deep neural network that will draw the bounding boxes around the other obstacles (other vehicles on the road).

### 2. Sensor Fusion
So once we know what the world looks the next step is to augment that understanding of the world using other sensors so radar and laser to get measurements that are difficult for a camera alone to understand. It helps the vehicle to have a god understanding of exact amount of obstacles are and how fast are they moving. This helps us extracting information like speed, distace, size of an obstacle, and loaction with the help of sensors. To be fully adaptive car has to be capable enough to gather and store real time data in a dynamic unpredictable environment. Sensors like LiDAR or RADAR for long range sensing and ultrasound sensors for short range that helps seeing things that are very close to the vehicle. The most famous and accurate sensors are LiDAR but they are too expensive that affordability is an issue and hence mass production becomes though. 

As ANoRC is a small scale project we would be using stereo camera to detect obstacles. It can easily be scaled us for industrial use with proper investments on sensors. 

<p align="center">
<img src="https://github.com/harrykarwasra/autonomous-vehicle/blob/master/images/ADAS-cars-Adobe-106263301-520x378.jpg" width="300" height="220" />
</p>

### 3. Localization
They use MAPS because these will help them what the world is suppose to look like. Humans can memorise easily to the routes they are familiar with because they know what to expect , where the speed changes, where do they have to take a turn or where is the intersection. So, Self Driving car uses maps that tells them where they have to look.

Identifying specific landmarks like poles, mailing box and measuring the car’s distance from each of the individually to estimate the car’s position.

<p align="center">
<img src="https://github.com/harrykarwasra/autonomous-vehicle/blob/master/images/overview-3.gif" width="300" height="220" />
</p>

### 4. Path Planning
So, once we have figures out where exactly we are int he world and what the world looks like, the next step comprises of charting a path through that world to figure out how to get to our desired destination. It is all about finding a safe and an efficient part to move through the traffic.


### 5. Control
The final step in the pipeline is control. Control means how actually turn the steering wheel and hit the break or accelerator in order to execute the desired trajectory that we have build during the path planning.

<img src="https://github.com/harrykarwasra/autonomous-vehicle/blob/master/images/overview.png" />


Check out the submodule and features of the project in breif down below:

# Table of Content 
#### 1. Traffic Light Detector/Classifier 

<p align="center">
<img src="https://github.com/harrykarwasra/autonomous-vehicle/blob/master/images/giphy-2.gif" width="300" height="220" />
</p>

#### 2. Path Planning
#### 3. 2D-LiDAR Mapping 
#### 2. Lane Detction 
<p align="center">
<img src="https://github.com/harrykarwasra/autonomous-vehicle/blob/master/images/overview.gif" width="300" height="220" />
</p>
