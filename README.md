# opendog_robot

This repository is inspired by (and uses CAD from) James Bruton from XRobots:
https://github.com/XRobots/openDog

![openDog in ROS](opendog_description/share/opendog_rviz.png?raw=true "openDog in ROS")

While the URDF is still a work in progress, to launch openDog in RViz:
1) Install your ROS Distro of choice: http://wiki.ros.org/ROS/Installation
2) Run the following commands in the terminal:
```
$ mkdir -p ~/ros_ws/src
$ cd ~/ros_ws/src/
$ git clone https://github.com/IanTheEngineer/opendog_robot.git
$ cd ~/ros_ws/
$ source /opt/ros/<distro>/setup.bash
$ catkin_make
$ source ~/devel/setup.bash
$ roslaunch opendog_description test_opendog_description.launch
```
