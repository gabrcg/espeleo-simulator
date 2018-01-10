EspeleoRobo Simulator

Play with it using:

roslaunch espeleo_gazebo espeleo.launch
rosrun turtlesim turtle_teleop_key /turtle1/cmd_vel:=/cmd_vel

### Dependencies
Make sure following ROS packages are installed:

* effort_controllers
* joint_state_controller
* hector-gazebo-plugins

```
sudo apt-get install ros-kinect-effort-controllers ros-kinect-joint-state-controller ros-kinect-hector-gazebo-plugins
```
