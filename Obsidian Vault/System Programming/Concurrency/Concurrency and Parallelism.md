### Idea
![[Concurrency, Parallelism & Threads.pdf#page=2]]
#### Concurrency with processes
![[Concurrency, Parallelism & Threads.pdf#page=6]]
#### Threads
![[Concurrency, Parallelism & Threads.pdf#page=7]]
![[Screen Shot 2024-08-07 at 5.36.28 pm.png]]
#### Data Race
Both threads have access to the counter and to write the number, which may lead to unexpected final value when there's no synchronisation mechanisms in place. 
![[Screen Shot 2024-08-08 at 3.42.56 pm.png]]
#### Mutices 
- Ensures that only one thread can access the critical section at a time.
![[Concurrency, Parallelism & Threads.pdf#page=16]]
#### Deadlocks
![[Concurrency, Parallelism & Threads.pdf#page=18]]
#### Solving deadlock using a try-lock mechanism
![[Concurrency, Parallelism & Threads.pdf#page=19]]
#### Atomic Operations
- Guarantees that certain operations on shared data are performed atomically.
![[Concurrency, Parallelism & Threads.pdf#page=20]]

### Formally

#coding #assembly 



