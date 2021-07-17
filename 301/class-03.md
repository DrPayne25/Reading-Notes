# **301 Class #**

## **Section Selector**:
  - [**Things I want to know more About**](#things-i-want-to-know-more-about)
  - [**Lists and Keys**](#lists-and-keys)
  - [**The Spread Operator**](#the-spread-operator)
  - [**Table of Contents**](#code-301-reading-notes)

---

## **Things I want to know more about**


---

## **Lists and Keys**
- What does .map() return? It will create a new array populated with the results of calling a provided function on every element in the calling array
- If I want to loop through an array and display each value in JSX, how do I do that in React? You would use .map on the array for the value and then use curly braces to display that
- Each list item needs a unique key.
- What is the purpose of a key? Keys help React identify which items have changed, are added, or are removed.

## **Food for Thought**
- Need to get better with terms I understand what JSX is but question 2 really got me 



---

## **The Spread Operator**
- What is the spread operator? The spread syntax “spreads” the array into separate arguments.
- List 4 things that the spread operator can do.
  + Copying an array
  + Concatenating or combining arrays
  + Using an array as arguments
  + Adding an item to a list
- Give an example of using the spread operator to combine two arrays.
  - const Arr1 = ['1','2','3']
  - const Arr2 = ['4','5','6']
  - const Arr3 = [...Arr1,...Arr2]
  - console.log(...Arr3)
- Give an example of using the spread operator to add a new item to an array.
  - const Arr4 = [...Arr3,'7']
  - console.log(...Arr4)
- Give an example of using the spread operator to combine two objects into one.
  - const object1 = {name: "Alex"}
  - const object2 = {eyecolor: "Brown"}
  - let object3 = {...object1, ...object2}
  - console.log(object3);


## **Food for Thought**
- adding State please go over a bit more
- 

---

## **How to Pass Functions Between Components**
- In the video, what is the first step that the developer does to pass functions between components? They start by creating an increment function 
- In your own words, what does the increment function do? The increment function loops through people array and then looks at the name and if that matches the name it will then increase the count within that object by one
- How can you pass a method from a parent component into a child component? You can do this by using props to pass the function down to the child component
- How does the child component invoke a method that was passed to it from a parent component?- by using this.props 


## **Food for Thought**


---

## [**Code 301 Reading Notes**](/301/301homepage.md)
  1. [Class 01](/301/class-01.md)
  2. [Class 02](/301/class-02.md)
  3. [Class 03](/301/class-03.md)
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

