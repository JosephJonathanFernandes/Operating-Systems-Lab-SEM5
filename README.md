# 🎓 Operating Systems Lab - Semester 5 (CE560)

[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)
[![Learning](https://img.shields.io/badge/Purpose-Learning-brightgreen.svg)](LEARNING.md)
[![C++](https://img.shields.io/badge/Language-C%2B%2B-00599C.svg)](https://isocpp.org/)
[![Shell](https://img.shields.io/badge/Language-Shell-89e051.svg)](https://www.gnu.org/software/bash/)

> **Educational Repository** - A comprehensive collection of Operating Systems laboratory experiments and implementations for academic learning purposes.

## 📋 Table of Contents

- [About](#about)
- [Experiments](#experiments)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## 🎯 About

This repository contains practical implementations of core Operating Systems concepts as part of the Computer Engineering Semester 5 curriculum (CE560). Each experiment is designed to provide hands-on experience with fundamental OS algorithms and mechanisms.

**Learning Objectives:**
- Understanding process management and scheduling algorithms
- Implementing synchronization mechanisms
- Exploring memory management techniques
- Analyzing disk scheduling algorithms
- Practical application of OS concepts through coding

## 🧪 Experiments

### Experiment 1: Directory Management System
Implementation of a hierarchical directory structure in Unix/Linux.
- **Files:** `directory_system.txt`, `directory.txt`, `directory1.txt`
- **Concepts:** File systems, directory traversal

### Experiment 2: Shell Scripting
Basic to advanced shell scripting exercises.
- **Files:** `a.sh` through `e.sh`, plus practice set
- **Concepts:** Shell commands, scripting, automation

### Experiment 3: CPU Scheduling Algorithms (Non-Preemptive)
- **FCFS** (First Come First Serve): [FCFS.cpp](Experiment%203/FCFS.cpp), [FCFS1.cpp](Experiment%203/FCFS1.cpp)
- **SJF** (Shortest Job First): [SJF.cpp](Experiment%203/SJF.cpp)
- **Priority Scheduling**: [NPPriority.cpp](Experiment%203/NPPriority.cpp)

### Experiment 4: CPU Scheduling Algorithms (Preemptive)
- **Round Robin**: [RR.cpp](Experiment%204/RR.cpp)
- **Preemptive Priority**: [PPriority.cpp](Experiment%204/PPriority.cpp)
- **SRTF** (Shortest Remaining Time First): [SRTN.cpp](Experiment%204/SRTN.cpp), [SRTN1.cpp](Experiment%204/SRTN1.cpp), [SRTN2.cpp](Experiment%204/SRTN2.cpp), [SRTN3.cpp](Experiment%204/SRTN3.cpp)

### Experiment 5: Process Synchronization
- **Producer-Consumer Problem**: [ProducerConsumer.cpp](Experiment%205/ProducerConsumer.cpp)
- **Concepts:** Semaphores, mutual exclusion, race conditions

### Experiment 6: Deadlock Avoidance
- **Banker's Algorithm**: [Bankers.cpp](Experiment%206/Bankers.cpp)
- **Concepts:** Resource allocation, safe state detection

### Experiment 7: Page Replacement Algorithms
- **FIFO** (First In First Out): [FIFO.cpp](Experiment%207/FIFO.cpp)
- **LRU** (Least Recently Used): [LRU.cpp](Experiment%207/LRU.cpp)
- **Optimal**: [Optimal.cpp](Experiment%207/Optimal.cpp)

### Experiment 8: Disk Scheduling Algorithms
- **FCFS**: [fcfs.cpp](Experiment%208/fcfs.cpp)
- **SSTF** (Shortest Seek Time First): [sstf.cpp](Experiment%208/sstf.cpp)
- **SCAN**: [scan.cpp](Experiment%208/scan.cpp)
- **C-SCAN**: [cscan.cpp](Experiment%208/cscan.cpp)
- **LOOK**: [look.cpp](Experiment%208/look.cpp)
- **C-LOOK**: [clook.cpp](Experiment%208/clook.cpp)

## 🔧 Prerequisites

Before running the experiments, ensure you have:

- **C++ Compiler**: GCC/G++ (version 7.0 or higher)
- **Shell**: Bash (for shell scripts)
- **Operating System**: Linux/Unix or Windows with WSL
- **Basic Knowledge**: C++ programming and command-line interface

### Installation

**Linux/Ubuntu:**
```bash
sudo apt-get update
sudo apt-get install g++ build-essential
```

**macOS:**
```bash
xcode-select --install
```

**Windows:**
- Install WSL2 or MinGW-w64
- Or use an IDE like Code::Blocks or Visual Studio

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/Operating-Systems-Lab-SEM5.git
cd Operating-Systems-Lab-SEM5
```

### Compile and Run C++ Programs

```bash
# Navigate to specific experiment
cd "Experiment 3"

# Compile
g++ FCFS.cpp -o fcfs

# Run
./fcfs
```

### Execute Shell Scripts

```bash
# Navigate to experiment
cd "Experiment 2"

# Make executable
chmod +x a.sh

# Run
./a.sh
```

## 📁 Project Structure

```
Operating-Systems-Lab-SEM5/
├── .github/              # GitHub templates and workflows
├── Assignments/          # Lab assignments
├── Experiment 1/         # Directory management
├── Experiment 2/         # Shell scripting
├── Experiment 3/         # CPU scheduling (non-preemptive)
├── Experiment 4/         # CPU scheduling (preemptive)
├── Experiment 5/         # Process synchronization
├── Experiment 6/         # Deadlock avoidance
├── Experiment 7/         # Page replacement
├── Experiment 8/         # Disk scheduling
├── .gitignore           # Git ignore rules
├── CODE_OF_CONDUCT.md   # Community guidelines
├── CONTRIBUTING.md      # Contribution guidelines
├── LEARNING.md          # Learning resources
├── LICENSE              # BSD 3-Clause License
└── README.md            # This file
```

## 📚 Learning Resources

For additional learning materials, tutorials, and references, see [LEARNING.md](LEARNING.md).

## 🤝 Contributing

This is a learning repository, and contributions are welcome! Whether you're:
- Fixing bugs
- Improving documentation
- Adding new implementations
- Optimizing algorithms

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License

This project is licensed under the BSD 3-Clause License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Course Instructor and Teaching Assistants
- Operating System Concepts (Silberschatz, Galvin, and Gagne)
- The open-source community for learning resources
- Fellow students for collaboration and discussions

## 📞 Contact

For questions, suggestions, or collaboration:
- Open an [issue](../../issues)
- Submit a [pull request](../../pulls)

---

**Note:** This repository is maintained for educational purposes. Code implementations are meant for learning and may not be production-ready.
