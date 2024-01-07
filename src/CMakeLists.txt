add_library(my_lib STATIC)

add_subdirectory(inc)
target_sources(my_lib PRIVATE 
    LibA.cpp LibB.cpp)

target_link_libraries(my_lib PUBLIC my_lib_include)