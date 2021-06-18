project("sonarqube-example-project")
set(EXECUTABLE_OUTPUT_PATH  ${PROJECT_SOURCE_DIR}/build/)
add_executable(sonarqube-example-project thissmells.cpp)