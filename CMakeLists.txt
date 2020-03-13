cmake_minimum_required(VERSION 3.15)
project(CSCI_366_Programming_Assignments_PA1_Basic_Battleship_2)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)
include_directories(cereal)
include_directories(dtl)
include_directories(googletest)
include_directories(src)
include_directories(test)

add_executable(CSCI_366_Programming_Assignments_PA1_Basic_Battleship_2
        src/Client.cpp
        src/Client.hpp
        src/client_main.cpp
        src/CMakeLists.txt
        src/common.hpp
        src/Server.cpp
        src/Server.hpp
        src/server_main.cpp
        test/CMakeLists.txt
        test/tests.cpp
        CMakeLists.txt
        LICENSE.md
        player_1.setup_board.txt
        player_2.setup_board.txt
        README.md)
