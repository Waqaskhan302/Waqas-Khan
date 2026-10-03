Enhanced xv6-RISC-V Kernel

Name| Roll Number| Semester
Waqas Khan| BCS-F24-E06| 5th Semester

Project Overview

This project extends the xv6-RISC-V teaching operating system with 10 simple and practical modules: 5 for Operating Systems and 5 for Computer Architecture.

Operating System Modules

#| Module| Description
1| Kernel Event Logger| Records important kernel events
2| Process Family Tree| Displays parent-child processes
3| Sleep-Wake Tracker| Shows when processes sleep and wake
4| File Access Tracker| Records basic file access
5| Process Lifetime Tracker| Shows process running lifetime

Computer Architecture Modules

#| Module| Description
6| Instruction Execution Tracker| Shows basic instruction activity
7| CPU Mode Monitor| Shows user and supervisor mode
8| Stack Usage Monitor| Displays basic stack usage
9| Page-Fault Tracker| Counts page-fault events
10| Timer Tick Analyzer| Displays timer tick activity

Mermaid Diagram

flowchart TD
    A[User Programs] --> B[xv6-RISC-V Kernel]

    B --> OS[Operating System Modules]
    B --> CA[Computer Architecture Modules]

    OS --> O1[Kernel Event Logger]
    OS --> O2[Process Family Tree]
    OS --> O3[Sleep-Wake Tracker]
    OS --> O4[File Access Tracker]
    OS --> O5[Process Lifetime Tracker]

    CA --> C1[Instruction Tracker]
    CA --> C2[CPU Mode Monitor]
    CA --> C3[Stack Usage Monitor]
    CA --> C4[Page-Fault Tracker]
    CA --> C5[Timer Tick Analyzer]

    O1 --> K[Kernel]
    O2 --> K
    O3 --> K
    O4 --> K
    O5 --> K

    C1 --> R[RISC-V CPU]
    C2 --> R
    C3 --> R
    C4 --> R
    C5 --> R

    K --> R
    R --> H[RISC-V Hardware]

Technologies

- xv6-RISC-V
- C
- RISC-V Assembly
- QEMU
- RISC-V Toolchain
- Git & GitHub
- Mermaid


