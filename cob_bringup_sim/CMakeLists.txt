cmake_minimum_required(VERSION 2.8.3)
project(cob_bringup_sim)

find_package(catkin REQUIRED)

catkin_package()

### TEST ###
if(CATKIN_ENABLE_TESTING)
  find_package(cob_default_env_config REQUIRED)
  find_package(cob_supported_robots REQUIRED)
  find_package(roslaunch REQUIRED)
  foreach(robot ${cob_supported_robots_ROBOTLIST})
    foreach(env ${cob_default_env_config_ENVLIST})
      message("testing for robot: ${robot} in env: ${env}")
      #roslaunch_add_file_check(launch robot:=${robot} robot_env:=${env})
      roslaunch_add_file_check(launch ROBOT=${robot} ROBOT_ENV=${env})
    endforeach()
  endforeach()
endif()

### INSTALL ###
install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(PROGRAMS scripts/remove_object.py scripts/spawn_object.py scripts/move_object.py
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
