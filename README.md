
# Java Multithreading Practice

## Overview

This project contains implementations of various Java multithreading concepts through 11 different problems. Each problem focuses on a different aspect of concurrent programming, such as thread creation, synchronization, deadlocks, producer-consumer patterns, and more.

## Technologies Used

- Java
- Multithreading
- Synchronization
- ReentrantLock

## Problems Implemented

### 1. Even and Odd Number Printing Using Threads
- **Description:** Create two threads to print even and odd numbers from 1 to 20.
- **Concept Used:** Basic thread creation and synchronization.

### 2. Sorting an Array Using Multiple Threads
- **Description:** Sort an array of integers using multiple threads.
- **Concept Used:** Parallel sorting and thread coordination.

### 3. Matrix Multiplication Using Threads
- **Description:** Perform matrix multiplication using multiple threads to speed up computation.
- **Concept Used:** Parallel computation and multi-threaded processing.

### 4. Sum of Prime Numbers Using Multiple Threads
- **Description:** Calculate the sum of all prime numbers up to a given limit using multiple threads.
- **Concept Used:** Task division, parallel computation.

### 5. Bank Account Simulation with Concurrent Transactions
- **Description:** Simulate a bank account where multiple threads perform concurrent deposits and withdrawals.
- **Concept Used:** Synchronization to prevent race conditions.

### 6. Deadlock Simulation Using Synchronization
- **Description:** Demonstrate a deadlock scenario using synchronized blocks.
- **Concept Used:** Synchronization and deadlock handling.

### 7. Yield Example in Multithreading
- **Description:** Demonstrate the use of the `yield()` method in Java to allow other threads to execute.
- **Concept Used:** Thread scheduling and yielding.

### 8. Producer-Consumer Problem
- **Description:** Implement the Producer-Consumer problem using multithreading.
- **Concept Used:** Inter-thread communication using `wait()` and `notify()`.

### 9. Learning ReentrantLock
- **Description:** Demonstrate the use of `ReentrantLock` for thread synchronization.
- **Concept Used:** Explicit locking mechanism in Java.

### 10. Bank Account Using ReentrantLock
- **Description:** Implement a bank account simulation using `ReentrantLock` for handling concurrent transactions.
- **Concept Used:** Fine-grained locking using `ReentrantLock`.

### 11. Read and Write Lock Using ReentrantReadWriteLock
- **Description:** Implement a program that demonstrates the use of `ReentrantReadWriteLock` for handling multiple read and write operations.
- **Concept Used:** Read-write locking for improved performance in concurrent read scenarios.

## How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/grithwikreddy/Multi-thread-Learning.git
   cd Multi-threading-Learning
   ```
2. Compile and run the Java program:
   ```sh
   javac org/example/Main.java
   java org.example.Main
   ```


