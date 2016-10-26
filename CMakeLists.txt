cmake_minimum_required(VERSION 3.3)
project(MeanShift_cpp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY "${CMAKE_CURRENT_SOURCE_DIR}")

set(SOURCE_FILES MeanShift.cpp cpp_test.cpp)

add_executable(MeanShift_cpp ${SOURCE_FILES})

# add libs you need
# set(OpenCV_LIBS opencv_core opencv_highgui opencv_nonfree)

# linking
# target_link_libraries(MeanShift_cpp ${OpenCV_LIBS})
