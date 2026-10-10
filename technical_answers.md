# Part C: Technical Answers (0.5 mark)

## Question 1: Thread vs Process


[process class in project is simulated process its implements runnable, while threads executes work after in the addprocesstoqueue() method create a thread for simulated process after that the schedular use currentthread.start() to execute currentthread.join()]

## Question 2: Ready Queue Behavior

[in project the time quantum 3000ms and p7 6640ms and first execution p7 use 3000ms and has 3640ms and second execution use 3000ms and 640ms remaining so it will requeued 640ms twice after initial queue until cpu finish]


## Question 3: Thread Lifecycle



1. **New**: [p1 java thread enter new state when addProcessToQueue execute]

2. **Runnable**: [p1 runnable if schedullar calls current thread]

3. **Running**: [when selected to execute and performs run method]

4. **Waiting**: [p1 thread enters time waiting state in thread.sleep(time)]

5. **Terminated**: [when p1 still work remaining the project create other object]

## Question 4: Real-World Applications
[os can use round robin scheduling to give runnable tasks to use cpu tasks it is simulation and tinme quantum limits can execute before scheduler tasks and give another task it will return to the ready queue, a context switch allows the cpu executing one task resume another]

