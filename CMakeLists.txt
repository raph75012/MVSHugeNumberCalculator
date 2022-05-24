cmake_minimum_required(VERSION 3.21)
project(MVSHugeNumberCalculator_ C)

set(CMAKE_C_STANDARD 99)

add_executable(MVSHugeNumberCalculator_ main.c UseHugeNumber/Type/HugeFloat.c UseHugeNumber/Type/HugeFloat.h UseHugeNumber/Type/HugeInt.c UseHugeNumber/Type/HugeInt.h UseHugeNumber/Type/HugeUnsignedInt.c UseHugeNumber/Type/HugeUnsignedInt.h)
