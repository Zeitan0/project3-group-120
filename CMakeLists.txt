cmake_minimum_required(VERSION 3.27)

project(project_3)

set(CMAKE_CXX_STANDARD 14)

include_directories("C:/Users/zengt/OneDrive/Documents/GitHub/project-3-group-120/pugixml-master/src")

add_executable(project_3 main.cpp pugixml-master/src/pugixml.cpp
        Trie.cpp
        hashTable.h
        hashTable.cpp
        Trie.h
)
