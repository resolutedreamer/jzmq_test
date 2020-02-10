cmake_minimum_required(VERSION 3.10)
project(jzmq_test)

find_package(Java REQUIRED)
include(UseJava)

set(JAVA_SOURCE_FILES HelloWorld.java)
add_jar(jzmq_test_jar ${JAVA_SOURCE_FILES})


