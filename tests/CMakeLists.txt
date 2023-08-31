include(CTest)

if(BUILD_TESTING)
add_executable(TestDebugging test_debugging.cpp)
target_link_libraries(TestDebugging SBS)
add_test(NAME TestDebugging COMMAND TestDebugging)
endif()