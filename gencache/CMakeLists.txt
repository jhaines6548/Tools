cmake_minimum_required(VERSION 3.7)
project(gencache VERSION 1.0 LANGUAGES CXX)

set(CMAKE_MODULE_PATH APPEND "${CMAKE_CURRENT_SOURCE_DIR}/../Modules")

include(ConfigureWindows)

find_package(ICU COMPONENTS uc data REQUIRED)

add_executable(gencache src/main.cpp)

target_link_libraries(gencache ICU::uc ICU::data)

target_compile_features(gencache PRIVATE cxx_std_11)

include(GNUInstallDirs)
install(TARGETS gencache RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR})
