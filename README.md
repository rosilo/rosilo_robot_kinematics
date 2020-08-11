# rosilo_robot_kinematics

A library encapsulating the communication over ROS of a node that provides kinematic information (should inherit from `RobotKinematicsProvider`) and a node that reads that kinematic information (should composing `RobotKinematicsInterface`).

## Requirements

### System-wide packages
- `libeigen3-dev`
- `libdqrobotics`

### ROS:
- `geometry_msgs`

### Rosilo:
- `rosilo_conversions`
