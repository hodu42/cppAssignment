cmake_minimum_required(VERSION 3.23)
project(cppAssignment)

set(CMAKE_CXX_STANDARD 14)

include_directories(5_Operator_Overloading/Matrix)
include_directories(5_Operator_Overloading/DDay)
include_directories(5_Operator_Overloading/Fraction)
include_directories(5_Operator_Overloading/Money)
include_directories(6_String/SentenceProcessing)

add_executable(cppAssignment
        5_Operator_Overloading/Matrix/Matrix.cpp
        5_Operator_Overloading/Matrix/Matrix.h
        5_Operator_Overloading/Matrix/MatrixApp.cpp)
