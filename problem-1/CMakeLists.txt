project (problem-1)

add_executable(animalgame animalgame.cpp)

## i installed fmt on my system
find_package(fmt)
target_link_libraries(animalgame fmt::fmt)
