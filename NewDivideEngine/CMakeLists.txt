# CMakeList.txt : CMake project for NewDivideEngine, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (NewDivideEngine
"src/main.cpp"
"src/Application.h"
"src/Application.cpp"
)

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET NewDivideEngine PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
