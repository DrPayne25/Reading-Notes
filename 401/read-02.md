# **301 Class #02**

## **Section Selector**:
  - [**Things I want to know more About**](#things-i-want-to-know-more-about)
  - [**In Test We Trust - TDD with Python**](#in-tests-we-trust---tdd-with-python)
  - [**If Name Equals Main**](#if-name-equals-main)
  - [**Recursion**](#recursion)
  - [**Table of Contents**](#code-301-reading-notes)

---

## **Things I want to know more about**
- Poetry install will install all dependencies in your pyproject.toml
- dunder = __
- function in python require something inside aka can't be empty 
- import is getting it from the environment 
- pip3 install avoid using pip3 to install
- poetry add can be done in the same way to do it in the virtual environment 
- Things should be installed in the local environment 
- write tests first so that you know the parameters that you are working with 
- Test Driven Development might be a nice key for interviews 
- Test required for the function 
- poetry add pytest-watch ptw will start it 
- 


---

## **In Tests We Trust - TDD with Python**
- Unit tests are pieces of code used to test your input and output.
- TDD: Test Driven Development is to think and write tests first before your code 
- Its okay for the start of a the project to be hard its okay 
- Test name should be descriptive and say what is expected 
- The file name should follow the same name as the module you create. ex: example.py expected: test_example.py
- AAA 
  - Arrange: organize the data you need to execute the code also know as input
  - Act: execute the code being test 
  - Assert: Once executed check that the output matches what your expected input
- pytest is what this article recommends testing with
- Cycle:
  - Write a test to fail because the feature isn't there 
  - Write the feature and make the above test pass
  - Refactor as needed 
- TDD isn't about money/tests its about software design first
- Makes code more reliable due to the tests your craft 
- Just need to practice 
## **Food for Thought**
- Still a bit confused on the functions part of some of the tests but I think that will come as we continue to learn more over the coming weeks. 

---

## **If Name Equals Main**
- in python before executing code the interpeter reads the source file to define a few special variables/global variables
- If its the main program being read it sets the __name__ variable to the value of __main__
- If its not main it will set the __name__ will be set to the module's name. 
- A module is a file containing Python definitions and statements the file name is the module name with suffix .py 
- Every python module has its __name__ defined if its __main__ it implies that the module is being run standalone 
- If you import a module in another script the __name__ is set to the name of the script/module
- if __name__ == main it will only execute if its being run directly and not imported 


## **Food for Thought**
This made the if __name__ == "__main__": makes way more sense than it did yesterday 


---

## **Recursion**
- Recursion: the process in which a function calls itself directly or indirectly the corresponding function is called as recursive function 
- Base Condition: the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems
- Break down a problem into one or more smaller problems and add base conditions that stop the recursion 
- Direct recursive happens when a functions calls the same function
- indirect recursive if it calls another function within 
- When the recursive call is the last thing executed by the function 
- 


## **Food for Thought**
Function fun don't get it? 


---

## [**Code 401 Reading Notes**](/401/401homepage.md)
  1. [Read 01]
  2. [Read 02](/401/read-02.md)
  3. Day 02
  4. Day 03
  5. Day 04
  6. Day 05
  7. Day 06
  8. Day 07
  9. Day 08
  10. Day 09
  11. Day 10
  12. Day 11
  13. Day 12
  14. Day 13
  15. Day 14
<!-- DrP E-Sign Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start -->
