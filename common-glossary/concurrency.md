# Concurrency

**Concurrency** refers to techniques that make programs more usable. Concurrency can be implemented, and is used a lot, on single processing units, but it may benefit from multiple processing units with respect to speed.

Though, it is the case that the tasks may look like they are running simultaneously, but in reality they are not. Concurrency takes advantage of a CPU feature known as *time-slicing* - provided by the [operating system](./operating-system.md). This feature allows each task to run part of its execution before going into a waiting state. When the first task is in the waiting state, the CPU is assigned to the second task to complete its part of the task.

## Related Terms

- [parallelism](./parallelism.md)
- [thread](./thread.md)
- [multithreading](./multithreading.md)

### References

*Parallelism vs. concurrency.* (n.d.). Retrieved from https://wiki.haskell.org/Parallelism_vs._Concurrency. 

Saurabh. (2021, July 18). *Concurrency vs parallelism.* Retrieved from https://howtodoinjava.com/java/multi-threading/concurrency-vs-parallelism/. 