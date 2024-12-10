cmake_minimum_required(VERSION 3.23)

project(Arduino-Library-I2CDevice LANGUAGES C CXX ASM)

add_library(arduino_I2CDevice INTERFACE)

target_include_directories(arduino_I2CDevice
  INTERFACE
  ${CMAKE_CURRENT_LIST_DIR}/src
)