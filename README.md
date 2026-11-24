# TurtleBot3 ROS 2 Workspace

What this project does (navigation, SLAM, etc.).

## Requirements
- Ubuntu 22.04, ROS 2 Humble
- TurtleBot3 packages (see `turtlebot.repos`)

## Build
    cd ~/turtlebot_ws
    vcs import src < turtlebot.repos
    colcon build --symlink-install
    source install/setup.bash

## Run
    ros2 launch <package> <launch_file>.py
