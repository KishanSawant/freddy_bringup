cmake_minimum_required(VERSION 3.0.2)
project(freddy_bringup)

find_package(catkin REQUIRED COMPONENTS
  freddy_description
)


catkin_package(
    CATKIN_DEPENDS
        freddy_description
)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
