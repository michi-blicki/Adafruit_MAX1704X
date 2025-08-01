cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_MAX1704X.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES Adafruit_BusIO)

project(Adafruit_MAX1704X)
