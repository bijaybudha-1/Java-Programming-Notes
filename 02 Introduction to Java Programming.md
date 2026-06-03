# Basics Java

## 2.1 What is Java?

Java is a programming language and a platform used to develop applications. It is:

* High level  
* Object Oriented  
* Secure & Robust  

---

# Application

1. Desktop Application such as: acrobat reader, media player, antivirus etc.  
2. Web application  
3. Mobile application  
4. Enterprise systems  
5. Games & embedded systems  

---

## 2.2 Features of Java

#### 1. Simple  
* Easy to learn & use  
* Syntax is similar C++  
* Removes complex feature like pointers.  

#### 2. Object - oriented  
* Everything is based on objects.  
* Support OOP concepts like:  
  -> Class , Object  
  -> Inheritance  
  -> Polymorphism  

#### 3. Platform Independent  
* Java follows Write once Run anywhere / WORA  
* Code run on the any system using JVM.  

#### 4. Secure  
* No use of explicit pointers.  
* Runs inside JVM sandbox  
* Helps develop virus - free system.  

#### 5. Robust  
* It uses strong memory management.  
* There is a lack of pointer that avoids security problems.  
* Java provides automatic garbage collection which runs on the Java Virtual Machine.  

#### 6. Portable  
* Java bytecode can run on any platform.  
* No need for system - specific implementation  

#### 7. Architecture Neutral  
* Fixed size of datatypes  
* Same behavior on all machine.  

#### 8. High Performance  
* Faster than traditional interpreted language  
* Uses bytecode close to machine code.  

#### 9. Multithreaded  
* Can perform multi tasks as the same time  
* Improves performance  

---

## 2.3 Difference between JVM, JRE & JDK

### 1. JVM (Java Virtual Machine):
* It is an abstract machine (doesnot physically exist)  
* Provides runtime environment to execute Java bytecode  
* Converts bytecode -> Machine code  
* Makes Java platform independent.  

`In short :* Runs Java program ` 

---

### 2. JRE (Java Runtime Environment)
* JRE = JVM + Libraries + supporting files  
* Provides environment to run Java programs  
* Does not contain development tools  

`In short : Helps run Java program  `

---

### 3. JDK (Java Development Kit)
* JDK = JRE + Development tools (compiler etc.)  
* Used to develop & run Java programs  
* Contain tools like:  
  • javac (compiler)  
  • debugger  

`In short : Used to develop Java programs `

---

## 2.4 Importance of the Main Method in Java

* The main method is the entry point of every Java program.  
* Execution of the program starts from the main method.  

# Why Main method is important

- JVM start execution from the main method  
- Without main method, the program will not run.  
- It tells JVM where to begin execution.  
```java
public static void main (string[] args)
```
* `public:` JVM can access it.  
* `static:` no need to create object  
* `void:` does not return any value  
* `String[] args:` used to pass command line arguments.  