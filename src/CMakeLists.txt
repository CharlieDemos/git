cmake_minimum_required (VERSION 2.6)

# 1. name of the generated project
project (Tutorial)


# 5. add the executable
add_executable (Tutorial Hello.cpp)

# 6. add the install targets
install (TARGETS Tutorial DESTINATION bin)
