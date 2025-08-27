
# Python List Operations Project

Welcome to the **python-wk2-** project! This repository is designed to help you understand and practice fundamental list operations in Python. Lists are one of the most versatile and widely used data structures in Python, and mastering them is essential for any Python programmer.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. [List Operations Explained](#list-operations-explained)
5. [Code Walkthrough](#code-walkthrough)
6. [How to Run](#how-to-run)
7. [Expected Output](#expected-output)
8. [Further Reading](#further-reading)
9. [Contributing](#contributing)
10. [License](#license)

---

## Project Overview

This project contains a single Python file, `list.py`, which demonstrates a sequence of common list operations. These operations include creating a list, adding and removing elements, sorting, and searching for values. The project is ideal for beginners who want to learn how to manipulate lists in Python.

## Features

- Create an empty list
- Append multiple elements
- Insert an element at a specific position
- Extend the list with another list
- Remove the last element
- Sort the list in ascending order
- Find and print the index of a specific value

## Getting Started

To get started with this project, you need to have Python installed on your system. You can download Python from the official website: [python.org](https://www.python.org/downloads/).

### Clone the Repository

```powershell
git clone <repository-url>
cd python-wk2-
```

### File Structure

```
python-wk2-/
│
├── list.py
└── README.md
```

## List Operations Explained

Below are the operations performed in `list.py` with explanations:

1. **Create an Empty List**
	- `my_list = []`
	- Initializes an empty list.

2. **Append Elements**
	- `my_list.append(10)`
	- Adds elements to the end of the list.

3. **Insert at a Specific Position**
	- `my_list.insert(1, 15)`
	- Inserts the value 15 at index 1 (second position).

4. **Extend with Another List**
	- `my_list.extend([50, 60, 70])`
	- Adds multiple elements from another list to the end.

5. **Remove the Last Element**
	- `my_list.pop()`
	- Removes the last element from the list.

6. **Sort the List**
	- `my_list.sort()`
	- Sorts the list in ascending order.

7. **Find and Print the Index of a Value**
	- `index_30 = my_list.index(30)`
	- Finds the index of the value 30 and prints it.

## Code Walkthrough

Here is the code in `list.py` with comments:

```python
# Create an empty list
my_list = []

# Append elements
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend with another list
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort in ascending order
my_list.sort()

# Find and print the index of 30
index_30 = my_list.index(30)
print("Index of 30:", index_30)
```

## How to Run

To run the code, open a terminal in the project directory and execute:

```powershell
python list.py
```

## Expected Output

When you run the script, you should see:

```
Index of 30: 3
```

## Further Reading

- [Python Lists Documentation](https://docs.python.org/3/tutorial/datastructures.html#more-on-lists)
- [Python Official Website](https://www.python.org/)
- [W3Schools Python Lists](https://www.w3schools.com/python/python_lists.asp)

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add more list operations, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author 

Charles Omondi
