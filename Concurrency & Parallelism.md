Basics (Foundational Concepts)

What is the difference between concurrency and parallelism?

What is the Global Interpreter Lock (GIL)?

How does the GIL affect multithreading in Python?

When should you use threads vs processes?

What are CPU-bound tasks and I/O-bound tasks?

Why is threading useful for I/O-bound tasks?

Explain the difference between synchronous, asynchronous, and non-blocking operations.

What is the event loop in asyncio?

What is the difference between concurrent.futures.ThreadPoolExecutor and ProcessPoolExecutor?

What is the difference between multiprocessing.Process and threading.Thread?

🔹 Threading (Concurrency using Threads)

How does Python achieve concurrency with threads despite the GIL?

What is context switching?

How do you prevent race conditions in Python threads?

Explain Locks, RLocks, Semaphore, and Condition variables.

What is a deadlock? How do you avoid it?

How do you daemonize a thread in Python?

What is the queue.Queue class used for in threading?

How does the GIL influence CPU-bound multithreaded programs?

How would you implement a producer–consumer pattern using threads?

What is the difference between thread-safe and non-thread-safe objects?

🔹 Asyncio (Asynchronous Programming)

What is asynchronous programming?

What does the async keyword do in Python?

What does the await keyword do?

What is a coroutine?

Explain the asyncio event loop.

What are tasks in asyncio?

Difference between asyncio.gather and asyncio.wait?

How does exception handling work inside coroutines?

What is the difference between concurrent.futures and asyncio?

What is backpressure in async systems?

🔹 Multiprocessing (True Parallelism)

How does Python achieve parallelism with multiprocessing?

What is the role of IPC (Inter-Process Communication)?

How does multiprocessing.Pool work?

What is the difference between Pool.map and Pool.apply?

How do processes share memory?

What is copy-on-write?

How does multiprocessing avoid the GIL?

Explain overheads of process creation.

When would multiprocessing be slower than threading?

How do you debug multiprocessing code?

🔹 Advanced Concepts

What is Amdahl's Law and how does it apply to Python parallelism?

Explain GIL-free implementations like PyPy, Jython, and Cython.

How does Python implement green threads (gevent, eventlet)?

What are futures in concurrent programming?

How does asyncio handle thousands of connections efficiently?

Explain the concept of cooperative multitasking.

What is parallel I/O?

What are thread pools and process pools?

What is the difference between parallelism, vectorization, and multiprocessing?

What is the role of libuv in libraries like uvloop?

How do you use joblib for parallel processing?

What is a barrier synchronization?

What are fan-in and fan-out patterns?

Explain task scheduling in modern Python runtimes.

Explain Python's GIL behavior in CPython 3.12+ (improvements).

🔹 Practical Coding Questions

Implement a multithreaded web scraper.

Write code to run a function concurrently over a list of inputs using ThreadPoolExecutor.

Convert blocking I/O code to async.

Write an async function that makes 100 HTTP requests concurrently.

Implement a multiprocessing worker pool manually.

How do you cancel a running asyncio task?

How do you ensure graceful shutdown of threads/processes?

How do you handle shared state safely in multithreading?

Implement a rate limiter using asyncio.

Implement a producer-consumer system using multiprocessing Queue.

🔹 System Design + Python Concurrency

How would you build a real-time messaging system in Python?

How do async frameworks like FastAPI achieve concurrency?

Why is asyncio preferred for APIs but not for CPU-bound tasks?

How to build a parallel ETL pipeline?

What concurrency model does Celery use?

How does Python handle concurrent DB connections?

How do you scale Python concurrency across multiple machines?

How do you build a task scheduler like Airflow using Python concurrency?

What are typical bottlenecks in async Python systems?

How to design a high-throughput file processing system?

🔹 GIL / Internals Questions (Expert-Level)

How often does the GIL switch?

What operations release the GIL?

Why doesn’t Python remove the GIL entirely?

Explain the “check interval” in GIL.

What is the new per-interpreter GIL proposal?

How does Cython release the GIL?

How do NumPy operations bypass the GIL?

Does asyncio bypass the GIL? Why/why not?

How does Python internally switch between threads?

What is the difference between GIL, TLS (Thread Local Storage), and atomic operations?

🔹 Troubleshooting & Debugging Questions

How do you identify deadlocks in Python?

How do you detect race conditions?

How do you benchmark multithreaded vs multiprocessing code?

How do you profile async Python code?

How do you avoid memory leaks in async systems?

How do you debug stuck event loops?

How to detect if you're overusing threads?

When threads appear faster but are actually slower — why?

How do you debug orphaned child processes?

How to handle exceptions in ThreadPoolExecutor or ProcessPoolExecutor?

🔹 Real-World Scenarios

You need to process 1 million I/O operations — what model do you use?

You have 100 MB of CPU-heavy computation — what do you use?

You want to build a chat server — what do you use?

You want to parallelize ML model training — what approach?

How do you design a concurrency system that scales to 10k connections?

How do you mix threads + asyncio safely?

How do you avoid CPU starvation in async systems?

When should you NOT use multiprocessing?

How to build a fault-tolerant concurrent pipeline?

How to choose between FastAPI async handlers vs normal handlers?