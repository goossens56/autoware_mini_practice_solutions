cmake_minimum_required(VERSION 3.0.2)
project(autoware_mini_practice_solutions)

find_package(catkin REQUIRED)

find_package(rospy REQUIRED)
find_package(std_msgs REQUIRED)
catkin_package(
)

include_directories(
  ${rospy_INCLUDE_DIRS}
  ${std_msgs_INCLUDE_DIRS}
)

