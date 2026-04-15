DEVELOPMENT_LOG.md

Entry 1 - [March 20, 2026, 3:00 PM]

What I did:
Set up GitHub repository and initial project setup

Details:

Created GitHub account using university email

Forked the starter repository

Renamed repository to include my name

Added my student ID in SchedulerSimulation.java

Ran the code for the first time to understand output


Challenges:
I was not familiar with how to fork repositories and edit files directly on GitHub

Solution:
Watched a tutorial and followed the steps to fork and edit files correctly

Time spent:
40 minutes


---

Entry 2 - [March 21, 2026, 5:30 PM]

What I did:
Understanding the starter code and how the scheduling works

Details:

Read the Process class and SchedulerSimulation class

Learned how Round-Robin scheduling works

Observed how threads are created and executed

Tested the program multiple times to understand behavior


Challenges:
It was difficult to understand how threads and queue work together

Solution:
Reviewed lecture slides and searched examples online about threading and queues

Time spent:
1 hour


---

Entry 3 - [March 22, 2026, 4:00 PM]

What I did:
Implemented Feature 1: Process Priority

Details:

Added priority variable to Process class

Generated random priority values (1–5)

Modified output to display priority when process enters queue

Tested to ensure values appear correctly


Challenges:
At first, I forgot to display the priority in the output

Solution:
Updated the print statement to include priority information

Time spent:
45 minutes


---

Entry 4 - [March 23, 2026, 6:00 PM]

What I did:
Implemented Feature 2: Context Switch Counter

Details:

Created a static variable to count context switches

Incremented counter every time a process starts execution

Displayed total count at the end of simulation


Challenges:
I was unsure where exactly to increment the counter

Solution:
Placed the increment inside the scheduler loop before starting each thread

Time spent:
50 minutes


---

Entry 5 - [March 24, 2026, 7:00 PM]

What I did:
Implemented Feature 3: Waiting Time Tracking

Details:

Added creation time and waiting time variables

Used System.currentTimeMillis() to track time

Calculated waiting time after process completion

Displayed results in the final output


Challenges:
The waiting time calculation was confusing at first

Solution:
Reviewed how time differences work and adjusted the formula correctly

Time spent:
1 hour


---

Entry 6 - [March 25, 2026, 8:30 PM]

What I did:
Final testing and documentation

Details:

Tested all features together

Fixed minor bugs in output formatting

Completed DEVELOPMENT_LOG, REFLECTION, and ANSWERS files

Checked commits and repository structure


Challenges:
Some output values were not clear

Solution:
Improved formatting and added clearer print statements

Time spent:
45 minutes


---

 Summary

Total time spent on assignment:
~5 hours

Most challenging part:
Understanding how threads and scheduling work together and calculating waiting time correctly

Most interesting learning:
Learning how multithreading works in Java and how processes are scheduled using Round-Robin

What I would do differently next time:
Start earlier and practice more on threading concepts before implementing features
