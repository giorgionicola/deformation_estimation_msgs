cmake_minimum_required(VERSION 3.0.2)
project(deformation_estimation_msgs)


find_package(catkin REQUIRED COMPONENTS
  std_msgs
  message_generation
)


## Generate services in the 'srv' folder
add_service_files(
  FILES
    SetModelHead.srv
)

## Generate added messages and services with any dependencies listed here
generate_messages(
  DEPENDENCIES
  std_msgs  # Or other packages containing msgs
)


