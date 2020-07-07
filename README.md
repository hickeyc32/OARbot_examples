# OARbot_examples
Examples and implementations of OARbot in Gazebo. Each example is scripted with python and can be executed in one line with the roslaunch command. To run the examples, download the .py and corresponding .launch file to a desired package location within a catkin workspace and use:
```
roslaunch [PACKAGE] example.launch
```

Only library dependencies required are ROS (Kinetic or later), OpenCV2, and Gazebo. However, these examples also use the URDF models for the OARbot and kinova robotic arm.

## Ubuntu Installation Tutorials
[ROS](http://wiki.ros.org/melodic/Installation/Ubuntu)

[OpenCV2](https://docs.opencv.org/trunk/d7/d9f/tutorial_linux_install.html)

[Gazebo](http://gazebosim.org/tutorials?tut=ros_installing&cat=connect_ros#Introduction)

[Kinova](https://github.com/Kinovarobotics/kinova-ros)
