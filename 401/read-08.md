# **4011 Class #06**

## **Section Selector**:
  - [**Things I want to know more About**](#things-i-want-to-know-more-about)
  - [**List Comprehensions**](#list-comprehensions)
  - [**Table of Contents**](#code-401-reading-notes)

---

## **Things I want to know more about**
- 


---

## **List Comprehensions**
- List comprehension is a powerful and concise method for creating lists in Python that becomes essential the more you work with lists, and lists of lists
- 3 items needed for list comprehension ex: my_new_list = [ expression for item in list ]
  - First is the expression we’d like to carry out. expression inside the square brackets
  - Second is the object that the expression will work on. item inside the square brackets
  - Third, we need an iterable list of objects to build our new list from. list inside the square brackets
- List comprehension is when your're going to perform an expression on each item in the list the expression will determine what item is eventually stored in the output list
- you can perform list compreshion on  a single line of code or you can add conditional statements in the form of filters which allows more precision in the way lists are handled
- List comprehension methods are an elegant way to create and manage lists 
- In Python, list comprehensions are a more compact way of creating lists 
- More flexible than for loops, list comprehension is usually faster than other methods
- Before List comprehensions:
  squares = []
  for x in range(10):
    squares.append(x**2)
  print(squares)
  output: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
- With List Comprehensions:
  squares = [x**2 for x in range(10)]
  print(squares)
  output: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
- Multipy by 3 with list comprehension:
  multiples_of_three = [ x*3 for x in range(10) ]
- List Comprehensions with filter for even numbers: 
  even_numbers = [ x for x in range(1,20) if x % 2 == 0]
- List Comprehensions to find the first letter in a list:
  letters = [ name[0] for name in authors ]
- List Comprehensions to separate the letters in a string:
  letters = [ letter for letter in "20,000 Leagues Under The Sea"]
- List Comprehensions with a built in method:
  lower_case = [ letter.lower() for letter in ['A','B','C'] ]
  upper_case = [ letter.upper() for letter in ['a','b','c'] ]
- List Comprehensions to read each line in a file:
  poem = [ line for line in file ]
- list comprehension with user function followed by filter
  No Filter:
  def double(x):
    return x*2
  nums = [double(x) for x in range(1,10)]
  Output: [2, 4, 6, 8, 10, 12, 14, 16, 18]

  With Filter:
  even_nums = [double(x) for x in range(1,10) if x%2 == 0]
  Output: [4, 8, 12, 16]
- List Comprehension with additional arguments:
  nums = [x+y for x in [1,2,3] for y in [10,20,30]]
  Output: [11, 21, 31, 12, 22, 32, 13, 23, 33]
  
---
## [**Code 401 Reading Notes**](/401/401homepage.md)
  1. [Read 01]
  2. [Read 02](/401/read-02.md)
  3. [Read 03](/401/read-03.md)
  4. [Read 04](/401/read-04.md)
  5. Day 04
  6. Day 05
  7. [Read 06](/401/read-06.md)
  8. [Read 07](/401/read-07.md)
  9. [Read 08](/401/read-08.md)
  10. Day 09
  11. Day 10
  12. Day 11
  13. Day 12
  14. Day 13
  15. Day 14
<!-- DrP E-Sign Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start -->
