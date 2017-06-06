### Material

* [Little Book of Semaphores](http://greenteapress.com/wp/semaphores/): A comprehensive survey of different synchronization primitives and how they're used as building blocks for different concurrency problems.
* [Intro to OS](https://classroom.udacity.com/courses/ud923)
* [Advanced OS](https://classroom.udacity.com/courses/ud189)
* [Operating Systems](https://www.ops-class.org/courses/buffalo/CSE421_Spring2017/)
* Async IO: Here's a set of links that will hopefully demystify what async IO really is, and how they relate to lower level constructs like event-loops which provide abstractions over epoll, kqueue etc. It's also important to distinguish between user-space, green, native and kernal threads. It's also important to understand these in the backdrop of other programming models like co-routines (ex: Golang), actors (ex: Scala w/ Akka), LWPs (Erlang). It's important to understand the full lifecycle of a request from when a client connects to a server to how it handles the processing.
  * [PThreads Primer](http://www8.cs.umu.se/kurser/TDBC64/VT03/pthreads/pthread-primer.pdf)
