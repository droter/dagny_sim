cmake_minimum_required(VERSION 2.8.3)
project(dagny_sim)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS
  #stdr_parser
  #stdr_resources
  #stdr_robot
  #stdr_server
)

catkin_package()

