# mobile-manipulator
This is the simulation model of mecanum in gazebo environment.
Proceed as follows.

1. Load the mecanum.
roslaunch mecanum_sim mecanum.launch

2. Control the speed of the mecanum.
rostopic pub /cmd_vel geometry_msgs/Twist "linear:
  x: 1.0
  y: 0.0
  z: 0.0
angular:
  x: 0.0
  y: 0.0
  z: 0.5" 

3. if the gazebo fails to load, please change to mecanum_s.dae
