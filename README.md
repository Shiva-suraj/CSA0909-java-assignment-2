# CSA0909 — Programming in Java

## Assignment 2: CO2 — Strings and the Java Collection Framework

**Course Code:** CSA0909  
**Assignment:** Assignment 2 — CO2  
**Maximum Marks:** 50

## Overview

This repository contains Java solutions and task-wise documentation for all seven questions in Assignment 2. Each task is organized in a separate folder containing one Java source file and its corresponding README.

The programs cover string handling, Java collection classes, sets, maps, generics, comparators, queues, performance measurement, and validation.

## Assignment Tasks

| Question | Topic | Source |
|---|---|---|
| Q1 | String, StringBuilder and StringBuffer | [Task01/task1.java](Task01/task1.java) |
| Q2 | ArrayList, LinkedList and ArrayDeque | [Task02/task2.java](Task02/task2.java) |
| Q3 | HashSet and the equals/hashCode contract | [Task03/task3.java](Task03/task3.java) |
| Q4 | HashMap, TreeMap and LinkedHashMap | [Task04/task4.java](Task04/task4.java) |
| Q5 | Generics and Comparator-based ranking | [Task05/task5.java](Task05/task5.java) |
| Q6 | Queue, PriorityQueue and emergency triage | [Task06/task6.java](Task06/task6.java) |
| Q7 | Diagnose, redesign and validate | [Task07/task7.java](Task07/task7.java) |

## Repository Structure

```text
CSA0909-java-assignment-2/
├── Task01/
│   ├── task1.java
│   └── README.md
├── Task02/
│   ├── task2.java
│   └── README.md
├── Task03/
│   ├── task3.java
│   └── README.md
├── Task04/
│   ├── task4.java
│   └── README.md
├── Task05/
│   ├── task5.java
│   └── README.md
├── Task06/
│   ├── task6.java
│   └── README.md
├── Task07/
│   ├── task7.java
│   └── README.md
└── README.md
```

Each task folder contains exactly one Java source file and its corresponding README.

## Java Concepts Covered

- Immutable strings and mutable string-building classes
- List and deque implementations: ArrayList, LinkedList and ArrayDeque
- Set operations, object equality and hash codes
- Map implementations and iteration order
- Generic classes and Comparator-based sorting
- FIFO queues and priority queues
- Runtime measurement, algorithmic complexity and validation

## Requirements

- Java Development Kit (JDK) 8 or later
- A terminal or Java-compatible IDE

## Compile and Run

Open a terminal in the required task folder. Compile the Java source file and run the class with the matching name.

For example, to run Q1:

```bash
cd Task01
javac task1.java
java task1
```

Use the matching filename and class name for the other tasks. For Q5, the source is self-contained in the task folder and can be run with:

```bash
cd Task05
javac task5.java
java task5
```

## Source Acknowledgement

The task organization and initial solution material were adapted from the public reference repository [rishi2338/CSA0909-1911260190-ASSIGNMENT2](https://github.com/rishi2338/CSA0909-1911260190-ASSIGNMENT2). Repository-specific documentation and execution instructions have been adjusted for this repository.

---

**CSA0909 — Programming in Java | Assignment 2**
