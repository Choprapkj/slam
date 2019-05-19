# Map My World
Project submission for the Robotics Software NanoDegree program.

Link to rtabmap.db file:
https://www.dropbox.com/s/z77vphrueqx3uyk/rtabmap.db?dl=0

Dependencies:
This project was built using Ubuntu 18.04.02 LTS and ROS Melodic
Other requirements: Gazebo, catkin, rtabmap_ros, teleop_twist_keyboard

Instructions:
1. Clone the repository to src folder of catkin workspace.
2. Build the package with catkin_make and source the devel/setup.bash script
3. Launch the gazebo world and RViz roslaunch my_robot world.launch
4. Launch teleop node: rosrun teleop_twist_keyboard teleop_twist_keyboard.py
5. Launch mapping node: roslaunch my_robot mapping.launch
6. Navigate the robot with keyboard to map the world. The rtabmap.db file will be saved in /root/.ros/ when you terminate the mapping node.
