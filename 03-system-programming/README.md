# 🛠️ System Programming & Network Competence

## 🎯 SMART Goal Statement
**Specific:** I aim to reach the technical proficiency required for R&D roles in the ICT (Information and Communication Technologies) sector. To achieve this, I will master **C language** fundamentals, gain deep expertise in **Linux System & Network Programming** (specifically I/O Multiplexing), and finally transition this skillset to a **Modern C++** architecture.

**Measurable:**
- Complete all critical exercises in the "K&R" book.
- Develop a **TCP Chat Server** using **I/O Multiplexing (epoll)** in C, capable of handling 100+ concurrent clients with **zero memory leaks** (verified by Valgrind).
- Refactor the project using **Modern C++ (RAII, CMake)** standards by the end of the year.

**Achievable:** I will dedicate the first half of the year (Q1-Q2) to mastering C and System internals, and the second half (Q3-Q4) to robust project development and the C++ transition.

**Relevant:** The ICT/Defense domain requires high-performance packet processing. Understanding `epoll` vs `threads` and memory safety tools (`Valgrind`) is crucial for mission-critical software.

**Time-bound:**
- **K&R (C) Book Completion:** February 1, 2026
- **Linux System & Network Programming (C & Tools):** September 1, 2026
- **Transition to Modern C++ & Refactoring:** December 31, 2026

## 🗺️ Roadmap

### Phase 1: The Foundation (C Language - K&R)
*Deadline: February 1, 2026*
- [ ] **Book:** "The C Programming Language" (Brian Kernighan & Dennis Ritchie).
- [ ] **Output:** Solve in-text exercises and push code to `/exercises-c` folder.

### Phase 2: Under the Hood (System & Network with C)
*Deadline: September 1, 2026*
- [ ] **Resources:** "Beej's Guide to Network Programming" and Linux Man Pages.
- [ ] **System:** `fork()`, `exec()`, POSIX Threads (`pthread`), Mutex/Semaphores.
- [ ] **Concurrency (Critical):** Implement **I/O Multiplexing** using `poll()` or `epoll()` to handle multiple clients without creating a thread for each (Solving C10K problem).
- [ ] **Tooling & Quality:**
    - Use **Valgrind** to ensure 0 bytes memory leak.
    - Use **GDB** for debugging segmentation faults.
- [ ] **Project:** Develop a Chat Server in raw C capable of handling 50+ concurrent connections.

### Phase 3: Modern Architecture (Transition to C++)
*Deadline: December 31, 2026*
- [ ] **Build System:** Migrating from manual Makefiles to **CMake**.
- [ ] **Concept:** C++ Classes, RAII (Resource Acquisition Is Initialization), Smart Pointers.
- [ ] **Functional:** Replace function pointers with **Lambdas** and `std::function`.
- [ ] **Task:** Refactor the Phase 2 project using C++ (OOP) standards.
- [ ] **Goal:** Analyze the trade-offs between `malloc` vs `new/make_unique` and `epoll` raw implementation vs C++ wrappers.