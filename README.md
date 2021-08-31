# Zordon Description

Repository for the ros package of the zordon URDF

## Dependencies

### [ROS](http://wiki.ros.org/ROS/Installation)

* ROS Melodic
* Gazebo 9

If you have not downloaded the full-desktop-version of ROS which comes with Gazebo Simulator, then you might need to download a couple of pre-requisites to run the simulation. Even if you have downloaded the full version, yet its a good practice to run the following command which checks if all the pre-requisites are installed or not. And if they are not installed, then the same command downloads them all automatically.

```
sudo apt-get install gazebo9 libgazebo9-* ros-melodic-robot-state-publisher ros-melodic-robot-joint-state-publisher ros-melodic-robot-joint-state-publisher-gui ros-melodic-teleop-twist-keyboard
```


### Testing the simulation

Firstly, please place this complete repository or just the ROS folder into your src folder of [catkin_ws](http://wiki.ros.org/catkin/Tutorials) and run catkin_make command. Once the catkin_make is done successfully, then to launch the robot in an empty simulation world for testing in Gazebo Simulator, run the following command on your terminal

```
roslaunch zordon_description gazebo.launch
```