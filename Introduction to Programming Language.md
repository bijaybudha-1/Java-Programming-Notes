# Chapter 1: Introduction to Programming Language and History of Java

## Learning Objectives

After studying this chapter, you will be able to:

* Understand what a programming language is.
* Explain the concept of algorithms and syntax.
* Describe the history of Java.
* Understand Java ownership and development.
* Explain the WORA principle.
* Understand JVM and Bytecode.
* Describe the Java program execution process.
* Explain why Java is platform independent.

---

# 1. What is a Programming Language?

A **programming language** is a formal language used by humans to communicate instructions to a computer so that it can perform specific tasks.

Programming languages act as a bridge between humans and computers.

## Examples of Programming Languages

| Language   | Description                                                 |
| ---------- | ----------------------------------------------------------- |
| Python     | Easy to learn and widely used.                              |
| Java       | Used for desktop, web, mobile, and enterprise applications. |
| C++        | Powerful language used in games and system software.        |
| JavaScript | Makes websites interactive.                                 |

### Key Points

* Used to write computer programs.
* Helps automate tasks.
* Consists of rules and syntax.
* Converts human instructions into machine-executable code.

---

# 2. What is an Algorithm?

An **algorithm** is a step-by-step procedure used to solve a problem or complete a task.

Before writing code, programmers often design an algorithm.

## Example Algorithm

### Problem

Add two numbers.

### Algorithm

1. Start
2. Input first number
3. Input second number
4. Add the numbers
5. Display the result
6. Stop

### Characteristics of a Good Algorithm

* Clear
* Simple
* Finite
* Efficient
* Produces correct output

---

# 3. What is Syntax?

**Syntax** refers to the set of rules that define how code must be written in a programming language.

Every programming language has its own syntax.

## Example

Correct Java syntax:

```java
System.out.println("Hello World");
```

Incorrect syntax:

```java
System.out.println("Hello World")
```

The missing semicolon (`;`) causes a syntax error.

### Importance of Syntax

* Prevents errors
* Improves readability
* Helps compiler understand code
* Ensures correct program execution

---

# 4. History of Java

Java is one of the most popular programming languages in the world.

## Development

* Developed by **James Gosling**
* Created at **Sun Microsystems**
* Developed in the early 1990s

## Original Name

The original name of Java was:

> **Oak**

The name was later changed to:

> **Java** (1995)

### Why Was It Called Oak?

The project was named after an oak tree outside James Gosling's office.

---

# 5. Ownership of Java

## Timeline

### Sun Microsystems

Java was originally developed and maintained by:

> Sun Microsystems

### Oracle Corporation

In **2010**, Oracle Corporation acquired Sun Microsystems and became the owner of Java.

### Current Owner

> Oracle Corporation

---

# 6. Key Principle of Java

## Write Once, Run Anywhere (WORA)

One of Java's most important principles is:

> **Write Once, Run Anywhere (WORA)**

This means a Java program can run on any device that has a JVM installed.

### Benefits

* Platform independence
* Reduced development cost
* Easy deployment
* Cross-platform compatibility

---

# 7. Why Java Became Popular

Java became popular because of several powerful features.

## 1. Platform Independent

Java programs can run on:

* Windows
* Linux
* macOS
* Unix

without changing the source code.

---

## 2. Bytecode and JVM

Java source code is converted into bytecode.

The JVM executes the bytecode on different operating systems.

---

## 3. Security

Java is designed to be secure.

Features include:

* No direct pointer manipulation
* Bytecode verification
* JVM security checks

---

## 4. Internet Support

Java was designed to support network-based applications.

Common uses include:

* Web applications
* Enterprise systems
* Cloud applications
* Distributed systems

---

# 8. Bytecode Concept

Java follows a two-step execution process.

## Step 1

Java source code is compiled into:

```text
Bytecode (.class file)
```

## Step 2

The JVM converts bytecode into machine code and executes it.

### Important Point

Java does **not** compile directly to machine code.

Instead:

```text
Java Code → Bytecode → Machine Code
```

---

# 9. What is Bytecode?

## Definition

**Bytecode** is the intermediate code generated when a Java program is compiled.

It is stored in a:

```text
.class file
```

### Characteristics

* Platform independent
* Not machine code
* Executed by JVM
* Portable across systems

---

# 10. How Java Program Execution Works

## Step 1: Write Java Source Code

```text
Program.java
```

## Step 2: Compile

The Java compiler (`javac`) converts source code into bytecode.

```bash
javac Program.java
```

Output:

```text
Program.class
```

## Step 3: Execute

The JVM loads and executes the bytecode.

```bash
java Program
```

The JVM converts bytecode into machine code and produces output.

---

# 11. Java Program Execution Flow

```text
Java Source Code (.java)
          │
          ▼
   Java Compiler (javac)
          │
          ▼
     Bytecode (.class)
          │
          ▼
 Java Virtual Machine (JVM)
          │
          ▼
      Machine Code
          │
          ▼
         Output
```

---

# 12. Key Points About Bytecode

Remember the following:

* Bytecode is NOT machine code.
* Bytecode is platform independent.
* Bytecode is stored in `.class` files.
* JVM executes bytecode.
* JVM converts bytecode into machine code.
* Bytecode enables Java's WORA principle.

---

# 13. Why Bytecode is Important

## 1. Platform Independence

Allows Java programs to run on different operating systems.

## 2. Portability

Programs can be moved between systems easily.

## 3. Flexibility

One bytecode file can run on multiple platforms.

## 4. Security

JVM verifies bytecode before execution.

## 5. WORA Support

Bytecode makes "Write Once, Run Anywhere" possible.

---

# Quick Revision

## Programming Language

A language used to communicate instructions to a computer.

## Algorithm

A step-by-step method for solving a problem.

## Syntax

Rules for writing correct code.

## Java

* Developed by James Gosling.
* Created at Sun Microsystems.
* Originally called Oak.
* Renamed Java in 1995.

## JVM

Java Virtual Machine that executes bytecode.

## Bytecode

Platform-independent intermediate code stored in `.class` files.

## WORA

Write Once, Run Anywhere.

---

# Interview Questions

### Q1. What is a programming language?

A programming language is a formal language used to give instructions to a computer.

### Q2. What is an algorithm?

An algorithm is a step-by-step procedure used to solve a problem.

### Q3. What is syntax?

Syntax is the set of rules that define how code must be written.

### Q4. Who developed Java?

James Gosling.

### Q5. What was Java originally called?

Oak.

### Q6. Who owns Java today?

Oracle Corporation.

### Q7. What is JVM?

The Java Virtual Machine that executes Java bytecode.

### Q8. What is bytecode?

Intermediate platform-independent code generated by the Java compiler.

### Q9. In which file is bytecode stored?

`.class` file.

### Q10. What does WORA stand for?

Write Once, Run Anywhere.

### Q11. Why is Java platform independent?

Because Java programs are compiled into bytecode, which can run on any system that has a JVM.

---

# Chapter Summary

In this chapter, you learned:

* What a programming language is.
* The concept of algorithms.
* The meaning of syntax.
* The history of Java.
* Java ownership.
* The WORA principle.
* JVM and bytecode.
* Java program execution flow.
* Why Java is platform independent.

These concepts form the foundation for learning Java programming and understanding how Java programs are compiled and executed.
