cmake_minimum_required(VERSION 2.8.3)
project(orca_stereo)

## Find catkin and everything we need in ROS
find_package(catkin REQUIRED COMPONENTS
  rospy
)

## Declare a catkin package and export dependencies
catkin_package(
  CATKIN_DEPENDS
  rospy
)

## Set up include directories
include_directories(include ${catkin_INCLUDE_DIRS})

## Require C++14
add_compile_options(-std=c++14)