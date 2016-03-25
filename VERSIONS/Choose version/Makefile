CPP = g++

# Opencv 2.4.12
#CPPFLAGS = -L/Users/Vareto/Documents/OpenCV/VERSIONS/2.4.12/build/Release/lib \
#	   -I/Users/Vareto/Documents/OpenCV/VERSIONS/2.4.12/build/Release/include

# Opencv 3.0.0
CPPFLAGS = -L/Users/Vareto/Documents/OpenCV/VERSIONS/3.0.0/build/Release/lib \
	   -I/Users/Vareto/Documents/OpenCV/VERSIONS/3.0.0/build/Release/include

# Opencv 3.1.0
#CPPFLAGS = -L/Users/Vareto/Documents/OpenCV/VERSIONS/3.1.0/build/Release/lib \
#	   -I/Users/Vareto/Documents/OpenCV/VERSIONS/3.1.0/build/Release/include

all: showVersion

showVersion: getVersion.cpp
	$(CPP) $(CPPFLAGS) $^ -o $@