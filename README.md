## Repo for practice with Ros, URDF and Gazebo
For use with this tutorial: https://www.udemy.com/course/ros2-tf-urdf-rviz-gazebo/?couponCode=CP251118BG1
1. Install urdf `sudo apt install ros-jazzy-urdf-tutorial`
2. Launch this urdf proj 
```
bash run_activity.sh
```
### urdf commands
```
ros2 topic echo /joint_states
ros2 run robot_state_publisher robot_state_publisher --ros-args -p robot_description:="$(xacro section_3/s3_solution.urdf)"
ros2 launch my_robot_description display.launch.xml
```

### Commands for tools
```
sudo apt install ros-jazzy-joint-state-publisher-gui
ros2 run joint_state_publisher_gui joint_state_publisher_gui
rqt_graph
ros2 run rviz2 rviz2
```

## For Gazebo

To install gazebo, source bashrc after installing
```sudo apt install ros-jazzy-ros-gz```
To start gazebo
```gz sim```
Useful links
https://en.wikipedia.org/wiki/List_of_moments_of_inertia#List_of_3D_inertia_tensors
https://wiki.ros.org/urdf/Tutorials/Adding%20Physical%20and%20Collision%20Properties%20to%20a%20URDF%20Model



