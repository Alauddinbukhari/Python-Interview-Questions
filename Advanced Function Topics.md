🔹 1. Core Advanced Function Concepts

What are first-class functions in Python?

How are functions different from methods?

What is the difference between arguments and parameters?

Explain positional-only, keyword-only, and default parameters.

What is function annotation? Is it enforced?

What happens when you pass a mutable object to a function?

How does Python handle memory allocation for function calls?

Can a function return multiple values? How?

🔹 2. *args and **kwargs

What are *args and **kwargs?

Can we use both *args and **kwargs in the same function?

What is the correct order of parameters in a function?

How do you unpack arguments when calling a function?

Difference between:

def func(a, *args, **kwargs):


and

def func(*args, a, **kwargs):

🔹 3. Lambda Functions

What is a lambda function?

When should you avoid using lambda?

Can a lambda contain multiple expressions?

Compare lambda vs def.

Give a real-world use case of lambda.

🔹 4. Higher-Order Functions

What is a higher-order function?

Examples of built-in higher-order functions?

Explain map(), filter(), and reduce().

Difference between map() and list comprehension?

When would you prefer filter() over list comprehension?

🔹 5. Closures

What is a closure in Python?

Why are closures useful?

Explain with an example.

How does Python remember values inside closures?

Difference between closure and class?

🔹 6. Decorators (Very Important)

What is a decorator?

How does a decorator work internally?

Why are decorators useful?

Write a decorator to measure function execution time.

How do you pass arguments to a decorator?

What is functools.wraps and why is it important?

Can a decorator modify function behavior?

🔹 7. Recursion

What is recursion?

What is a base condition?

Difference between recursion and iteration?

What causes a RecursionError?

Tail recursion — does Python support it?

🔹 8. Scope & Namespace

What are LEGB rules?

Difference between global and nonlocal?

When should you avoid global variables?

How does Python resolve variable names?

🔹 9. Generator Functions

What is a generator?

Difference between yield and return?

How does a generator save memory?

Generator vs iterator?

Can a generator be restarted?

🔹 10. Functional Programming Concepts

What is pure function?

What is immutability?

What are side effects?

How does Python support functional programming?

🔹 11. Advanced & Tricky Questions

What happens if a function has mutable default arguments?

Why is this dangerous?

How can you fix mutable default arguments?

Can a function modify a global variable?

Explain function caching (@lru_cache).

What happens if you return a function from a function?

How does Python handle function stack memory?

🔹 12. Real-World Coding Questions

Write a decorator that logs function calls.

Create a function that counts how many times it has been called.

Write a generator for Fibonacci numbers.

Write a function that accepts unlimited arguments and returns their average.

Create a closure that remembers user login attempts.

🔹 Bonus (Interview Gold)

How do decorators differ from middleware?

Can functions be serialized?

What is introspection in Python?

How do __call__() and functions relate?

Explain partial() from functools.