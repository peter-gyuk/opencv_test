project( view )
cmake_minimum_required(VERSION 2.8)
find_package( OpenCV REQUIRED )
add_executable( view view.cpp )
target_link_libraries( view ${OpenCV_LIBS} )
