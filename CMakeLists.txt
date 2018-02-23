project(Behavior-Planner)

cmake_minimum_required( VERSION 3.5)

add_definitions(-std=c++11)

set(CXX_FLAGS "-Wall")
set(CMAKE_CXX_FLAGS, "${CXX_FLAGS}")


include_directories(
    include/
    )


set(sources
    src/main.cpp
    src/road.cpp
    src/vehicle.cpp
    src/cost.cpp
    )

add_executable(behavior_planner ${sources})

#target_link_libraries()
