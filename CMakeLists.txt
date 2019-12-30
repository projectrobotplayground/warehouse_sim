cmake_minimum_required(VERSION 2.8.3)
project(warehouse_sim)


find_package(catkin REQUIRED)

catkin_package(
)

install(DIRECTORY models worlds
        DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
