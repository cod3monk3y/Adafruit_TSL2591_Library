#cmake_minimum_required(VERSION 3.10)

#project(Adafruit_TSL2591_Library VERSION 0.1)

#set(CMAKE_CXX_STANDARD 17)
#set(CMAKE_CXX_STANDARD_REQUIRED True)

add_library(Adafruit_TSL2591 Adafruit_TSL2591.cpp)
target_include_directories(Adafruit_TSL2591 PUBLIC include)
target_link_libraries(Adafruit_TSL2591 Adafruit_Sensor)