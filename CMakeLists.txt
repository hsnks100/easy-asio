project(app)
add_executable(app main.cpp)
target_link_libraries(app boost_system boost_thread pthread)
