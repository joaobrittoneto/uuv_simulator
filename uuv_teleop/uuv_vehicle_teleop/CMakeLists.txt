cmake_minimum_required(VERSION 2.8.3)
project(uuv_vehicle_teleop)

find_package(catkin REQUIRED joy_teleop joy)

catkin_package()

install(DIRECTORY launch
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
        PATTERN "*~" EXCLUDE)
