cmake_minimum_required(VERSION 3.4)

PROJECT( asmlib-opencv-demo )
FIND_PACKAGE(OpenCV 2.4.12 PATHS /Users/Vareto/Documents/OpenCV/VERSIONS/2.4.12/opencv-2.4.12/cmake)
SET(TEST_SRC main.cpp XGetopt.cpp)

INCLUDE_DIRECTORIES( ../lib/ )
INCLUDE_DIRECTORIES( /Users/Vareto/Documents/OpenCV/VERSIONS/2.4.12/build/Release/lib/ )
INCLUDE_DIRECTORIES( /Users/Vareto/Documents/OpenCV/VERSIONS/2.4.12/build/Release/include/ )
INCLUDE_DIRECTORIES( /Users/Vareto/Documents/OpenCV/VERSIONS/2.4.12/build/Release/include/opencv/ )
INCLUDE_DIRECTORIES( /Users/Vareto/Documents/OpenCV/VERSIONS/2.4.12/build/Release/include/opencv2/ )

ADD_EXECUTABLE( demo ${TEST_SRC})
TARGET_LINK_LIBRARIES( demo asm ${OpenCV_LIBS})
