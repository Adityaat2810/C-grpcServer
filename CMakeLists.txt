cmake_minimum_required(VERSION 3.20)
project(grpc-server)

# link source file
add_executable(${PROJECT_NAME}
    src/main.cpp
)

# link header files
target_include_directories(${PROJECT_NAME}
    PUBLIC
        ${PROJECT_SOURCE_DIR}/include
)