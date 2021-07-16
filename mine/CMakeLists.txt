cmake_minimum_required(VERSION 3.10.2)
project(RealSenseID_Mine)

add_executable(authenticate-cpp-sample authenticate.cc)
target_link_libraries(authenticate-cpp-sample PRIVATE rsid)

add_executable(enroll-cpp-sample enroll.cc)
target_link_libraries(enroll-cpp-sample PRIVATE rsid)
