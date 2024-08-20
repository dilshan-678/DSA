cmake_minimum_required(VERSION 3.26)
project(DSA C)

set(CMAKE_C_STANDARD 11)

add_library(DSA library.c
        stack.c
        Linearqueue.c
        Circulerqueue.c
        single_linked_list.c
        double_linked_list.c
        BST.c
        queue_in_linked_list.c
        stack_in_link_list.c)
