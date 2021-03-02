cmake_minimum_required (VERSION 3.0.0)
 
project (cmake4vscode)

set(EXECUTABLE_OUTPUT_PATH ./${CMAKE_BUILD_TYPE})

set(SOURCE src/main.cpp)
 
add_executable (${PROJECT_NAME} ${SOURCE})
