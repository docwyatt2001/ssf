# --- Command line tests

add_executable(commandline_tests EXCLUDE_FROM_ALL commandline_tests.cpp)
target_link_libraries(commandline_tests ssf_framework)
add_unit_test(commandline_tests)
set_property(TARGET commandline_tests PROPERTY FOLDER "Unit Tests/CommandLine")
