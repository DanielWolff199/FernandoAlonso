# 2021-04-Lab-2-1635238-Aronson-1701184-Bartkunsky
## Readme

The programs in this repository are the programs built for the implementation of Elen4020 Laboratory two. These programs all perform a matrix transposition using different algorithms. The algorithms used are called Naive, NaiveThreading, Block-Threading, and Diagonal-Threading. The threading-technologies used are OpenMP, Pthreads, and the testing program Laboratory_2_Tests.cpp. These programs allow user input for matrix size and number of iterations and outputs the times taken for the calculations to be output.

In order to run the programs we have developed for Elen4020 Lab 2, follow the instructions.

**Prerequisites**
- Have the gcc compiler installed
- Be able to run unix commands
- Download the file doctest.h in the same folder

**Steps**
- Open a unix command line in the same folder as this README
- In order to build the executable files, using the makefile, the command is $make
- The files generated are called naive.o, NaiveThreadingOpenMp.o, DiagonalThreadingOpenMP.o, BlockThreadingOpenMP.o, DiagonalThreadingPthreads.o, BlockThreadingPthreads.o, and Laboratory_2_Tests.o
- In order to run these executable files, the command is $./filename, for example, $./BlockThreadingOpenMP.o
- In order to delete the executable files, using the makefile, the command is $make clean
