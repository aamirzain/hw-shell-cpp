project (problem-3)

add_executable(functor functor.cpp)

## i installed fmt on my system
find_package(fmt)
target_link_libraries(functor fmt::fmt)
