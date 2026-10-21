# Palindrome Checker Using Stack and Queue

## 1. Introduction
This mini-project implements a Palindrome Checker application in Python using **Stack** and **Queue** data structures. A palindrome is a word, phrase, number, or other sequence of characters that reads the same forward and backward. This application demonstrates the contrasting properties of **LIFO (Last In, First Out)** and **FIFO (First In, First Out)** behavior to validate string symmetry.

## 2. Objectives
* Understand and implement fundamental linear data structures (Stacks and Queues).
* Explore the contrasting traversal behaviors of LIFO and FIFO.
* Clean and process raw text inputs by handling alphanumeric extraction and case normalization.
* Present the complete solution interactively using a Jupyter Notebook.

## 3. Description
When validating a palindrome using this approach:
1. The input string is filtered to remove spaces and special symbols, and characters are normalized.
2. The processed characters are simultaneously pushed into a **Stack** and enqueued into a **Queue**.
3. Elements are popped from the stack (retrieving them in reverse LIFO order) and dequeued from the queue (retrieving them in original FIFO order) simultaneously.
4. If all corresponding character pairs match, the string is confirmed as a palindrome.

## 4. Technologies Used
* **Programming Language:** Python 3
* **Environment:** Jupyter Notebook (`.ipynb`)
* **Core Logic:** Built-in Python lists and control structures (avoiding complex external dependencies for clear academic demonstration).

## 5. Features
* Case-insensitive validation of strings and phrases.
* Automatic exclusion of spaces and punctuation.
* Interactive cell-by-cell execution via Jupyter Notebook.
* Detailed test cases covering valid palindromes and non-palindromes.

## 6. Stack and Queue Operations Used
* `stack.append(char)` / `queue.append(char)`: Inserts characters into the respective data structures.
* `stack.pop()`: Retrieves items in reverse order (LIFO behavior).
* `queue.pop(0)`: Retrieves items in original order (FIFO behavior).

## 7. How to Run the Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/YashKhakal0017/DS-Mini-Project-1.git](https://github.com/YashKhakal0017/DS-Mini-Project-1.git)
