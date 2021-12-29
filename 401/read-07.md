# **4011 Class #06**

## **Section Selector**:
  - [**Things I want to know more About**](#things-i-want-to-know-more-about)
  - [**How to use Random Module**](#how-to-use-random-module)
  - [**Table of Contents**](#code-401-reading-notes)

---

## **Things I want to know more about**
- 


---

## **Python Scope**
- When you start a python program you're in the global python scope
- its turnes your main script into a module called __main__
- To inspect the names within your main global scope, you can use dir()
- When you call dir() with no arguments, you get the list of names available in your main global Python scope
- There’s only one global Python scope per program execution
- This scope remains in existence until the program terminates and all its names are forgotten
- You can access or reference the value of any global name from any place in your code
- Whenever you assign a value to a name in Python, one of two things can happen:
  - You create a new name
  - You update an existing name
- Python assumes that names assigned in the body of a function are local to that function
- Global names can be updated or modified from any place in your global Python scope
- Modifying global names is generally considered bad programming practice Ex:
  - Difficult to debug: Almost any statement in the program can change the value of a global name
  - Hard to understand: You need to be aware of all the statements that access and modify global names
  - Impossible to reuse: The code is dependent on global names that are specific to a concrete program
- Good programming practice recommends using local names rather than global names Ex:
  - Write self-contained functions that rely on local names rather than global ones
  - Try to use unique objects names, no matter what scope you’re in
  - Avoid global name modifications throughout your programs
  - Avoid cross-module name modifications
  - Use global names as constants that don’t change during your program’s execution
- LEGB stands for Local, Enclosing, Global, and Built-in
- Python provides two keywords that allow you to modify the content of global and nonlocal names
  - global
  - nonlocal
- with a global statement you can define a list of names that are going to be treated as global names
- The statement consists of the global keyword followed by one or more names separated by commas
- The use of global is considered bad practice in general
- You can also use a global statement to create lazy global names by declaring them inside a function
- Even though you can use a global statement to create lazy global names, this can be a dangerous practice that can lead to buggy code
- You can use global from inside any function or nested function and the names listed will always be mapped to names in the global Python scope
- With a nonlocal statement, you can define a list of names that are going to be treated as nonlocal
- Unlike global, you can’t use nonlocal outside of a nested or enclosed function
- You can’t use a nonlocal statement in either the global scope or in a local scope
- You can’t use nonlocal to create lazy nonlocal names
- Names must already exist in the enclosing Python scope if you want to use them as nonlocal names
- 

---
## [**Code 401 Reading Notes**](/401/401homepage.md)
  1. [Read 01]
  2. [Read 02](/401/read-02.md)
  3. [Read 03](/401/read-03.md)
  4. [Read 04](/401/read-04.md)
  5. Day 04
  6. Day 05
  7. [Read 06](/401/read-06.md)
  8. Day 07
  9. Day 08
  10. Day 09
  11. Day 10
  12. Day 11
  13. Day 12
  14. Day 13
  15. Day 14
<!-- DrP E-Sign Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start -->
