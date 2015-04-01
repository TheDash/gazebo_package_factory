cmake_minimum_required(VERSION 2.8.3)
project(gazebo_package_factory)
find_package(catkin REQUIRED)
catkin_package()

install(PROGRAMS scripts/generate_gazebo_package DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})
