<h1 align='center'>Sensor Model Assignment</h1>

## 📝 Table of Contents

- [Requirement 1](#req1)
  - [Steps](#steps1)
  - [Example](#ex1)
- [Requirement 2](#req2)



## 📃 Requirement 1 <a name = "req1"></a>
### Steps <a name = "steps1"></a>
 <h4>1-Load the Environment Map</h4>
 Use a provided image of a robot's environment where obstacles and free spaces are represented.

 <h4>2-Visualize the Map</h4>
 Display the map and overlay the given robot's position and orientation.

 <h4>3-Simulate Sensor Rays</h4>
 Cast rays of lenght 12m (max range) from the robot in various directions to simulate its sensors scanning the environment.

 <h4>4-Detect Obstacles</h4>
 For each ray, identify the point where it first intersects with an obstacle.

 <h4>5-Calculate Metrics</h4>
 Measure the distance to the obstacle and determine its coordinates relative to the robot.

 <h4>Display Results</h4>
 Visualize the detected rays on the map and output the collected data about each ray.

 ### Example <a name = "ex1"></a>
 Given the ropot pose x=14m y=7.4m theta=135 (x=350 pixel y=185 pixel) we got this output 
 ![Swagger](Map.png)


## 📃 Requirement 2 <a name = "req2"></a>
