# CSA02-1911260219-Assingnment4.

CSA02 – C Programming Assignment 4

Modelling Real-World Data with Structures and Unions

Student Details

- Name: A.Nusrath
- Register Number: 1911260219
- Course: C Programming
- Course Outcome: CO4
- Compiler: one compiler. com

Assignment Overview

This assignment demonstrates the use of structures, nested structures, arrays of structures, structure pointers, unions and storage classes in C programming.

Tasks Completed

Task| Topic| Result
Task 1| Patient Register – Data Design Review| Designed patient records using nested structures
Task 2| Courier Parcel Tracking| Implemented nested structures and selection sort
Task 3| Unions and Memory Layout| Implemented tagged unions and checked memory sizes
Task 4| Structure Forensics| Demonstrated pass by value and structure pointers
Task 5| Storage Classes| Demonstrated auto, static, extern and register
Task 6| Canteen Inventory and Billing| Designed inventory, sales and revenue summary

Repository Structure

Assignment4/
│
├── Task01/
│   ├── task1.c
│   └── output.png
│
├── Task02/
│   ├── task2.c
│   └── output.png
│
├── Task03/
│   ├── task3.c
│   └── output.png
│
├── Task04/
│   ├── task4.c
│   └── output.png
│
├── Task05/
│   ├── task5.c
│   ├── counter.c
│   ├── extern_main.c
│   └── output.png
│
├── Task06/
│   ├── task6.c
│   └── output.png
│
└── README.md

Compilation and Execution

All programs are compiled using GCC with warning flags.

Task 1

gcc -Wall -Wextra task1.c -o task1
./task1

Result: Patient details are stored and displayed using structures.

Task 2

gcc -Wall -Wextra task2.c -o task2
./task2

Result: Parcels are sorted by weight using selection sort.

Task 3

gcc -Wall -Wextra task3.c -o task3
./task3

Result: Tagged unions display temperature, humidity and status readings.

Task 4

gcc -Wall -Wextra task4.c -o task4
./task4

Result: Structure pointers correctly update bank account balances.

Task 5

gcc -Wall -Wextra task5.c -o task5
./task5

Result: Demonstrates automatic and static counters.

The extern implementation uses two source files:

gcc -Wall -Wextra extern_main.c counter.c -o extern_demo
./extern_demo

Task 6

gcc -Wall -Wextra task6.c -o task6
./task6

Result: Demonstrates canteen inventory, stock updates, expiry warnings and revenue sorting.

Concepts Covered

- Structures and nested structures
- Arrays of structures
- Structure pointers and arrow operator
- Unions and tagged unions
- Memory allocation, alignment and padding
- Storage classes: auto, static, extern and register
- Selection sort and linked lists

Submission

C source files and execution screenshots are organised into separate task folders.
