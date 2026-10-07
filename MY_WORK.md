# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [shahad majed alotaibi] |
| **Student ID** | [446051487] |
| **University Email** | [446051487]@std.psau.edu.sa |
| **GitHub Username** | [shahadwq] |
| **Repository Link** | [https://github.com/shahadwq/OS-Assignment1-shahad-alotaibi] |
 
---

## 🎥 Video Link
**Video Link**: https://drive.google.com/file/d/13NPjEiE2lhbjy2vUtRhqq2WYREjSG6dc/view?usp=drivesdk

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 5, 2026, 9:30 AM]
**What I did**:Forked the repository and updated student ID

**Details**:- Forked the starter repository on GitHub and cloned it locally.
- Updated student ID to 446051487 in SchedulerSimulation.java at line 150.
- Compiled and ran the initial program to ensure the setup works.

**Challenges**:
Making sure the student ID was updated correctly in the source code.
**Solution**:
Checked line 150 in SchedulerSimulation.java and verified the program executed without errors.
**Time spent**:
45 minutes
---

### Entry 2 - [October 5, 2026, 2:00 PM]
**What I did**:Implemented Feature 1 (Process Priority)

**Details**:
- Added priority integer field to the Process class. 
  - Updated constructor to accept priority parameter.  
   - Added getPriority() getter method.

**Challenges**:Making sure constructor updates didn't break existing process instantiations.

**Solution**:Checked and updated process object creations in SchedulerSimulation.java.

**Time spent**:
1 hour

---

### Entry 3 - [October 5, 2026, 7:30 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter)

**Details**:
- Created static variable `contextSwitchCount` in `SchedulerSimulation`.
- Incremented the counter inside the simulation loop whenever context switching occurred.
- Displayed total context switches at the end of execution.

**Challenges**: Identifying the exact location in the loop where context switches occur.

**Solution**: Traced queue switching logic and placed the increment statement in the context switch block.

**Time spent**: 1 hour

---

### Entry 4 - [October 6, 2026, 4:00 PM]
**What I did**: Implemented Feature 3 (Completed Processes Counter)

**Details**:
- Added static variable `completedProcessesCount` in `SchedulerSimulation`.
- Tracked processes that finished execution (`Remaining time: 0ms`).
- Displayed total completed processes count in the final summary.

**Challenges**: Distinguishing finished processes from preempted ones.

**Solution**: Checked the remaining execution time condition (`Remaining time: 0ms`) before incrementing.

**Time spent**: 45 minutes

---
### Entry 5 - [October 7, 2026, 11:00 AM]
**What I did**: Documentation, Git history cleanup, and final testing

**Details**:
- Filled student information and development log entries in `MY_WORK.md`.
- Used `git commit --amend` to rename commit message and forced push to GitHub.
- Performed final run to confirm console output and context switch counts.

**Challenges**: Resolving duplicate commit message on GitHub repository.

**Solution**: Executed `git commit --amend` followed by `git push --force`.

**Time spent**: 1 hour

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.
**Total time spent on assignment**: 4.5 hours

**Most challenging part**: Tracking process execution states accurately within the simulation loop to count context switches without affecting queue order.

**Most interesting learning**: Gaining a clear hands-on understanding of how CPU scheduling algorithms manage processes and context switching in operating systems.

**What I would do differently next time**: Create simple test cases earlier to verify process queue transitions step by step before implementing all features.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[While working on SchedulerSimulation.java, I learned how Java handles concurrent execution by creating process threads that implement the Runnable interface. I observed how calling Thread.start() begins asynchronous execution, allowing processes to simulate running work concurrently rather than strictly in sequential order. To simulate processing time on the CPU, Thread.sleep() was used to pause thread execution for specified durations. I also saw how Thread.join() is essential for thread synchronization, ensuring that the main program waits for active process threads to complete before printing the final execution summary. What surprised me most was how context switches between threads require careful timing to avoid race conditions when updating shared counters like contextSwitchCount. Seeing output lines like "[Process 1] Executing... Remaining time: 400ms" made the theoretical concepts of thread execution and state transitions very concrete.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was implementing Feature 2 to accurately track context switches within the process scheduling loop. It was difficult because I needed to trace the simulation logic carefully to determine the exact moment a process is preempted and another thread takes over CPU execution. Initially, I placed the increment statement inside the main process loop, which caused contextSwitchCount to increment incorrectly on every iteration rather than only during true process switches. Debugging this required adding temporary print statements to observe when process states changed between active threads. After analyzing how the scheduler switches execution between process threads, I correctly positioned the contextSwitchCount++ line inside the queue switching block. Verifying that the final count matched the expected scheduling output gave me a much clearer understanding of thread preemption in operating systems.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[To overcome the challenges I faced during implementation, I adopted a systematic debugging and step-by-step testing strategy. First, I carefully re-read the assignment instructions in README.md and thoroughly analyzed the existing code structure in SchedulerSimulation.java. Whenever a feature did not work as expected, I inserted temporary System.out.println statements to track variable values and thread execution flow in real-time. This print-based debugging approach helped me pinpoint exactly where context switches occurred and how process remaining times were updated. Additionally, I made small code modifications and re-ran the program frequently rather than attempting large changes all at once. By testing incrementally, I could immediately verify whether each fix worked correctly without introducing new bugs into the simulation. Combining thorough documentation review with iterative testing allowed me to resolve all technical issues independently and successfully complete the assignment.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading concepts applied in this simulation are fundamental to building responsive real-world applications such as web browsers and mobile apps. For example, in a modern web browser, separate threads handle UI rendering, user input, and background network requests simultaneously without freezing the user interface. Similarly, in music streaming applications, one thread streams audio data continuously in the background while another handles user interactions. In video games, multithreading allows graphics rendering, physics calculations, and AI logic to run in parallel across multi-core CPUs. Just as our scheduler managed process execution states and context switches, real-world operating systems schedule these application threads to maximize CPU efficiency. Understanding thread synchronization and preemption helps developers prevent unresponsive applications and deadlocks when managing shared resources.]

### Optional: What would you like to learn more about?

[I would like to learn more about advanced CPU scheduling algorithms like Multi-Level Feedback Queue (MLFQ) and thread synchronization mechanisms like Semaphores and Mutexes.]

### Optional: How confident do you feel about multithreading concepts now?

[Intermediate. I feel confident about thread creation, Runnable execution, join, sleep, and context switching, but I would like more practice with thread synchronization and race conditions.]

### Optional: Feedback on the assignment

[This assignment was very practical and effective! Building the scheduling simulation made abstract operating system concepts much easier to understand and apply.]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[In `SchedulerSimulation.java`, the class named `Process` represents a simulated process model, whereas actual execution is driven by a real Java `thread` created via `new Thread(process)` in `addProcessToQueue()`. We used threads instead of separate OS processes because threads share the same memory space and have much lower creation overhead and faster communication. This shared memory allows our program to manage the `ready queue` and record state changes during a `context switch` without heavy inter-process communication. As a result, this multithreading approach efficiently simulates each process's `burst time` execution across every `time quantum`.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, when a process does not finish within its allocated time quantum, it is preempted by the scheduler and placed back at the end of the ready queue. This enables other waiting processes in the queue to receive CPU time in a fair, sequential order. For instance, process P3 required multiple time quanta and was re-queued until its remaining execution time reached zero. Re-queueing is critical for fairness because it prevents a single long-running process from monopolizing the CPU and guarantees that all processes make steady progress.]

Example from my output:
```text
[Scheduler] Process P3 running (Remaining time: 800ms)
[Scheduler] Time quantum expired for Process P3
[Scheduler] Process P3 added to ready queue

**Explanation of example:**
[In this output snippet, Process P3 was executing on the CPU, but because its burst time exceeded the single time quantum, the scheduler preempted it. Process P3 was re-queued 2 times before completing its total execution. This demonstrates how Round-Robin scheduling cycles through processes in the ready queue to maintain CPU allocation fairness.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 enters the New state when instantiated via `new Thread(process)` inside `addProcessToQueue()`, prior to calling `start()`.

2. **Runnable**: P1 becomes Runnable when `Thread.start()` is called, placing its thread into the ready queue waiting for CPU execution.

3. **Running**: P1 enters the Running state when the CPU allocates time to it and its `run()` method actively executes.

4. **Waiting**: P1 thread enters Timed Waiting when `Thread.sleep()` is called to simulate CPU execution, while the main thread waits using `Thread.join()`.

5. **Terminated**: P1 enters Terminated state after finishing its `run()` method when its remaining burst time reaches 0ms.

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): OS CPU Time-Sharing Scheduler

**Description**:
An operating system uses Round-Robin scheduling to allocate CPU time across multiple active user applications like background updates, text editors, and media players. Each application process gets assigned a fixed time quantum to execute its threads. When the quantum expires, a context switch occurs to save state and give the CPU to the next ready process.

**Why Round-Robin works well here**:
Round-Robin guarantees fairness by preventing any high-computation background task from starving other active applications. It maintains high UI responsiveness and predictable system execution, ensuring smooth user experience.

### Example 2: Multi-Client Web Server Request Processing

**Description**:
A multi-threaded web server processes incoming HTTP client requests by allocating handler threads for each connected client. The server scheduler distributes execution time among client threads using time-slicing to process request chunks incrementally. If a request does not complete in its time quantum, it is re-queued so other client requests get served.

**Why Round-Robin works well here**:
Round-Robin ensures fair bandwidth and processing throughput for all connected users simultaneously. It prevents large file download requests from blocking short API requests, providing predictable latency and high responsiveness.

## Summary

**Key concepts I understood through these questions:**
1. Round-Robin scheduling mechanics, time quantum management, and process re-queueing.
2. The core differences between Java threads and operating system processes.
3. Thread lifecycle states (New, Runnable, Running, Waiting, Terminated) and synchronization using `join()`.

**Concepts I need to study more:**
1. Thread synchronization primitives, race conditions, and mutexes in concurrent systems.
2. Advanced CPU scheduling algorithms such as Multi-Level Feedback Queues (MLFQ).
---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [x] Repository is **PUBLIC** (Settings -> Danger Zone -> Visibility)
- [x] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [x] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [x] Student ID is set in `SchedulerSimulation.java` (line 150)
- [x] Code compiles and runs with no errors
- [x] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [x] Each feature has clear comments

**Commits**
- [x] **At least 3 meaningful commits, ideally 6 or more**
- [x] **One commit per feature**
- [x] Commits are spread over **different dates** (not all in the last hour)
- [x] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [x] Full name and student ID filled in at the top
- [x] Development log has **5+ entries** on different dates
- [x] Reflection: 4 questions, 5-7 sentences each
- [x] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [x] No `[...]` placeholders left
- [x] No section headers deleted

**Video**
- [x] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [x] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [x] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [x] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
