# cross-compiling-test
On Windows
===============================
Software cmake_minimum_required
-------------------------------
CMAKE gui (https://cmake.org/download/)
Visual Studio 2017 (community version, free)
(suggested) atom

To compile
------------------------------
-download zip file of project and extract

-use cmake gui
--point cmake to source code and also specify the build to
be in the same location as source but in build (i.e., source/build).
-once configured once specify "Debug" for the CMAKE_CONFIGUATION_TYPES
-configure and generate makefile and select open project

On Linux
=====================
to compile
cd cross-compiling-test
mkdir build
cd bulid
ccmake ..
