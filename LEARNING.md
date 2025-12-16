# Learning Resources

Curated references to deepen understanding of Operating Systems concepts and the experiments in this repository.

## Core Texts
- *Operating System Concepts* by Silberschatz, Galvin, Gagne
- *Modern Operating Systems* by Andrew S. Tanenbaum
- *Operating Systems: Three Easy Pieces* (OSTEP) – free online book: https://pages.cs.wisc.edu/~remzi/OSTEP/

## Scheduling Algorithms
- OSTEP Chapters on CPU Scheduling
- Linux Completely Fair Scheduler (CFS) overview: https://docs.kernel.org/scheduler/sched-design-CFS.html
- Visualization of scheduling algorithms: https://cs.usfca.edu/~galles/visualization/.

## Synchronization & Concurrency
- OSTEP Chapters on Concurrency, Locks, Semaphores
- Little Book of Semaphores: https://greenteapress.com/wp/semaphores/
- POSIX Threads Programming tutorial: https://computing.llnl.gov/tutorials/pthreads/

## Deadlocks
- OSTEP Deadlock chapters
- Banker’s Algorithm explanation: https://www.geeksforgeeks.org/Bankers-Algorithm-in-Operating-System/

## Memory Management & Paging
- OSTEP chapters on Address Translation and Paging
- LRU/FIFO/Optimal replacement discussions: https://pages.cs.wisc.edu/~remzi/OSTEP/vm-smalltables.pdf

## Disk Scheduling
- Disk scheduling visual guide: https://www.cs.iit.edu/~virgil/cs470/lectures/DiskSched.html
- SCAN/C-SCAN/LOOK/C-LOOK animations: https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/

## Shell Scripting
- GNU Bash Reference Manual: https://www.gnu.org/software/bash/manual/bash.html
- Bash style guide: https://google.github.io/styleguide/shellguide.html

## Tools for Secure, Clean Repos
- GitGuardian guidance on avoiding secrets: https://docs.gitguardian.com/
- GitHub Secret Scanning overview: https://docs.github.com/code-security/secret-scanning
- Pre-commit hooks: https://pre-commit.com/

## Suggested Practice
- Re-implement algorithms from scratch and compare outputs
- Add logging to observe state transitions (queues, ready lists, disk head movement)
- Write tests for edge cases (single process, identical burst times, max queue sizes)

## Learning Philosophy
This repository is intentionally structured for education. Favor clarity and comments that explain *why* an approach is taken, not just *what* the code does.
