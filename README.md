# ⚙️ CPU Scheduling & Deadlock Simulator

Simulates CPU scheduling with deadlock detection and recovery.
Built in Python for Operating Systems course (ENCS3390).

## Features
- Priority Scheduling with Round-Robin (time quantum = 10)
- Deadlock detection using cycle detection
- Deadlock recovery by process termination
- Gantt chart output
- Average waiting & turnaround time calculation

## Files
- `priorty_RR.txt` — Priority Round-Robin scheduling
- `deadlock.txt` — Scheduling with deadlock detection & recovery
- `input.txt` — Input file with process data

## Input Format
PID ArrivalTime Priority CPU{burst} IO{burst} CPU{burst}
Example:
0 0 1 CPU{50} IO{30} CPU{20}
1 5 2 CPU{20} IO{30} CPU{20}
## How to Run

**Priority Round-Robin:**
   python priorty_RR.txt

**Deadlock Detection:**
   python deadlock.txt

## Requirements
- Python 3.x
- Input file: `input.txt` in the same folder

## Authors
Shahd Raed Shweketeh & Nadeen Ali Jaber
ENCS3390 OS Course | 2024-2025
