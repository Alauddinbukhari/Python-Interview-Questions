1. Time & Space Complexity (Python-specific)

How does Python list resizing work internally?

Why is list.append() amortized O(1)?

Why is iterating through a list faster than iterating through a dictionary?

What is the time complexity of slicing (list[a:b])?

What is the space complexity of Python recursion compared to loops?

How does Python optimize string concatenation?

Why is "".join(list_of_strings) faster than concatenating using +=?

2. Memory Management & Internals

How does Python’s memory allocation work? Explain small object allocator (pymalloc).

What is reference counting?

What are Python’s garbage collection generations?

Why does Python sometimes NOT free memory to the OS?

What is object interning? (e.g., small integers, strings)

How are Python objects stored in memory (PyObject structure)?

What is a memory leak in Python? Can Python have one?

3. Writing Efficient Python Code

When should you use list comprehensions over loops?

Difference between generator expressions vs list comprehensions.

When should you use map() / filter() vs loops?

How do you avoid repeated expensive function calls inside loops?

How to micro-optimize Python code using functools.lru_cache?

What is faster: in on list vs set vs dictionary? Why?

4. Multithreading, Multiprocessing & Concurrency

What is the GIL (Global Interpreter Lock)?

Why doesn’t multithreading speed up CPU-bound code?

Which tasks benefit from multithreading in Python?

How do you parallelize CPU-bound tasks in Python?

Difference between ThreadPoolExecutor and ProcessPoolExecutor.

Why is multiprocessing expensive in Python?

What is shared memory & copy-on-write?

5. Asynchronous Programming

When is asyncio useful?

Why is async not suitable for CPU-heavy work?

Difference between threading vs asyncio.

What is an event loop?

How do awaitables, tasks, and coroutines differ?

How does Python handle I/O without blocking the event loop?

6. Profiling & Debugging Performance

How do you measure execution time? (timeit)

How do you profile CPU bottlenecks? (cProfile, profile)

How do you profile memory usage? (memory_profiler)

How do you find slow SQL queries inside Python apps?

How to interpret profiling outputs (call counts, cumulative time)?

How to optimize hot loops (vectorization, caching, restructuring)?

7. Data Structures & Optimization

Why are sets faster than lists for lookups?

Why are tuples slightly faster than lists?

Difference between list vs deque performance.

When to use array module / NumPy arrays instead of lists?

How does hashing impact dictionary performance?

How to implement an LRU cache efficiently?

8. Real-world Performance Questions

How do you optimize a slow Python API endpoint?

How to speed up a Python script that processes millions of records?

How do you optimize database-heavy Python code?

How to reduce network latency in Python applications?

How to optimize performance in Django/Flask/FastAPI?

How do you handle large files efficiently?

How do you reduce memory usage in long-running processes?

9. Advanced Optimization Topics

Why is Python slow compared to Go/Java?

How does PyPy improve performance?

What are C extensions? (Cython, CPython API)

How does Numba speed up loops?

How to use vectorization for Python performance?

What is JIT compilation?

What is the difference between CPython, PyPy, Jython?