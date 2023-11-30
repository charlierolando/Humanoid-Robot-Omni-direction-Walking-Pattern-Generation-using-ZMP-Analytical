project(anu)

add_subdirectory(matplotplusplus)

add_executable(my_target main.cpp)
target_link_libraries(my_target PUBLIC matplot)
