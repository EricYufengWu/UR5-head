# UR5-head
URDF packages of a rbot head for a UR5 arm system

version 2: added collision and initial tags, ready to be used in Gazebo.

download and extract the folder in catkin_ws/src

To show the model in rviz: go to the folder and type: 
user:~/catkin_ws/src/ur5_head_description$ roslaunch ur5_head_description urdf_visualize.launch model:='$(find ur5_head_description)/urdf/head.urdf' 
