# Multithreading in Java

## 👨‍💻 Author

**Arpit Choubey — SDET | QA | Automation Engineer**
🔗 **LinkedIn** | **Medium**

## ⭐ Support

If this repository helps you, please **Star 🌟** it!

---

## Overview

This repository demonstrates **Multithreading in Java**, covering how threads work, their execution model, and practical producer–consumer examples. The project contains different Java classes explaining threads, thread operations, and how multiple threads execute concurrently.

---

## What is a Thread?

* A **thread** is the smallest unit of execution within a process.
* A process may contain multiple threads, and all threads share the same memory and resources of that process.
* Threads allow tasks to run concurrently, improving efficiency.
* Each thread follows its own **path of execution**.

---

## Multitasking

Multitasking allows an Operating System to perform **multiple tasks simultaneously**.

### 🔸 On Single-Core CPUs

* The CPU performs **time-sharing** — rapidly switches between tasks.
* Creates an illusion of parallelism.

### 🔸 On Multi-Core CPUs

* True parallel execution is possible.
* Different tasks or threads can run **simultaneously on separate cores**.

---

## What is Multithreading?

Multithreading is the ability of a program to execute **multiple threads concurrently** within a single process.

### ✔ How Multithreading Works

* A task can be broken into smaller subtasks (threads).
* These threads can run in parallel, improving performance.
* Threads share the same memory space, making communication fast.

### ✔ Example in Real World: Web Browsers

A browser uses multiple threads:

* One for rendering the page
* One for executing JavaScript
* One for user interactions (scrolling, clicking)

This results in:

* Faster performance
* Smooth user experience
* Increased responsiveness

---

## Key Benefits of Multithreading

* Better CPU utilization
* Faster execution of multiple operations
* Improved performance of complex tasks
* Smooth UI and responsive applications

---

## Folder Structure

```
MultithreadingInJava/
├── eclipse-workspace/
│   └── SeleniumPractice/
│       └── MultithreadingInJava/
│           └── src/
│               └── MultiThreads/
│                   ├── Company.java
│                   ├── Consumer.java
│                   ├── Main.java
│                   ├── MyAnotherThread.java
│                   ├── MyThread.java
│                   ├── Producer.java
│                   ├── ThreadOP.java
│                   └── package-info.java
├── .classpath
├── .gitignore
├── .project
└── README.md
```

---

## How to Run

1. Import the project into **Eclipse/IntelliJ** or run via terminal.
2. Run the `Main.java` file to observe thread execution.
3. Explore producer-consumer examples to understand thread synchronization.

---

## Notes

* Proper synchronization using `wait()`, `notify()`, `notifyAll()` or `Lock` API prevents race conditions.
* Threads should be handled carefully to avoid deadlocks.

