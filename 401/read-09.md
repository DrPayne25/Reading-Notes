# **4011 Class #06**

## **Section Selector**:
  - [**Things I want to know more About**](#things-i-want-to-know-more-about)
  - [**Dunder Methods**](#dunder-methods)
  - [**Statistics - Probability**](#statistics---probability)
  - [**Table of Contents**](#code-401-reading-notes)

---

## **Things I want to know more about**
- 


---

## **Dunder Methods**
- special methods are a set of predefined methods you can use to enrich your classes. They are easy to recognize because they start and end with double underscores
- “dunder methods”, a short form of “double under"
- Dunder methods let you emulate the behavior of built-in types.
- This elegant design is known as the Python data model and lets developers tap into rich language features like sequences, iteration, operator overloading, attribute access, etc
- Look at Python’s data model as a powerful API you can interface with by implementing one or more dunder methods
- Object Initialization: __init__
  - To construct account objects from the a class I need a constructor which in Python is the __init__ dunder
  - The constructor takes care of setting up the object
- Object Representation: __str__, __repr__
  - __repr__: The “official” string representation of an object. This is how you would make an object of the class. The goal of __repr__ is to be unambiguous
  - __str__: The “informal” or nicely printable string representation of an object. This is for the enduser
- You can make an object callable like a regular function by adding the __call__ dunder method
- context manager is a simple “protocol” (or interface) that your object needs to follow so it can be used with the with statement. Basically all you need to do is add __enter__ and __exit__ methods to an object if you want it to function as a context manager


## **Statistics - Probability**
  
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
  10. [Read 09](/401/read-09.md)
  11. Day 10
  12. Day 11
  13. [Read 12]()
  14. Day 13
  15. Day 14
<!-- DrP E-Sign Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start -->
