# INTERVAL TREE

## Overview
An interval tree can be used to efficiently find a set of numeric intervals overlapping or containing another interval.
The idea is to create a binary search tree (BST) with automatic balance such as the red black tree, the AVL tree, etc. to maintain the set of intervals so that all operations can be performed in O-time (log n)

This library provides a basic implementation of an interval tree using C++ templates, a presentation (.pptx) developing step-by-step methods to add; delete;search; computational cost, use cases.

## Use of the demo
The demo is implemented in the c++11 language, the use and compilation is simple.
Copy all the code from intervaltree.cpp and paste it into your favorite program, compile and go.

## Build and Run
Compilation instruction:
g++ interval.cpp -o interval.exe
Finally execute:
interval.exe
    
## Dependencies (windows)
g++ 11 and graphviz

## Contributions - Implementation and theory
* Part of the implementation and the theory for the basic guide of the code was from the page: Geeks for Geeks
* Wikipedia
* Interval Tree in Data Structure - Includehelp.com
* Interval Trees - DGP

## Author
Elvis David Minaya Mamani
eminayama@ulasalle.edu.pe

## University
Universidad La Salle


