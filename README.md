# Stack Implementation in C++

This is my **first Stack experiment** in C++.  
I created this project to understand the basic concepts and operations of a **Stack data structure** using a class and array.

## 📌 About the Project

A **Stack** is a linear data structure that follows the **LIFO (Last In, First Out)** principle.

This means the element that is inserted last will be removed first.

### Example

```text
Push: 10 → 20 → 30

Stack:
30 ← Top
20
10

Pop → 30
```

## 🚀 Features

This program implements the following Stack operations:

- **Push** – Adds an element to the stack
- **Pop** – Removes the top element
- **Peek** – Displays the top element without removing it
- **Traverse** – Displays all elements from top to bottom
- **Search** – Searches for an element in the stack
- **isFull()** – Checks whether the stack is full
- **isEmpty()** – Checks whether the stack is empty

## 🛠️ Technologies Used

- **Language:** C++
- **Concepts:** Data Structures, Stack, Classes, Arrays
- **Compiler:** Any standard C++ compiler

## 📂 Project Structure

```text
Stack-Implementation/
│
├── stack.cpp
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### 2. Open the project

Open the project folder in **VS Code** or any C++ IDE.

### 3. Compile the program

```bash
g++ stack.cpp -o stack
```

### 4. Run the program

Windows:

```bash
stack.exe
```

Linux/macOS:

```bash
./stack
```

## 📋 Menu

The program provides the following menu:

```text
--- Stack Menu ---
1. Push
2. Pop
3. Peek
4. Traverse
5. Search
0. Exit
```

## 🧠 What I Learned

Through this experiment, I learned:

- How a Stack works
- The **LIFO** principle
- Stack overflow and underflow
- Implementing a Stack using an array
- Using classes in C++
- Implementing functions for different Stack operations
- Basic searching and traversal in a Stack

## ⚠️ Important Note

The stack size in this implementation is limited to **100 elements** using:

```cpp
#define MAX 100
```

If more than 100 elements are pushed, the program displays **Stack Overflow**.

Trying to pop from an empty stack results in **Stack Underflow**.

## 📈 Future Improvements

I plan to improve this implementation by:

- Implementing Stack using a linked list
- Adding dynamic memory allocation
- Improving the menu interface
- Adding more error handling
- Studying the time complexity of each operation

## 👨‍💻 Author

**Asish Tirlingi**

This is my **first Stack implementation experiment in C++**, created as part of my journey in learning **Data Structures and Algorithms (DSA)**.

---

⭐ If you find this project useful, feel free to explore the repository and follow my learning journey!
