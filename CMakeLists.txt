cmake_minimum_required(VERSION 3.16)
project(gui_control)

find_package(catkin REQUIRED COMPONENTS
  rospy
  std_msgs
)

catkin_python_setup()

#add_service_files(
#  FILES
#)

#generate_messages(
#  DEPENDENCIES
#)

catkin_package(
  CATKIN_DEPENDS rospy std_msgs
  )


#catkin_install_python(
#  PROGRAMS
#    scripts/
# DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
#)

include_directories(
  ${catkin_INCLUDE_DIRS}
)
