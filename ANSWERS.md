# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**

A process is a full program with its own memory, while a thread is a smaller part of a program that shares memory with other threads.

We used threads in this assignment because they are faster and use fewer resources than processes.

Differences:

- Threads share memory → faster communication
- Processes have separate memory → slower

In the code:
Thread thread = new Thread(process);

---


---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

If a process does not finish in its time quantum, it is stopped and moved to the end of the queue.

Example:
P1 completed quantum
P1 yields CPU
P1 added to ready queue

This is important for fairness, so all processes get a chance to run.



Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what's happening in the output snippet you pasted]

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**


A thread goes through these states:

- New: when the thread is created
- Runnable: when start() is called
- Running: when run() is executing
- Waiting: when using join() or sleep()
- Terminated: when execution finishes

Example: P1 starts with start(), runs, then finishes.




## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

1. Web Server: handles many users, each gets CPU time
2. Media Player: runs audio and video together

Round Robin is good because it gives fair time to each task and keeps the system responsive.


### Example 1: [Name of application/scenario]

**Description**: 
[Describe the real-world scenario or application]

**Why Round-Robin works well here**: 
[Explain why Round-Robin scheduling is suitable. Consider fairness, responsiveness, predictability, etc.]

### Example 2: CPU Scheduling

Description:
In operating systems, the CPU time is shared among processes. Each process is given a small fixed time called a time quantum, and then the CPU moves to the next process in a circular order.

Why Round-Robin works well here:
Round-Robin works well because it ensures fairness among all processes. Every process gets an equal chance to run, which prevents any single process from monopolizing the CPU. It also improves system responsiveness.
---

## Summary

**Key concepts I understood through these questions:**
1. The concept of time quantum in scheduling.
2.The importance of fairness in resource allocation.
3.How Round-Robin improves responsiveness and reduces waiting time.. 

**Concepts I need to study more:**
1. How to choose the optimal time quantum.
2.The differences between Round-Robin and other algorithms like FCFS and SJF.

