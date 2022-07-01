# 1. Introduction
Systems that are designed to do more than one thing at a time, it is called
asynchronous programming

**3 models of asyncrony:**
- Multiple machines: requester -> queues -> machines
- Multiple processes: on a single machine and share access to processing cores. Do not share resources
- Multiple threads: on a single process and share resources.
 
**Thread specific resource:**
- Stack memory: each thread has a dedicated stack
- Thread local storage
- Registers

**Thread sharing resource:**
- Heap memory

# 3. Task
- An activity that is ongoing while the main thread is continue.
- Support cancellation and reporting of progress

# 4. Thread
