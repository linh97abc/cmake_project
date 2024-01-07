add_library(my_lib STATIC)

target_include_directories(my_lib PUBLIC inc)

target_sources(my_lib PRIVATE 
    LibA.cpp LibB.cpp)
