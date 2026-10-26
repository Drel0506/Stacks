# Week 12 — Stacks and Queues

A C# Windows Forms application for the **Data Structures and Algorithms** laboratory. This project demonstrates stack and queue operations using arrays, postfix expression evaluation, and decimal-to-binary conversion.

## 📚 Overview

**Topic:** Stacks  
**Language:** C#  
**Framework:** Windows Forms

## 🎯 Learning Objectives

- Understand the LIFO (Last In, First Out) and FIFO (First In, First Out) principles.
- Implement stack operations using arrays.
- Implement queue operations using arrays.
- Apply stacks to postfix expression evaluation.
- Convert decimal numbers to binary using a stack.
- Test data structures and handle common errors.

## 🧱 Features

### 1. Stack Operations

Implements a stack from scratch using an array.

| Operation | Description |
|---|---|
| `Push` | Adds an element to the top of the stack. |
| `Pop` | Removes and returns the top element. |
| `Peek` | Returns the top element without removing it. |
| `IsEmpty` | Checks whether the stack is empty. |
| `IsFull` | Checks whether the stack has reached its capacity. |
| `Display` | Displays the stack elements from top to bottom. |

**Principle:** LIFO — the last element inserted is the first element removed.

### 2. Queue Operations

Implements a queue using an array, with FIFO behavior.

| Operation | Description |
|---|---|
| `Enqueue` | Adds an element to the rear of the queue. |
| `Dequeue` | Removes and returns the front element. |
| `Peek` | Returns the front element without removing it. |
| `IsEmpty` | Checks whether the queue is empty. |
| `IsFull` | Checks whether the queue has reached its capacity. |
| `Display` | Displays elements from front to rear. |

**Principle:** FIFO — the first element inserted is the first element removed.

### 3. Postfix Expression Evaluation

Evaluates mathematical expressions written in postfix notation using a stack.

Supported operators:

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)

Example:

```text
Expression: 23+
Result: 5
```

The application processes operands and operators using a stack and handles invalid expressions and division by zero.

### 4. Decimal-to-Binary Conversion

Converts a non-negative decimal integer into binary using a stack.

Example:

```text
Decimal: 13
Binary:  1101
```

The conversion repeatedly divides the number by two, pushes the remainders onto a stack, and pops them to produce the binary representation.

### 5. Interactive Menu

The application provides menu-based navigation for accessing the available features.

- Stack operations
- Queue operations
- Postfix expression evaluation
- Decimal-to-binary conversion
- Exit

The application continues running until the user chooses to exit.

### 6. Operation Log and Visualization

- Displays operation results and timestamps.
- Provides visual representations of stack and queue elements.
- Identifies the top of the stack and the front and rear of the queue.
- Reports invalid operations and full or empty data structures.

## 🛠️ Technologies Used

- **C#** — application logic and data structures
- **Windows Forms** — graphical user interface
- **Arrays** — underlying storage for stacks and queues
- **.NET** — application runtime and framework

## ▶️ Getting Started

### Prerequisites

- Windows
- Visual Studio with the .NET desktop development workload, or a compatible .NET SDK
- The .NET target framework required by the project

### Running the Application

1. Clone or download this repository.
2. Open the project in Visual Studio or VS Code.
3. Restore the project dependencies if necessary.
4. Build the project.
5. Run the Windows Forms application.
6. Enter the desired array capacity when prompted.
7. Select an operation from the menu.

If the project uses an SDK-style Windows Forms configuration, you can run it from the terminal with:

```powershell
dotnet run --project .\WindowsFormsApp3.Modern.csproj
```

Adjust the project filename if yours differs.

## 🧪 Sample Operations

### Stack

```text
Push(10)
Push(20)
Push(30)
Peek()    -> 30
Pop()     -> 30
Display() -> 20, 10
```

### Queue

```text
Enqueue(10)
Enqueue(20)
Enqueue(30)
Peek()     -> 10
Dequeue()  -> 10
Display()  -> 20, 30
```

## 📖 Academic Information

**Course:** Data Structures and Algorithms  
**Laboratory Activity:** Week 12 — Stacks  
**Duration:** 3 Hours  
**Instructor:** Prof. Lester G. Diampoc  
**Institution:** University of Makati

## 👨‍💻 Author

Developed as part of the Week 12 Data Structures and Algorithms laboratory exercises.

---

*This project is intended for educational purposes and demonstrates fundamental data structure concepts and their applications.*
