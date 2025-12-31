cmake_minimum_required(VERSION 3.8)
project(franka_11_description)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY .
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
