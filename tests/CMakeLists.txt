include(CTest)

if(BUILD_TESTING)
add_executable(TestDebugging test_debugging.cpp)
target_link_libraries(TestDebugging SBS)
add_test(NAME TestDebugging COMMAND TestDebugging)

add_executable(TestConcurrentVector test_concurrent_vector.cpp)
target_link_libraries(TestConcurrentVector SBS)
add_test(NAME TestConcurrentVector COMMAND TestConcurrentVector)
endif()