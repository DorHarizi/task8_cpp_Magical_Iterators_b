cmake_minimum_required(VERSION 3.25)
project(task7_cpp_TheQuestForTheMagicalIterators_a)

set(CMAKE_CXX_STANDARD 17)

add_executable(task7_cpp_TheQuestForTheMagicalIterators_a main.cpp sources/MagicalContainer.hpp sources/MagicalContainer.cpp sources/AscendingIterator.cpp sources/SideCrossIterator.cpp sources/PrimeIterator.cpp Demo.cpp Test.cpp)
