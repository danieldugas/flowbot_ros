
```
mkdir ~/Code/flowbot_ws/src -p
cd ~/Code/flowbot_ws
catkin init
catkin config --merge-devel --extend /opt/ros/melodic

cd ~/Code/flowbot_ws/src
git clone git@github.com:danieldugas/flowbot_ros
wstool init
wstool merge flowbot_ros/dependencies.rosinstall
wstool update

catkin build
```

