# GPR-20 ROS Messages Package (gpr20_msgs)
This package contains the ROS messages, actions, services and launch files that are used in the GPR-20 robot. Since definitions are paramount for running every utility of the robot's software, this package must be present in every machine running utilities. It is agreed that nodes can be only executed via launch files, that are required to be present in this package.

## Launch Files
There are two launch files in the package:
- __GPR20_robot:__ launches the nodes that are meant to run in the robot's onboard computer.
- __GPR_server:__ launches the nodes that are meant to run in a server computer.
