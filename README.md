# Gazebo Actor in Hospital
Adds an actor inside the AWS Robomaker Hospital World environment on a static path

## Installation
1. Download and install the [aws-robomaker-hospital-world environment](https://github.com/aws-robotics/aws-robomaker-hospital-world).
1. Clone this directory into your ROS-workspace
1. run `colcon build`

Alternatively you can use the docker environment [here](../hospital-world-docker).

## Run
source your colcon workspace and run `roslaunch gazebo_actor_in_hospital view_hospital.launch --screen`.

