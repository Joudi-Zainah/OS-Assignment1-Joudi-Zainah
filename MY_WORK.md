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
| **Full Name** | [Joudi Ghazi Zainah] |
| **Student ID** | [446052698] |
| **University Email** | [446052698]@std.psau.edu.sa |
| **GitHub Username** | [Joudi-Zainah] |
| **Repository Link** | [https://github.com/Joudi-Zainah/OS-Assignment1-Joudi-Zainah] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

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

### Entry 1 - [October 4, 2026, 7:34 PM]
**What I did**:Set up the project environment, and update the student ID.

**Details**:
1-Downloaded the required project files.
2-Opened the project in the IDE.
3-Checked the required tools and extensions.
4-Committed my changes to Git.

**Challenges**:Installing Git and the required extensions was challenging.

**Solution**:I checked which tools and extensions were suitable for my operating system and installed them correctly.

**Time spent**:3 hours.

---

### Entry 2 - [October 6, 2026, 12:00 AM]
**What I did**:Implemented the priority feature.

**Details**:
1-Added the priority feature to the simulation.
2-Worked on assigning priority values to processes.
3-Checked the priority values in the program output.
4-Committed my changes to Git.

**Challenges**:Adding priority without affecting the Round Robin scheduling was challenging.

**Solution**:I made sure I understood how priority works and checked the program output after implementing the feature.

**Time spent**:1 hour

---

### Entry 3 - [October 6, 2026, 12:52 AM]
**What I did**:Implemented the context-switching feature.

**Details**:
1-Added the context-switching logic to the simulation.
2-Worked on tracking switches between processes.
3-Checked the context-switching output.
4-Committed my changes to Git.

**Challenges**:Tracking context switches correctly and making sure they were calculated properly was challenging.

**Solution**:I reviewed the context-switching logic and checked the output to make sure the number of switches was correct.

**Time spent**:1 hours and half.

---

### Entry 4 - [October 8, 2026, 10:31 PM]
**What I did**:Implemented waiting time and turnaround time.

**Details**:
1-Worked on calculating the waiting time for each process.
2-Added the turnaround time calculation.
3-Checked the results in the program output.
4-Committed my changes to Git.

**Challenges**:Calculating waiting time and turnaround time correctly and displaying them without repeating the results was challenging.

**Solution**:I used output logic to display the results correctly and avoid duplication.

**Time spent**:3 hours and half.

---

### Entry 5 - [October 8, 2026, 11:16 PM]
**What I did**:Worked on the My Work file.

**Details**:
1-Worked on answering the assignment questions in the My Work file.
2-Answered the technical questions related to the assignment.
3-Reviewed my answers and made sure they matched the concepts used in the code.
4-Committed my changes to Git.

**Challenges**:Understanding the technical questions and connecting the theoretical concepts to the code was challenging.

**Solution**:I reviewed the concepts and tried to explain them in my own words while connecting them to the code.

**Time spent**:2 hours and half.

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

**Total time spent on assignment**: [11 hours and half]

**Most challenging part**:Calculating waiting time and turnaround time correctly and displaying the results without repetition.

**Most interesting learning**:Understanding how different scheduling concepts work together in the simulation.

**What I would do differently next time**:I would plan the implementation more carefully and test each feature step by step.

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

[I learned that the program can run multiple threads to do or perform a task, by multithreading. In addition the Runnable interface defines the task that a thread will execute responding to its run() method. I also learned how to use methods such as Thread.start() to start a thread.Also Thread.join() makes the program wait for a thread to finish before continuing.Through multithreading, I learned that threads need to be coordinated carefully to keep the simulation organized and running correctly.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The first challenge was setting up the correct development tools and environment for my operating system, which took some time. Another challenge was adding process priorities without affecting the Round-Robin scheduling order. For the context switch counter,I had to know the correct place to count each time a process started running. For the waiting time feature I needed to calculate how long each process waited in the ready queue accurately. Also I  had to make sure each process appeared only once in the final summary table because each process can be with multiple thread.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[First of all I read the assignment instruction and understanding the code carfully. I worked step by step for each feature rather than doing them all at ones. With every change that I make I run the program to check the output. Also I checked that process priorities were displayed without changing the Round-Robin queue order. I also checked the context switch counter and the final waiting time summary.For the last feature I checked the waiting time and turnaround time values in the summary table.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Firstly multithreading is useful because it allows an application to handle multiple tasks at the same time. For example, in a photo editing app can process image changes while still responding to user actions.In a shopping app, users can search for products while their shopping cart updates in the background.In a banking app, users can view their account information while recent transactions are loading .Also, in a web browser can download files while the continues browsing.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

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

[A process is a program in execution that has its own memory space and a thread is a part of execution within a process. when we talk about a single process can contain multiple threads, which share the process's memory and resources. Threads are usually easier and faster to create than processes, and they can share data because they belong to the same process. In my code, the Process class represents a simulated process, and new Thread(process) creates a thread to execute its code. Also start() starts the thread and join() makes the scheduler wait for it to finish.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[Round robin scheduling gives each process a fixed amount of time called a time quantum. If a process does not finish within its time quantum it goes back to the end of the queue to wait for its next turn. In my code the time quantum is 2000 milliseconds, so process P1 runs for 2000 milliseconds first and then has 1925 milliseconds remaining. P1 goes back to the queue and runs again later until it finishes. This continues until all processes are completed.]

Example from my output:
```
[
  ▶ P1 executing quantum [2000ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P1 completed quantum 2000ms │ Overall progress: [██████████░░░░░░░░░░] 50%
     Remaining time: 1925ms
  ↻ P1 yields CPU for context switch

  ➕ P1 added to ready queue │ Burst time: 3925ms
 Priority: 2
┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P3 → P4 → P5 → P6 → P7 → P8 → P9 → P10 → P11 → P12 → P13 → P14 → P15 → P16 → P1]
└───────────────────────────────────────────────────────────────────────────────
▶ P1 executing quantum [1925ms] 
  ⚡ Quantum progress: [███████████████] 100%
  ⏸ P1 completed quantum 1925ms │ Overall progress: [████████████████████] 100%
     Remaining time: 0ms
  ✓ P1 finished execution!

┌─ Ready Queue ─────────────────────────────────────────────────────────────────
│ [P3 → P6 → P7 → P8 → P11 → P13 → P14 → P15 → P16]
└───────────────────────────────────────────────────────────────────────────────]
```

**Explanation of example:**
[The first executes of P1 for 2000 ms but still has 1925 ms remaining so it waited till the end of the ready queue. Other processes get their turns before P1. Then P1 executes for the remaining 1925 ms and finishes.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when I create its thread using new Thread(process), before I call start().]

2. **Runnable**: [P1 becomes Runnable when I call start(), which allows the thread to start executing.]

3. **Running**: [P1 is Running when it is executing its code.]

4. **Waiting**: [A thread waits when it needs to wait for another thread to finish. In my code for example, the main thread uses join() to wait for the process threads, and p1 pause for a short time using Thread.sleep().]

5. **Terminated**: [P1 is Terminated when it finishes executing its run() method.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[an operating system uses Round Robin to give each process a turn to use the CPU. Each process gets a time quantum and if it does not finish it goes back to the end of the queue. This is similar to my simulation where each process runs for 2000 milliseconds before moveing to the next process. The context switch happens when the CPU stops running one process and switches to another.]

**Why Round-Robin works well here**:
[Round Robin works well because each process gets a fair chance to use the CPU. It also helps the system respond faster instead of making one process wait too long. The time quantum makes the scheduling more predictable.]

### Example 2: [Handling Multiple Client Requests in a Server]

**Description**:
[A server can use Round Robin to give different client tasks a turn to execute using threads. Each thread gets a limited amount of execution time before the scheduler moves to another ready thread. This is similar to my simulation where each process gets 2000 milliseconds and unfinished processes return to the queue. A context switch happens when the CPU switches from one thread to another.]

**Why Round-Robin works well here**:
[Round Robin can help prevent one thread from using all the CPU time while other threads wait. It improves fairness and helps different client tasks get a chance to execute. This is useful when a server handles multiple tasks at the same time, although real servers may use other scheduling methods too.]

## Summary

**Key concepts I understood through these questions:**
1.How Round Robin uses a time quantum to schedule processes.
2.How context switching allows the CPU to execute different tasks.
3.The difference between a process and a thread.

**Concepts I need to study more:**
1.How different scheduling algorithms compare in terms of fairness and response time.
2.How context switching works in operating systems.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
