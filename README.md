# OARbot_examples
Examples and implementations of OARbot in Gazebo. Each example is scripted with python and can be executed in one line with the roslaunch command. To run the examples, download the .py and corresponding .launch file to a desired package location within a catkin workspace and use:
```
roslaunch [PACKAGE] example.launch
```

Only library dependencies required are ROS (Kinetic or later), OpenCV2, Pygame, and Gazebo. However, these examples also use the URDF models for the OARbot and Kinova robotic arm. All launch files will load the models into gazebo and execute the rospy scripts there.

## Ubuntu Installation Tutorials
[ROS](http://wiki.ros.org/melodic/Installation/Ubuntu)

[OpenCV2](https://docs.opencv.org/trunk/d7/d9f/tutorial_linux_install.html)

[Pygame](https://www.pygame.org/docs/)

[Gazebo](http://gazebosim.org/tutorials?tut=ros_installing&cat=connect_ros#Introduction)

[Kinova](https://github.com/Kinovarobotics/kinova-ros)

## Script Uses

#### OARbot_nav
Basic go-to point test of the OARbot that demonstrates it's omnidirectional movement capabilities

#### face_control
By using Haar Cascades in OpenCV2, a webcam can detect a users face and smile to control the movement of the OARbot.

#### banjOAR_kazooie
The pygame library is used to control the OARbot with WASD movement and mouse-controlled look. The gazebo world is a *rough* recreation of the level "Spiral Mountain" from Banjo-Kazooie
