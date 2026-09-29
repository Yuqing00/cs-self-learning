# First Course Path: Missing Semester → CS61A → CS61C / CSAPP

A weekly plan built from [docs/CS学习规划.en.md](../docs/CS学习规划.en.md) and the course pages in this repo.

**Assumed pace:** about 10 hours a week (e.g. 2 weeknight sessions + one longer weekend block). At 15–20 h/week, compress each phase by roughly a third to a half.

| Phase | Course | Listed hours | Weeks at ~10 h/wk |
|---|---|---|---|
| 0 | Crash Course: Computer Science (optional warm-up) | 8 | during week 1 |
| 1 | [MIT Missing Semester](../docs/编程入门/MIT-Missing-Semester.en.md) | 10 (+ exercises) | 2 |
| 2 | [UC Berkeley CS61A](../docs/编程入门/Python/CS61A.en.md) | 50 (+ projects) | 10 |
| 3a | [UC Berkeley CS61C](../docs/体系结构/CS61C.en.md) | 100 | 12–14 |
| 3b | [CMU 15-213 / CSAPP](../docs/计算机系统基础/CSAPP.en.md) | 150 | 16–18 |

> The guide itself notes that Missing Semester mentions dev-process terms, so it works best right alongside or just before a first programming course. Doing it first is fine if you treat unfamiliar terms as "look up later".

---

## Phase 1 — MIT Missing Semester (weeks 1–2)

Site: <https://missing.csail.mit.edu/>. Do the exercises after each lecture; they are the point.

- **Week 1:** Course overview + the shell, shell tools & scripting, editors (Vim), data wrangling (grep/sed/awk). Watch Crash Course CS episodes as a background warm-up.
- **Week 2:** Command-line environment (tmux, dotfiles, ssh), version control (Git), debugging & profiling, metaprogramming, security basics.
- **Deliverable:** your own dotfiles repo on GitHub, and every later assignment committed with Git.
- **Companion (build-your-own-x → "Shell" or "Command-Line Tool"):** write a tiny shell or CLI tool in Python to lock in pipes, processes, and arguments.

## Phase 2 — CS61A (weeks 3–12)

Site: <https://cs61a.org> (backups listed on the course page). Textbook: *Composing Programs*.

- **Week 3:** Functions, control, environment diagrams. Lab 00–01, HW 01.
- **Week 4:** Higher-order functions, lambdas. HW 02. Start **Project 1: Hog**.
- **Week 5:** Recursion and tree recursion. Finish Hog.
- **Week 6:** Data abstraction, lists, sequences, trees. **Project 2: Cats**.
- **Week 7:** Mutability, iterators and generators.
- **Week 8:** Object-oriented programming, inheritance. Start **Project 3: Ants**.
- **Week 9:** Linked lists, efficiency, finish Ants.
- **Week 10:** Scheme and interpreters.
- **Week 11:** **Project 4: Scheme interpreter** (the highlight of the course).
- **Week 12:** SQL, review, and a buffer week to catch up.
- **Companion (build-your-own-x → "Programming Language"):** after Project 4, build a small Lisp or calculator interpreter in a second language. Also start solving ossu's intro problems if you want extra practice.

> **Note on CS61B:** both CS61C and CSAPP list CS61A **and** CS61B as prerequisites. You can go straight on after 61A, but expect to learn C and some data-structure basics on the fly. If that feels rough, slot in [CS61B](../docs/数据结构与算法/CS61B.en.md) (~12 weeks) first.

## Phase 3 — pick one next

### Option A: CS61C, Great Ideas in Computer Architecture (weeks 13–26)

Hardware-leaning, very project-driven, a bit gentler than CSAPP.

- **Weeks 13–15:** Number representation, C, pointers, memory management. **Project 1** (C warm-up, e.g. Game of Life).
- **Weeks 16–18:** RISC-V assembly, calling convention. **Project 2**: a neural net for MNIST in RISC-V assembly.
- **Weeks 19–22:** Digital logic, datapath, pipelining (Logisim). **Project 3**: build a 2-stage pipelined CPU.
- **Weeks 23–24:** Caches, virtual memory.
- **Weeks 25–26:** Parallelism: SIMD, OpenMP. **Project 4**: a fast toy NumPy.
- **Companion (build-your-own-x → "Emulator / Virtual Machine"):** write a CHIP-8 or small RISC-V emulator.

### Option B: CSAPP / CMU 15-213 (weeks 13–30)

Software-leaning systems course: the best on-ramp to operating systems, networking, and performance work. Harder (🌟×5).

- **Weeks 13–15:** Bits, integers, floats. **Data Lab**.
- **Weeks 16–18:** Machine-level x86-64. **Bomb Lab**, then **Attack Lab**.
- **Weeks 19–21:** Processor architecture, optimization, memory hierarchy. **Cache Lab**.
- **Week 22:** Linking (read *Programmer's Self-Cultivation* ch. on linking if stuck).
- **Weeks 23–25:** Exceptional control flow, processes, signals. **Shell Lab**.
- **Weeks 26–28:** Virtual memory, dynamic allocation. **Malloc Lab**.
- **Weeks 29–30:** Network programming and concurrency. **Proxy Lab**.
- **Companion (build-your-own-x → "Shell", "Web Server", "Operating System"):** each maps directly onto a lab above.

**How to choose:** pick CS61C if "how does the CPU actually run my code?" excites you, or you lean toward hardware, ML systems, or performance. Pick CSAPP if you lean toward operating systems, backend, networking, or security. Most people eventually take both.

---

## Companion top-starred repositories

- **[ossu/computer-science](https://github.com/ossu/computer-science):** a full free CS degree curriculum. Use it as a map to check what you have covered and what comes after this path (OS, networks, databases).
- **[codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x):** "rebuild it to understand it" tutorials. The companion bullets above point at matching sections.
- **[jwasham/coding-interview-university](https://github.com/jwasham/coding-interview-university):** useful alongside or after CS61B if interviews are a goal.
- **[donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer):** best after CSAPP or an OS/networks course.

## Weekly routine

1. Lectures or readings first half of the week, assignments second half.
2. Commit every lab and project to your own repo, even unfinished ones.
3. Do the assignments before looking at any public solutions.
4. End of each week: tick off progress below and write 3 lines on what was hard.

## Progress

- [ ] Phase 1: Missing Semester
- [ ] Phase 2: CS61A
- [ ] Phase 3: CS61C (chosen 2026-09-29)
