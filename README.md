# Workflow Engine

This Java program simulates a workflow engine using a directed graph, where each node represents a task that can only execute after all its parent tasks are completed. Nodes with multiple children are processed in parallel using Java multithreading.

## ✅ Features
- Executes a workflow based on a tree-like directed graph.
- Ensures tasks run only after their dependencies are complete.
- Supports parallel execution of child tasks using multithreading.
- Outputs execution order and total number of tasks.

## 🚀 How to Run

1. Compile the code:
   javac WorkflowEngines.java
   java WorkflowEngines

## Enter the input as follows:
![image](https://github.com/user-attachments/assets/a63a2f53-bbc2-46c6-b468-26a504b08172)

##  Sample Output
![image](https://github.com/user-attachments/assets/729c4b97-943d-421a-8716-6c6128b23e3d)

## Input Format
1.First line: Number of nodes (N)

2.Next N lines: Format id:NodeName

3.Next line: Number of edges (M)

4.Next M lines: Format sourceId:destinationId

## 🛠️ Tools Used
1.Java 8 or above

2.ExecutorService and multithreading


