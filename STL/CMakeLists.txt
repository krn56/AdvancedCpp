cmake_minimum_required(VERSION 2.8.9)
project (STL)

add_compile_options(-std=c++11)

add_executable(vectors src/vectors.cpp)
add_executable(vectors_and_memory src/vectors_and_memory.cpp)
add_executable(two_dimensional_vector src/two_dimensional_vector.cpp)
add_executable(lists src/lists.cpp)
add_executable(map src/map.cpp)
add_executable(custom_object_map src/custom_object_map.cpp)
add_executable(custom_object_map_key src/custom_object_map_key.cpp)
add_executable(multimap src/multimap.cpp)
add_executable(sets src/sets.cpp)
add_executable(stack_and_queue src/stack_and_queue.cpp)
add_executable(sort_deque_friend src/sort_deque_friend.cpp)
add_executable(complex_types src/complex_types.cpp)
