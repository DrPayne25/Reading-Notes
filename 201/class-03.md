# **Class 02 Developer Payne's First Adventure continues**

## **Section Selector**:
  - [**Food For Thought**](#food-for-thought)
  - [**Table of Contents**](#code-201-reading-notes)
  - [**Lists**](#lists)
  - [**Boxes**](#boxes)
  - [**Decisions and Loops**](#decisions-and-loops)

---

## **Food For Thought**
-  Always use 'use strict' at the top of .js
-  An array is made up of elements
-  An element is a thing inside an array each element has an index within that array. 
-  Index starts at 0 and points to the place-in-order where the elements exists inside the array 
-  console.log(myArray[2\]); would be said as console log myArray at 2
-  Arrays have multiple different data types
-  comma after each item in an array 
-  .length can be used to count the items in an array 
-  `` use this for the below way to write instead of ""
-  ${\} This will used to put a js variable inside a string
-  myArray[4\] = 'Alex' would add an item to the myArray array 
-  myArray.push(\) Lets you add an item to an array 
-  ` use the backtick to write 
-  for (let i = 0; i < example.length; i++\) {\} get used to this counter 
-  960 px is  a good estimate for width 

---

## **Lists**
3 Different types of List  
**Ordered list**: List where each item in the list is numbered  
**Unordered List**: Lists that with a character rather than a number  
**Definition Lists**: Made up of a set of terms along with the definitions for each of those terms  
Ordered Lists are created with the <ol\> and each item is placed in and <li\> and</li\>  
Unordered Lists are created with the <ul\> and each item is placed in and <li\> and</li\>  
Browsers indent lists by default  
Definition Lists are created with the <dl\> inside that you will see pairs of <dl\> and <dt\>  
<dt\> is used to contain the term being defined  
<dd\> is used to contain the definition  
you can put a second list inside an <li\> to create a sub list or nested list    

## **Key Takeaways**
- There are three types of HTML lists: ordered, unordered, and definition.
- Ordered lists use numbers.
- Unordered lists use bullets.
- Definition lists are used to define terminology. 
- Lists can be nested inside one another.

---

## **Boxes**
- The most popular ways to specify the size of a box are to use pixels, percentages, or ems  
- Pixels have been the most popular method due to how accurately you can control the size  
- Percentages base the size of the box relative to the size of the browser window  
- Ems base the size of th box on the size of the text within in  
- Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide  
- You can use the max-width property to ensure that lines of text do not appear too wide within a big browser window and you can use the min-width property to make sure that they do not appear too narrow one example  
- The same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-height and max-height properties.  
- The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values  
- Hidden: This property simply hides any extra content that does not fit in the box  
- Scroll: This property adds a scrollbar to the box so that users can scroll to see the missing content.  
Every box has three available properties that can be adjusted to control its appearance
  1. Border: Every box has a border (even if it is not visible or is specified to be 0 pixels wide)  
  2. Margin: Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.  
  3. Padding: Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.  

## **Key Takeaways**
- CSS treats each HTML element as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding for each box with CSS.
- It is possible to hide elements using the display and visibility properties.
- Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of boxes containing text and the leading.
- CSS3 has introduced the ability to create image borders and rounded borders.

---

## **Decisions and Loops**
- A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value
- If you use a data type JavaScript did not expect, it tries to make sense of the operation rather than report an error
- Falsy values are treated as if they are fa1se
**Falsy Values**
  1. var example = False: Boolean False
  2. var example = 0: The Number zero
  3. var example = ' ': Empty Value
  4. var example = 10/'score': NaN(Not a Number\)
  5. var example; a variable with no value assigned 
- Truthy values are treated as if they are true. Almost everything that is not one of the above Falsy values can be treated as true
**Truthy Values**
  1. var example = True: Boolean True
  2. var example = 1: number other than zero
  3. var example = 'carrot': Strings with content
  4. var example = 10/5; Number Calculations
  5. var example = 'true': true written as a string
  6. var example = '0': zero written as a string
  7. var example = 'false': false written as a string


## **Key Takeaways**
- Conditional statements allow your code to make decisions about what to do next.
- Comparison operators (===, !==, ==, !=, <, >, <=, =>) are used to compare two operands.
- Logical operators allow you to combine more than one set of comparison operators.
- if ... else statements allow you to run one set of code if a condition is true, and another if it is false.
- switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).
- Data types can be coerced from one type to another. All values evaluate to either truthy or falsy.
- There are three types of loop: for, while, and do . . . while. Each repeats a set of statements.

---

## [**Code 201 Reading Notes**](/201/201homepage.md)
  1. [Class 00](../class-01.md)
  2. [Class 01](../class-02.md)
  3. [Class 02](../class-03.md)
  4. [Class 03](../class-04.md)
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
