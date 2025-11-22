👨‍🎓 Student Information

Name: Nisha Sangwan
Course: B.Tech CSE
Subject: ENCS351 – Operating System Lab
Assignment No.: 4

🖥️ Operating Systems Lab – Assignment 4
ENCS351 – System Calls, VM Detection, Batch Processing & File System Operations
📘 Overview

This repository contains the complete implementation for Operating System Lab Assignment 4, focusing on Linux system calls, multiprocessing, batch execution, inter-process communication (IPC), VM detection, and CPU scheduling algorithms.
The assignment simulates low-level OS behavior using Python, Bash, and (optional) C.

Each task is implemented as a separate script with clear outputs and proper documentation, following the official lab instructions.

🧪 Tasks Included
✅ Task 1 — Batch Processing Simulation (Python)

Implements a batch-processing system that executes multiple Python scripts sequentially using subprocess.
Includes:

script1.py

script2.py

script3.py

Controller script: Task1_BatchProcessing.py

Demonstrates basic batch execution similar to traditional OS batch processing systems.

✅ Task 2 — System Startup & Logging

Simulates system boot and shutdown events using Python’s multiprocessing and logging modules.

Features:

Process creation

Logging start & end times

Log written to system_log.txt

Replicates real system boot process behaviour.

✅ Task 3 — System Calls & IPC (Windows-Compatible)

Simulates fork, pipe, wait, and exec behaviour using Python’s multiprocessing.Pipe() (Windows-friendly).

Implements:

Parent → child message passing

IPC through a communication pipe



✅ Task 5 — CPU Scheduling Algorithms

Implements the following algorithms in Python:

FCFS — First Come First Serve

SJF — Shortest Job First

Priority-Based Scheduling

Round Robin (RR)

For every algorithm:

Waiting Time (WT)

Turnaround Time (TAT)

Average WT

Average TAT
