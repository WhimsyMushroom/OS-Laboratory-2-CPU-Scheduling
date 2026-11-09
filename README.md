# OS Laboratory 2 – CPU Scheduling Algorithms

**Course:** BCA151 – Operating Systems Laboratory  
**Institution:** Mindanao State University – Iligan Institute of Technology  
**College:** College of Computer Studies  
**Department:** Department of Computer Applications  
**Activity:** Laboratory Activity 2 – CPU Scheduling Algorithms

---

## I. Introduction

CPU scheduling is an important function of an operating system. It determines which process will use the CPU and for how long. Different scheduling algorithms are used to improve CPU utilization, reduce waiting time, and provide better system performance.

This activity implements five CPU scheduling algorithms using Python: First Come, First Served (FCFS), Shortest Job First (SJF), Non-Preemptive Priority Scheduling, Round Robin (RR), and Shortest Remaining Time First (SRTF).

The program displays the Gantt chart, completion time, turnaround time, waiting time, response time, and average performance metrics for each algorithm.

## II. Objectives

1. Implement different CPU scheduling algorithms using Python.
2. Understand the differences between preemptive and non-preemptive scheduling.
3. Generate Gantt charts to represent process execution.
4. Calculate completion time, turnaround time, waiting time, and response time.
5. Compare the performance of different scheduling algorithms.
6. Understand the effect of the Round Robin time quantum.
7. Use Git and GitHub to manage and submit the source code.

## III. Technologies Used

- Python
- Visual Studio Code
- Git
- GitHub

## IV. Project Structure

```text
OS-Laboratory-2-CPU-Scheduling/
│
├── cpu_scheduling.py
├── README.md
│
└── screenshots/
    ├── fcfs.png
    ├── sjf.png
    ├── priority.png
    ├── round_robin.png
    └── srtf.png