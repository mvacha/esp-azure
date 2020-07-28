# The following five lines of boilerplate have to be in your project's
# CMakeLists in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.5)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
set (EXTRA_COMPONENT_DIRS "${CMAKE_CURRENT_BINARY_DIR}/../../../port" "C:/Users/michal/Repos/thesis/src/components/esp-cryptoauthlib")
project(iothub_client_sample_mqtt)

#set(CFLAGS "USE_PROV_MODULE" "HSM_AUTH_TYPE_CUSTOM")