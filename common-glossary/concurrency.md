# Concurrency

Concurrency is essentially applicable when we talk about a minimum of two tasks or more. When an application is capable of executing two tasks *virtually* at the same time, we call it a concurrent application.

Though, it is the case that the tasks may look like they are running simultaneously, but in reality they are not. Concurrency takes advantage of a CPU feature known as *time-slicing* - provided by the [operating system](./operating-system.md). This feature allows each task to run part of its execution before going into a waiting state. When the first task is in the waiting state, the CPU is assigned to the second task to complete its part of the task.

## Related Terms

- [parallelism](./parallelism.md)
- [thread](./thread.md)
- [multithreading](./multithreading.md)

### References

Saurabh. (2021, July 18). *Concurrency vs parallelism.* Retrieved from https://howtodoinjava.com/java/multi-threading/concurrency-vs-parallelism/. 