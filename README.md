# ROS2-TEST
"THIS PROJECT WILL BE FINISHED EVEN IT'S UGLY"

#DAY 1 
 -created pkg>publisher>subscriber>launch>log
 -errors faced:1
#DAY2
-created my own code
-errors faced:3
#DAY3
-created parameters
-errors faced:1
----Finished-----

# ROS2 Sensor Monitor

## Description
A simple ROS 2 system with a publisher and subscriber that monitors sensor values, logs them to a file, and raises warnings when a configurable threshold is exceeded.

## Nodes
- sensor_publisher: publishes random sensor values
- sensor_subscriber: logs values and warns when threshold is exceeded

## How to Run
```bash
colcon build
source install/setup.bash
ros2 launch ros2_sensor_node launch.py

