# 🐍 LeetCode Python Practice

Welcome to my **LeetCode Python Practice Repository** 🚀

This repository contains my Python programming practice and LeetCode problem solutions. I am building my coding skills step by step, starting with Python fundamentals and gradually moving toward **Data Structures and Algorithms (DSA)**.

---

## 🎯 Purpose

The purpose of this repository is to:

* Learn Python programming from the basics.
* Improve problem-solving skills.
* Practice coding regularly.
* Solve LeetCode problems using Python.
* Learn Data Structures and Algorithms.
* Understand different problem-solving approaches.
* Improve logical thinking.
* Learn time and space complexity.
* Prepare for coding interviews.

---

# 📚 Topics

This repository will contain practice programs from beginner to advanced levels.

### 🟢 Python Fundamentals

* Print statements
* Variables
* Data Types
* Input and Output
* Operators
* Type Conversion
* Conditional Statements
* `if`, `elif`, `else`
* `for` loops
* `while` loops

### 🟡 Python Intermediate

* Functions
* Strings
* Lists
* Tuples
* Sets
* Dictionaries
* List Comprehension
* Lambda Functions
* Exception Handling
* File Handling
* Modules

### 🔵 Data Structures & Algorithms

* Arrays
* Strings
* Hashing
* Two Pointers
* Sliding Window
* Stack
* Queue
* Linked List
* Binary Search
* Sorting
* Trees
* Graphs
* Recursion
* Backtracking
* Greedy Algorithms
* Dynamic Programming

---

# 🧩 LeetCode Problems

I will add LeetCode problems and solutions as I continue learning.

Some examples include:

| Problem                         | Topic            |
| ------------------------------- | ---------------- |
| Two Sum                         | Array / Hashing  |
| Palindrome Number               | Math / String    |
| Fizz Buzz                       | Loops            |
| Best Time to Buy and Sell Stock | Array            |
| Contains Duplicate              | Hashing          |
| Valid Anagram                   | String / Hashing |
| Binary Search                   | Searching        |
| Valid Parentheses               | Stack            |
| Reverse Linked List             | Linked List      |

---

# 💻 Example: Two Sum

### Problem

Given an array of integers and a target value, find two numbers whose sum equals the target.

### Python Solution

```python
class Solution:
    def twoSum(self, nums, target):
        for i in range(len(nums)):
            for j in range(i + 1, len(nums)):
                if nums[i] + nums[j] == target:
                    return [i, j]


solution = Solution()

nums = [2, 7, 11, 15]
target = 9

print(solution.twoSum(nums, target))
```

### Output

```text
[0, 1]
```

---

# 🚀 How to Create This Project

## Step 1: Install Python

Check Python:

```bash
python --version
```

Example:

```text
Python 3.x.x
```

---

## Step 2: Create a Project Folder

Create a folder such as:

```text
leetcode-practice-1
```

Open the folder in **VS Code**.

---

## Step 3: Create Python Files

Example:

```text
leetcode-practice-1/
│
├── README.md
├── 01_hello_world.py
├── 02_variables.py
├── 03_data_types.py
├── 04_if_else.py
├── 05_loops.py
├── 06_functions.py
├── 07_strings.py
├── 08_lists.py
└── ...
```

---

# ▶️ How to Run

Open the VS Code terminal and run:

```bash
python filename.py
```

For example:

```bash
python 01_hello_world.py
```

You can also use the **Run Python File** button in VS Code.

---

# 🧠 Problem-Solving Process

For each problem, I follow these steps:

1. Read the problem carefully.
2. Understand the input.
3. Understand the expected output.
4. Identify the required logic.
5. Write the Python solution.
6. Test the program.
7. Check edge cases.
8. Analyze time complexity.
9. Analyze space complexity.
10. Save the solution to GitHub.

---

# 📁 Suggested Project Structure

As the repository grows, problems can be organized like this:

```text
leetcode-practice-1/
│
├── README.md
│
├── 01_python_basics/
├── 02_variables/
├── 03_conditions/
├── 04_loops/
├── 05_functions/
├── 06_strings/
├── 07_arrays/
├── 08_hashing/
├── 09_two_pointers/
├── 10_sliding_window/
├── 11_stack/
├── 12_queue/
├── 13_linked_list/
├── 14_binary_search/
├── 15_sorting/
├── 16_trees/
├── 17_graphs/
├── 18_recursion/
├── 19_backtracking/
├── 20_greedy/
└── 21_dynamic_programming/
```

---

# 📈 Learning Path

My learning path is:

```text
Python Basics
      ↓
Variables & Data Types
      ↓
Conditions
      ↓
Loops
      ↓
Functions
      ↓
Strings
      ↓
Lists & Arrays
      ↓
Dictionaries
      ↓
Hashing
      ↓
Two Pointers
      ↓
Sliding Window
      ↓
Stack & Queue
      ↓
Linked List
      ↓
Binary Search
      ↓
Trees
      ↓
Graphs
      ↓
Recursion
      ↓
Backtracking
      ↓
Greedy
      ↓
Dynamic Programming
      ↓
Advanced LeetCode
```

---

# 📊 Progress

* [x] Python Basics
* [x] Variables
* [x] Data Types
* [ ] Input and Output
* [ ] Conditions
* [ ] Loops
* [ ] Functions
* [ ] Strings
* [ ] Lists
* [ ] Dictionaries
* [ ] Hashing
* [ ] Two Pointers
* [ ] Sliding Window
* [ ] Stack
* [ ] Queue
* [ ] Linked List
* [ ] Binary Search
* [ ] Sorting
* [ ] Trees
* [ ] Graphs
* [ ] Recursion
* [ ] Backtracking
* [ ] Greedy
* [ ] Dynamic Programming

---

# 🛠️ Technologies Used

* Python 3
* Visual Studio Code
* Git
* GitHub
* LeetCode

---

# 🔧 GitHub Workflow

After adding new Python programs:

```bash
git add .
```

Commit the changes:

```bash
git commit -m "Add more LeetCode practice"
```

Push to GitHub:

```bash
git push
```

---

# 🌱 What I Am Learning

Through this repository, I am improving:

* Python programming
* Problem solving
* Logical thinking
* Data Structures
* Algorithms
* Debugging
* Time complexity
* Space complexity
* Git and GitHub
* LeetCode problem solving

---

# 🎓 Learning Journey

This repository represents my journey from **beginner Python programming to advanced DSA and LeetCode problem solving**.

I will continue adding new programs and solutions as I learn new concepts.

The goal is simple:

```text
Learn → Practice → Solve → Understand → Improve 🚀
```

---

# 👩‍💻 Author

**Aishwarya**

Python & LeetCode Practice

---

## ⭐ Keep Coding!

> Consistent practice is the key to improving programming and problem-solving skills. 🐍💻🚀
