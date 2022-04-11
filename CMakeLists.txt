cmake_minimum_required(VERSION 3.21)
project(final_portfolio_project)

set(CMAKE_CXX_STANDARD 14)

add_executable(final_portfolio_project main.cpp Order.cpp Order.h Person.cpp Person.h Guest.cpp Guest.h Staff.cpp Staff.h Drive_Up.cpp Drive_Up.h Pick_up.cpp Pick_up.h)
