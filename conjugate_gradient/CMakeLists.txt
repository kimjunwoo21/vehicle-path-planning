# Set the minimum version of CMake that can be used
cmake_minimum_required(VERSION 3.10)

# Set the project name
project(conjugate_gradient_practice)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add an executable
add_executable(conjugate_gradient main.cpp)

# Link against libraries (if any)
# target_link_libraries(MyExecutable PRIVATE SomeLibrary)
