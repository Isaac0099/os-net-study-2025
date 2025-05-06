# Self‑Study Plan: Operating Systems & Computer Networking (5 May – 22 September 2025)

---

## Overview

* **Duration:** 20 weeks (Week 0 setup + 19 instructional weeks)
* **Weekly commitment:** ≈ 10 hrs (∼2 hrs Mon‑Thu, 4 hrs Sat)
* **Primary outcome:** Portfolio‑grade OS & networking projects; knowledge on par with UVU CS 3060 & CS 3560.
* **Optional outcome:** Sit for **Linux Foundation Certified Sysadmin (LFCS)** after Week 16 if I decide I want a formal credential.

---

## Links

* **GitHub repo:** [https://github.com/Isaac0099/os-net-study-2025](https://github.com/Isaac0099/os-net-study-2025)
* **Notion board:** [https://www.notion.so/os-net-study-2025-notion-1e61a3188b7780c99f8ef828d8e0bd9c](https://www.notion.so/os-net-study-2025-notion-1e61a3188b7780c99f8ef828d8e0bd9c)


---

## Detailed Weekly Outline & Checkpoints

| Wk              | Dates (Mon–Sun) | Hours | Operating Systems Task                                          | Networking Task                            | Deliverable                                            |
| --------------- | --------------- | ----- | --------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------------------ |
| 1               | 5 May – 11 May  | 10    | **MIT 6.1810 Lect 1–2**<br>OSTEP Ch 1–3 (Intro, virtualization) | Top‑Down Ch 1 (Overview)                   | Blog post #1: learning goals & environment screenshots |
| 2               | 12 May – 18 May | 10    | **xv6 Lab 0** (Unix utilities warm‑up)                          | **CS144 Lab 0** (socket primer)            | Repo pushes + self‑quiz (10 Q’s)                       |
| 3               | 19 May – 25 May | 10    | OSTEP Ch 4–6 (Processes, Scheduling) + MIT Lec 3                | Top‑Down Ch 2 (Application layer)          | Flashcard set (Anki or Notion DB)                      |
| 4               | 26 May – 1 Jun  | 10    | **xv6 Lab 1** (System calls)                                    | **CS144 Lab 1** (TCP receiver)             | Technical write‑up comparing syscalls vs HTTP APIs     |
| 5               | 2 Jun – 8 Jun   | 10    | OSTEP Ch 7–9 (Concurrency intro) + MIT Lec 4                    | Top‑Down Ch 3 (Transport layer; TCP/UDP)   | Peer code review with friend (PR comments)             |
| **Milestone A** | 9 Jun – 11 Jun  | –     | xv6 Lab 1 tests **green**                                       | –                                          | Short demo video (GIF)                                 |
| 6               | 12 Jun – 18 Jun | 10    | **xv6 Lab 2** (Threads)                                         | **CS144 Lab 2** (TCP sender)               | Code pushed + test results                             |
| 7               | 19 Jun – 25 Jun | 10    | OSTEP Ch 11–13 (Locks, CVs, Deadlock)                           | Top‑Down Ch 4 (Network layer; IP, routing) | Mid‑course reflective journal (≈400 words)             |
| 8               | 26 Jun – 2 Jul  | 10    | **xv6 Lab 3** (Virtual memory)                                  | **CS144 Lab 3** (TCP congestion control)   | All tests green + GIF                                  |
| 9               | 3 Jul – 9 Jul   | 10    | OSTEP Ch 14–16 (Paging)                                         | Top‑Down Ch 5 (Link layer; Ethernet)       | Progress report PDF (replaces hackerspace talk)        |
| 10              | 10 Jul – 16 Jul | 8     | **Catch‑up / review**                                           | **Catch‑up / review**                      | Blog post #2: lessons learned                          |
| **Milestone B** | 17 Jul – 20 Jul | –     | **Labs 0‑3 all pass**                                           | –                                          | Portfolio README update                                |
| 11              | 21 Jul – 27 Jul | 10    | OSTEP Ch 17–19 (File systems)                                   | Top‑Down Ch 6 (Wireless & Mobile)          | TinyFS prototype in Go                                 |
| 12              | 28 Jul – 3 Aug  | 10    | **xv6 Lab 4** (File system)                                     | **CS144 Lab 4** (NAT)                      | Demo video                                             |
| 13              | 4 Aug – 10 Aug  | 10    | OSTEP Ch 20–22 (I/O & Disks)                                    | Top‑Down Ch 7 (Multimedia, CDNs)           | QUIC & HTTP/3 notes                                    |
| 14              | 11 Aug – 17 Aug | 10    | MIT Lec 6 (Security) + OSTEP security sections                  | **CS144 Lab 5** (TCP reassembly)           | Security checklist (threat model)                      |
| 15              | 18 Aug – 24 Aug | 10    | **Capstone:** build mini shell                                  | **Side project:** UDP chat app             | Repos pushed + usage docs                              |
| **Milestone C** | 25 Aug – 28 Aug | –     | **All xv6 labs pass**                                           | **All CS144 labs pass**                    | Live demo (loom)                                       |
| 16              | 29 Aug – 4 Sep  | 10    | OSTEP summary & review                                          | **LFCS prep** (if opting in)               | Practice exam report                                   |
| 17              | 5 Sep – 11 Sep  | 8     | Polish shell & docs                                             | Polish chat app                            | Publish on portfolio site                              |
| 18              | 12 Sep – 18 Sep | 6     | Retrospective blog post                                         | –                                          | Final blog + résumé bullet                             |
| 19              | 19 Sep – 22 Sep | 4     | **Buffer / overflow**                                           | **Buffer / overflow**                      | Close‑out & next‑steps plan                            |

---

## Cost Snapshot

| Item                     | Cost       | Notes                      |
| ------------------------ | ---------- | -------------------------- |
| Top‑Down Approach e‑book | \~\$40     | Optional; else library PDF |
| VPS (demo hosting)       | \$25       | \$5/mo × 5 months          |
| LFCS exam (optional)     | \$445      | Decide by Week 12          |
| **Total (no cert)**      | **≈ \$65** |                            |

---

## Accountability

* **Weekly check‑in:** DM Monday morning (blockers, this‑week target).
* **Deliverables due:** Sunday 23:59 MT pushed to GitHub & linked in Notion.
* **Blog cadence:** Week 1, Week 10, Week 18 (plus optional in‑between posts).

---

## Week 0 · 28 Apr – 4 May 2025 — Environment Setup (due **Sun 4 May 23:59 MT**)

| Task                                     | Notes                                                                      |
| ---------------------------------------- | ---------------------------------------------------------------------------|
| Install Homebrew, Git, VS Code, Docker   | `brew install git gcc qemu risc-v-tools docker` **Done** ✔                 |
| Build / install RISC‑V toolchain for xv6 | or use `brew tap mitpals/xv6 && brew install xv6-toolchain`**Done** ✔      |
| Clone MIT 6.1810 xv6 repo                | `git clone https://github.com/mit-pdos/xv6-riscv.git` **Done** ✔           |
| Clone Stanford CS144 base                | `git clone https://github.com/sggin/dev.cs144` (or fork official)**Done** ✔|
| Create repo & Notion board               | **Done** ✔                                                             |
| Push README with goals                   | **Done** ✔                                        |
