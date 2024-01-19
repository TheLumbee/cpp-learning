cmake_minimum_required(VERSION "3.28.1")

project("HellowWord")

add_executable("${PROJECT_NAME}" "hello_world.cpp")

install(TARGETS "${PROJECT_NAME}" DESTINATION bin)
install(FILES "hello_world.cpp" DESTINATION src)