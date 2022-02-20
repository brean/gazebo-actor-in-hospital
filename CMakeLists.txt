cmake_minimum_required(VERSION 2.8.3)
project(gazebo_actor_in_hospital)

find_package(catkin REQUIRED COMPONENTS
  gazebo_ros
  aws_robomaker_hospital_world
)

catkin_package()

install(DIRECTORY launch worlds
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)