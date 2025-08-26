cmake_minimum_required(VERSION 3.12)
set(CMAKE_CXX_STANDARD 11)
set(DEMO_NAME livox_lidar_quick_start)
add_executable(${DEMO_NAME} main.cpp)

target_link_libraries(${DEMO_NAME}
        PUBLIC
        livox_lidar_sdk_static
				)
