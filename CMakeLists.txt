cmake_minimum_required(VERSION 2.8.3)
project(sma-wrapper)

find_package(catkin REQUIRED COMPONENTS
  rospy
  actionlib
  std_msgs
  sensor_msgs
  ensenso_camera_msgs
)

catkin_python_setup()

