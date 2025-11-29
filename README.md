## Repo for practice with Ros, URDF and Gazebo
For use with this tutorial: https://www.udemy.com/course/ros2-tf-urdf-rviz-gazebo/?couponCode=CP251118BG1
1. Install urdf `sudo apt install ros-jazzy-urdf-tutorial`
2. Launch urdf example `ros2 launch urdf_tutorial display.launch.py model:=/opt/ros/jazzy/share/urdf_tutorial/urdf/08-macroed.urdf.xacro`
3. Launch this urdf proj 
```
ros2 launch urdf_tutorial display.launch.py model:=/home/daniel/projects/urdf-gazebo-tutorial/section_3/my_robot.urdf
```
4. Launch s3 robot 
```
ros2 launch urdf_tutorial display.launch.py model:=/home/daniel/projects/urdf-gazebo-tutorial/section_3/s3_activity.urdf
```