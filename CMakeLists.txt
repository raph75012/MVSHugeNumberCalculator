cmake_minimum_required(VERSION 3.21)
project(MVSHugeNumberCalculator_ C)

set(CMAKE_C_STANDARD 99)

add_executable(MVSHugeNumberCalculator_ main.c UseHugeNumber/Operator/HugeFloatOperator.c UseHugeNumber/Operator/HugeFloatOperator.h UseHugeNumber/Operator/HugeIntOperator.c UseHugeNumber/Operator/HugeIntOperator.h UseHugeNumber/Operator/HugeUnsignedIntOperator.c UseHugeNumber/Operator/HugeUnsignedIntOperator.h)
