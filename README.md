# Coursera_StateEstimation and Localization for Self Driving Cars
This repository contains files of final project for Course 2 of 4 :"State Estimation and Localization of self driving cars" offered by University of Toronto on Coursera

# What is localization for self driving cars?
Localization, which is how a car figures out where it is in the world. Once the vehicle develops a comprehensive understanding of its environment(perception via camera,radar and lidar), it needs to determine exactly where in that environment it is.

# Maps
Self-driving cars use maps because these maps help them figure out what the world is supposed to look like.
Providing the vehicle with a map, however, raises a question. Where exactly is the vehicle on the map?

# Why is localization necessary for self driving cars?
Determining the vehicle's precise position on the map is called "localization". By localizing itself, the vehicle can determine its precise relationship to all of the elements on the map. Is the vehicle in the middle lane or the right lane? How far away is the curb? What about the next intersection?

Other components of the self-driving car technology stack, like the motion planner, will base decisions off of this localization information. For example, if the car localizes itself in the middle lane of a road, but the motion planner knows a left turn is coming up, then the motion planner will begin preparing the vehicle to shift into the left lane, so it's positioned to make the turn.

# How to localize precisely?
Localization is tricky, though. Figuring out precisely where the vehicle is involves rigorous mathematical algorithms and probability calculations.
There are many different techniques to help an autonomous vehicle locate itself with the help of various sensors available.
1) Odometry
2) Kalman Filters
3) Particle Filters
4) SLAM (Simulatanoeus Localization and Mapping)

