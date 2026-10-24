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
| **Full Name** | [Abdulrahman Abdullah Almuaythir] |
| **Student ID** | [445050211] |
| **University Email** | [445050211]@std.psau.edu.sa |
| **GitHub Username** | [Abdulrahman-Almuaythir] |
| **Repository Link** | [https://github.com/Abdulrahman-Almuaythir/OS-Assignment1-Abdulrahman-Almuaythir] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1wngQe19U_GOmpFywko-czs46tjmlIYyr/view?usp=sharing]

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

### Entry 1 - [October 2, 2026, 1:01 AM]
**What I did**: Initialized the repository and configured my student ID

**Details**: Cloned the assigned GitHub repository locally to VS Code.
Changed student ID on line 150 to my actual ID (445050211)
Verified student ID output and basic project configuration.
Committed changes with message: Update student ID.


**Challenges**: Git remote connection permission error when pushing.

**Solution**: Re-authenticated GitHub credentials via SSH key in VS Code terminal.

**Time spent**: 40 minutes

---

### Entry 2 - [October 7, 2026, 5:49 PM]
**What I did**: Implemented Process Priority handling  (Feature 1)

**Details**: Added priority field and getter/setter methods to the process class.
Modified process initialization to assign unique priority levels.
Compiled and executed the program to verify priority-based scheduling output.
Committed changes with message: Feature 1: Added priority field to Process class

**Challenges**: Priority values were not displaying properly in the console output. 

**Solution**: Updated the process printing method to format and include the priority attribute.

**Time spent**: 1 hour

---

### Entry 3 - [October 10, 2026, 6:46 AM]
**What I did**: Implemented Context Switch tracking (Feature 2)

**Details**: Added context switch counter logic in SchedulerSimulation.java.
Updated thread execution loops to track every time the CPU switches execution between processes.
Verified that the total context switches are correctly calculated and outputted at the end of execution.
Committed changes with message: Feature 2: Implemented context switch counter

**Challenges**:Context switch count was incrementing incorrectly when processes re-entered the ready queue.


**Solution**: Traced thread execution steps and refined the counter increment condition to only trigger during actual process switches.
**Time spent**: 1 hour

---

### Entry 4 - [October 10, 2026, 10:43 AM]
**What I did**: Implemented Waiting Time calculation logic (Feature 3)

**Details**: Added waiting time calculation tracking for each process during execution.
Updated the console summary output to display individual and average waiting times.
Verified simulation parameters and thread timing calculations.
Committed changes with message: Feature 3: Added waiting time tracking and summary table

**Challenges**: It took a lot of time to fully understand thread state transitions and correctly compute waiting times.

**Solution**: Managed my time by dividing the task into smaller parts and reviewed core thread concurrency and synchronization concepts.

**Time spent**: 3 hour

---

### Entry 5 - [October 10, 2026, 4:18 PM]
**What I did**: Answered technical questions and completed reflection

**Details**:Completed questions Q1-Q4 and summary in README.md.
Filled out the reflection section in MY_WORK.md.
Verified concepts related to Round-Robin scheduling and threads.
Committed and pushed documentation updates.

**Challenges**:Needed to refresh some information and review the solutions.

**Solution**: Re-read lecture notes and reviewed the code logic.

**Time spent**:2 hour

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

**Total time spent on assignment**: [8 hours]

**Most challenging part**:Feature 3

**Most interesting learning**:Thread vs Process

**What I would do differently next time**:start the home work early

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

[This assignment gave me an insight into the structure of the Java language, and the way in which tasks can be distributed using the Runnable and Thread classes. I discovered that I could launch separate tasks using the Thread.start method, and that I needed to use the Thread method join in order to get the program to wait until the task had completed. Simulating CPU work by breaking down burst times into smaller steps using Thread.sleep helped me understand how round-robin time-sharing works in code. When I ran the program, I saw that the console message paused and resumed, as each process was brought to the front. I saw, too, that you can’t start a thread that has finished; I had to create a new one whenever an incomplete task came to the head of the queue. This exercise has allowed me to bring into practice the theory of parallel processes which we learn in class.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[I found the most difficult part of this assignment to be the implementation of Feature 3, in which the elapsed waiting time and execution time for each thread is calculated. Because the Round Robin mechanism takes the processes in and out of the ready queue, calculating the waiting time is a more difficult task than a one-time calculation. I had to set the lastReadyTime of each process with a system.currentTimeMillis when it was created and again when it entered the ready list. It was also difficult to add up the waiting times inside the updateWaitingTime method without confusing the formula for the total execution time. Some of the processes would be incorrect and I had a lot of debugging to do. I also had to review my math skills. Making sure the final summary table printed all the aggregated numbers correctly at the end was really hard work.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I passed this difficulty by the simple expedient of step-by-step testing and by the aid of debugging with simple println lines in my code. Whenever the output in the console looked out of sorts, I added System.out.println lines to see if the processes in the ready queue were moving around properly, and I re-read the assignment instructions carefully to be sure I understood what the Round Robin algorithm was supposed to be. Testing my code after every small change helped me catch mistakes early and correct them before they became bigger problems. Comparing my terminal output against the expected assignment requirements gave me confidence that the scheduler was running as intended. This step-by-step approach made it easy to correct logical errors and complete the assignment successfully.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[In the future, I would spend more time planning the code structure before I start writing classes. I would draw up a paper flowchart for the process's life-cycle and thread-queues first. Designing the timing metrics and different states of the process beforehand would have saved a lot of time on the later debugging of the calculations. I would also make smaller unit tests for methods like the waiting-time function, instead of testing everything with the simulation. Starting from a clearer framework, and testing small parts early on, it would have gone much more smoothly.]

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

[In this assignment, a ⁠Process⁠ is a simulated program represented by a custom Java class, while the actual execution and CPU scheduling are handled by real Java ⁠threads⁠. A process contains its own execution space, whereas threads exist inside a process and share its memory resources. We used threads because they are lighter to create than separate processes and they share memory, so the main thread and each process's thread can both access the same Process object. Specifically, in ⁠SchedulerSimulation.java⁠, the method ⁠addProcessToQueue()⁠ instantiates each simulated process by wrapping it in a real thread using the ⁠new Thread(process)⁠ line.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, when a process cannot complete its execution within the assigned time quantum, it is temporarily paused and re-queued at the back of the ready queue. For instance, my process P14 started with a burst time of ⁠7393ms⁠ and required three execution cycles: it ran for its first ⁠3000ms⁠ quantum, yielded the CPU, ran for a second ⁠3000ms⁠ quantum, and finally executed its remaining ⁠1393ms⁠ before terminating. This re-queueing mechanism ensures fairness across the system by preventing long processes from monopolizing CPU time. Consequently, shorter processes like P1 and P2 were able to finish execution early without being delayed by P14.]

Example from my output:
```
[P14 completed quantum 3000ms | Remaining time: 4393ms
  P14 yields CPU for context switch
  P14 (Priority: 4) added to ready queue | Burst time: 7393ms]
```

**Explanation of example:**
[This snippet demonstrates P14 exceeding its ⁠3000ms⁠ time quantum while having ⁠4393ms⁠ remaining. As a result, the scheduler forces a context switch and places P14 back into the ready queue so other processes can receive CPU time.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1's thread is in the New state after ⁠new Thread(process)⁠ in ⁠addProcessToQueue()⁠ and before ⁠start()⁠ is called.]

2. **Runnable**: [P1 enters this state when its thread starts via ⁠Thread.start()⁠ and runs its code]

3. **Running**: [Running: P1 runs directly on the CPU while executing its time quantum inside the ⁠run()⁠ method.]

4. **Waiting**: [P1's thread enters Timed Waiting when it sleeps via ⁠Thread.sleep()⁠, while the main thread enters the Waiting state while waiting at ⁠Thread.join()⁠.]

5. **Terminated**: [The thread reaches Terminated when ⁠run()⁠ ends, which for P1 happens after its first quantum, right after ⁠P1 finished execution⁠ is printed.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[(operating-system level): OS CPU Scheduling.]

**Why Round-Robin works well here**:
[Operating systems use Round-Robin-style time slicing, often combined with priorities, to manage multiple programs running at the same time on a single CPU. It ensures fairness so no single heavy program freezes the system. Just like in my simulation where the time quantum was ⁠3000ms⁠ and processes like P14 yielded for other processes to run, the OS gives each program a small time slice. When a switch happens, the context switch saves the state of one program and loads another.]

### Example 2: [Name of application/scenario]

**Description**:
[ (application level): Multi-Tasking Desktop Apps (Browser + Music Player)]

**Why Round-Robin works well here**:
[A common real-world example is running a web browser while playing background music on a media player on your computer. Both applications run on different threads, and the OS shares the CPU between them in turns using Round-Robin principles. This ensures that a heavy webpage loading does not stutter or freeze your music playback, keeping the system smooth and fair for all running applications.]

## Summary

**Key concepts I understood through these questions:**
1 Round-Robin scheduling.
2 Thread Lifecycle
3 Processes vs.Threads.

**Concepts I need to study more:**
1 Context switching overhead.
2 Thread synchronization.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Blackboard does not accept submissions after the deadline, which is **October 10, 2026**.

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
