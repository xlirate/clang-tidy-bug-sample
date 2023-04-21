
add_executable(example example.cpp)
target_link_libraries(example PRIVATE myproject::project_warnings myproject::project_options)
