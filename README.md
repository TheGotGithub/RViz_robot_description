# RViz_robot_description

This package contains the description of a robot for use with ROS2. It includes URDF files and configuration files written in xacro format.

## Installation

Clone this repository into your ROS2 workspace:

```bash
cd /ros2_workspace/src
git clone https://github.com/TheGotGithub/RViz_robot_description.git
```
## Usage

To launch the robot description and visualize it, run the following command:

```bash
ros2 launch robot_description display.launch.py
```

To customize the robot and adjust its parameters, you can modify the URDF file `robot.urdf.xacro` and adjust the properties defined in `robot_config.xacro`.

### Customizing the Robot

You can customize the robot's configuration by modifying the `robot.urdf.xacro` file. This file contains the main URDF description of the robot's structure. Adjusting parameters such as link dimensions, joint types, and joint positions can be done directly in this file.

### Adjusting Properties

The parameters used in the URDF file are defined as properties in the robot_config.xacro file. These properties define dimensions, joint positions, and other customizable parameters. You can modify these property values in the robot_config.xacro file according to your requirements. By adjusting these values, you can easily customize the robot's dimensions and configurations without directly modifying the URDF file.

