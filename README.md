# UselessFuru — Code Portfolio

A code portfolio by **Alexander Dela Cruz** containing four projects that demonstrate systems programming, parallel computing, relational database design, and algorithmic problem solving.

📖 **Live documentation:** https://ueseless-productions.mintlify.app

## Projects

### GPU Programming
Three CUDA assignments and one final project, developed on the **TACC Lonestar6 HPC cluster** using **CUDA 11.3**. Covers parallel array operations, work scheduling strategies, a radix-2 FFT implementation, and an **N-body gravity simulation** with shared memory optimization.

### Hospital Database
A **MySQL relational database** modeling a 9-floor hospital across 8 tables (`patient`, `staff`, `doctor`, `nurse`, `manager`, `billing`, `treatment`, `treatment_staff`), populated with 108 patients, 54 staff, 108 treatments, and 108 billing records. Uses a subtype relationship off `staff` to keep the schema normalized.

### Programming Techniques
**C++ solutions to LeetCode and UVA Online Judge problems**, organized by technique: integer math, string processing, greedy algorithms, hash sets, map-based sorting, and DFS graph traversal.

### Algorithms
A **real-time terminal dictionary search tool** in C++. Reads character-by-character input via `getch()` and searches a JSON dictionary for prefix matches, displaying results instantly with color highlighting. Uses `nlohmann::json` for parsing.

## Technologies

- **CUDA C/C++** — GPU kernel development, shared memory optimization, TACC Lonestar6 HPC
- **MySQL** — Relational schema design, subtype modeling
- **C++ STL** — Containers and algorithms across competitive programming solutions
- **JSON / nlohmann::json** — Dictionary parsing for the search tool

## Documentation

Full write-ups for each project live on the documentation site:

- [GPU Programming](https://ueseless-productions.mintlify.app/gpu/overview)
- [Hospital Database](https://ueseless-productions.mintlify.app/hospital/overview)
- [Programming Techniques](https://ueseless-productions.mintlify.app/prog-tech/overview)
- [Algorithms](https://ueseless-productions.mintlify.app/algorithms/overview)
