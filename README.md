# Task Scheduling Simulator

This project implements a task scheduling simulator designed to evaluate the schedulability of periodic tasks in a non-preemptive scheduling environment. 

To choose one of the pre-implemented task tables for testing, modify the 'test' variable in line 7 of the C code. This allows you to switch between different task sets to evaluate their schedulability (value between 1 and 4).

## Features
- **Task Simulation**: Simulates the execution of tasks over a hyperperiod, taking into account their execution times and deadlines.
- **Permutations of Execution Orders**: Generates all possible permutations of task execution orders and evaluates which order produces the best schedule.
- **Schedulability Check**: Determines whether all tasks can be completed within their deadlines without missing any, based on the chosen execution order.
- **Score Calculation**: Calculates a score for each permutation based on the completion time of tasks, aiming to minimize delays.

## Installation
To run this project, clone the repository and compile the C code using your preferred development environment. Ensure that you have a C compiler installed.



