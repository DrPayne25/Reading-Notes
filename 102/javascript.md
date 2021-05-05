# **Bring me the Script: HTML CSS & Javascript a Match made in Heaven**

## **Food for thought**
+ () is 
+ {} anything inside is called a code block 
+ // is used to mark a note
+ cmd + ? will comment out a section in java
+ .js use console.log to see what the record is works in any sort of 
+ var today = new Date(\) would be said as declaring a variable named today and assigning it to the new Date data
+ To adjust your js file and create a function you can use all your old code add it in curly braces and name it a fucntion before hand function create    
![example](Images/function-b-example.png)  
+ Script tags go at the bottom but inside the body 
+ put return at the end of a function that way you can return that info in the function
+ === equals and equal sign in javascript  
![example2](Images/function-b-example2.png)  
+ cmd + ] is how you all tab

# **How it fits together**
+ **Javascript**: Also spelled JS 
+ Aim to keep HTML CSS and JS in separate files with the HTML files linking to the CSS and JS
+ **Content Layer**: This is going to be where the content lives it gives page structure and adds semantics 
 .HTML files makes up this layer  
+ **Presentation Layer**: .CSS files live here they use CSS to enhance the HTML pages with rules that state how the HTML content is presented (background, border, box dimensions, colors, fonts, etc\)
+ **Behavior Layer** .js files live here this changes how the page behaves, adding interactivity. Keep your JS in a separate file

## **Progressive Enhancement**
+ These three layers form the basis of a popular approach to building web pages called progressive enhancement
+ some people browse with JavaScript turned off, so you need to make sure that the page still works for them
+ Starting with the HTML layer allows you to focus on the most important thing about your site: its content
+ **HTML ONLY**: Being plain HTML, this layer should work on all kinds of devices, be accessible to all users, and load quite quickly on slow connections
+ **HTML+CSS**: Adding the CSS in a separate file keeps the rules for the how the page looks away from the content itself
+ You can have one style sheet per site or multiple that create different views of the same data
+ **HTML+CSS+JavaScript**: JS is the last piece added it enhances the usability of the page or the experience of interacting with the site
+ Keeping it separate means that the page still works if the user cannot load or run the JavaScript. You can also reuse the code on several pages (making the site faster to load and easier to maintain\)

## **Objects, Methods, and Bears......Oh My!!**
+ The below line of code shows how to use objects and methods normally referred to as calling a method of an object  
![calling-example](./Images/Calling-example.png)  
+ Behind the scenes the browser uses a lot more code ot make the words appear not important for what we a doing but good to know
+ You only need to know how to call the object and method and how to tell it the information it needs to do the job it will handle the rest Computer are Cool! 
+ There are lots of objects like the document object above and lots of methods like the wirte(\) method above that can help you write scripts

## **Run Java Run**
+ JS runs where it is found the HTML 
+ When the browser comes across a <script\> element, it stops to load the script and then checks to see if it needs to do anything.  
![script-example](./Images/script-example.png)  
+ In the above example you could move the script and it would change the positions of what it is scripting  

# **Summary**
+ It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension  
+ The HTML <script\> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link\> element can be used to load a CSS file)
+ If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created

# **Captain JavaScript has.....Basic JS Instructions**

## **I have a Statement from Captain JavaScript..**;
+ A script is a series of instructions that your computer follows one by one
+ Each individual instruction is know as a **Statement** 
+ Statements should end with a semicolon ;  
![statements-example](./Images/statement-example.png)
+ Lines 1-3 6,8,,10,12,& 14 are all statements
+ These {\} braces indicate the start and end of a code block. Each code block could contain many more statements 
+ Lines 5,7,9,11 determines which code should be run
+ Javascript is case sensitive hourNow and hournow are different 
+ Statements are instructions and each one starts on a new one and ends with a semicolon ;
+ This formatting makes your code easier to read
+ The semicolon tells the JS interpreter when a step is over and when it should move to the next one 
+ Statements cane be organized into code blocks 
+ statements can be surrounded by curley braces {\} this is a code block 
+ The closing curly brace is not followed by a semicolon ;
+ Code blocks will often be used to group together many more statements
+ This makes your code organized and more readable remember your code should be able to be read by anyone that understand JS HTML and CSS after this 

## **Conqueror of the Supreme Comments**
+ Write comments to explain what your code does. it makes it easier to read and understand and can help you and other who read it down the road
+ Multi-line comments are written by starting the line with /* and ends with */ anything written inside of that is not processed by the JS interpreter
+ Normally they are used for descriptions of how the script works or to prevent a section of the script from running when testing it   
![comments-example](./Images/comments-example.png)  

## **Variable Vinsmoke Appears**
+ A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables
+ When you write JavaScript, you have to tell the interpreter every individual step that you want it to perform. This sometimes involves more detail than you might expect
+ You can compare variables to short-term memory, because once you leave the page, the browser will forget any information it holds
+ A variable is a good name for this concept because the data stored in a variable can change (or vary) each time a script runs
+ variables can be used to represent values in your scripts that are likely to change. The result is said to be **calculated** or **computed** using the data stored in the variables
+ The use of variables to represent numbers or other kinds of data is very similar to the concept of algebra (where letters are used to represent numbers\). The equals sign does something very different in programming 

## **Variable Vinsmoke will you declare them?**
+ Before you can use a variable you need to announce that you want to use it
+ This involves creating the variable then giving it a name normally you say that you declare the variable   
![variable-example](./Images/variable-examples.png)   
+ Var in the above example is what a programmer calls a keyword the JS interpreter knows that this keyword is used to create a variable
+ Before you can use the variable you gotta name it sometimes called an identifier the variable in the above example is called quantity
+ if the variable name is more than one word it is usually written in camelCase
+ CamelCase means the first word is all lowercase and any subsequent words have their first letter capitalized

## **Variable Vinsmoke Assign them a Value**
+ Once a variable is created you can tell it what info you would like it to store. 
+ Normally you would say you assign a value to the variable   
![variable-examples2](./Images/variable-examples2.png)  
+ Huzzah that variable is now usable by name
+ In the above example quantity that we created earlier is now set to 3
+ Variable's names should describe the kind of data that variable hold
+ The equals sign = is an assignment operator it says that you age going to assign a value to the variable 
+ It is also used to update the value given to a variable  
+ Util a value is assigned it is generally called undefined 
+ Where a variable is declared can have an effect upon whether the rest of the script can use it
+ Often this is called the scope of a variable 

## **Dr Data Types Steps on the Scene** 
+ JavaScript distinguishes between numbers, strings, and true or false values known as Booleans
+ **NUMERIC DATA TYPE**: The numeric data type handles numbers **ex: 0.75**
+ **STRING DATA TYPE**: The strings data type consists of letters and other characters **ex: 'Hi, Ivy!'**
+ Note how the string data type is enclosed within a pair of quotes. These can be single or double quotes, but the opening quote must match the closing quote
+ Strings can be used when working with any kind of text. They are frequently used to add new content into a page and they can contain HTML markup
+ **BOOLEAN DATA TYPE**: Boolean data types can have one of two values: true or false it is generally on or off for this data type **ex: true**
+ In addition to these three data types, JavaScript also has others (arrays, objects, undefined, and null\)
+ Unlike some other programming languages, when declaring a variable in JavaScript, you do not need to specify what type of data it will hold

## **Variable Vinsmoke try to store a number**  
![numberstore](./Images/store-a-number-example1.png)   
![numberstore](./Images/store-a-number-example2.png)    
+ Here, three variables are created and values are assigned to them.  
+ price holds the price of an individual tile  
+ quantity holds the number of tiles a customer wants  
+ total holds the total cost of the tiles  
+ Note that the numbers are not written inside quotation marks. Once a value has been assigned to a variable, you can use the variable name to represent that value
+ Here, the total cost is calculated by multiplying the price of a single tile by the number of tiles the customer wants
+ The result is then written into the page on the final two lines. You see this technique in more detail on 
The first of these two lines finds the element whose id attribute has a value of cost, and the final line replaces the content of that element with new content
+ There are many ways to write content into a page, and several places you can place your script

## **Variable Vinsmoke try to store a string**  
![storeastring](./Images/store-a-string-example.png)  
+ Two variables are declared in the above example username & message and they and used for the above strings 'Molly' & 'See our upcoming range'
+ Note how the string is placed inside quote marks
+ The quotes can be single or double quotes, but they must match
+ Quotes should be straight (not curly) quotes
+ Strings must always be written on one line

## **Variable Vinsmoke try to using quotes inside a string**
![insdieastring](./Images/inside-a-string-example.png)   
+ Sometimes you will want to use a double or single quote mark within a string
+ Because strings can live in single or double quotes, if you just want to use double quotes in the string, you could surround the entire string in single quotes
+ If you just want to use single quotes in the string, you could surround the string in double quotes (as shown in the third line of the above example)
+ You can also use a technique called escaping the quotation characters. This is done by using a backwards slash (or "backslash") before any type of quote mark that appears within a string (as shown on the fourth line of this code sample).
+ The backwards slash tells the interpreter that the following character is part of the string, rather than the end of it.

## **Variable Vinsmoke try to store a boolean**
![booleanexample](./Images/store-a-boolean-example.png)  
+ A Boolean variable can only have a value of true or fa1se
+ It is rare that you would want to write the words true or false into the page for the user to read, but this data type does have two very popular uses
+ Booleans are used when the value can only be true/ fa1se
+ Second, Booleans are used when your code can take more than one path. Remember, different code may run in different circumstances

## **Variable Vinsmoke time to learn some shorthand**
![shorthand](./Images/shorthand-example.png)  
+ Variables are declared and values assigned in the same statement
+ Three variables are declared on the same line, then values assigned to each
+ Two variables are declared and assigned values on the same line. Then one is declared and assigned a value on the next line
+ The third example shows two numbers, but you can declare variables that hold different types of data on the same line, e.g., a string and a number
+ Here, a variable is used to hold a reference to an element in the HTML page

## **Variable Vinsmoke change your Value**
![changethevalue](./Images/changing-the-value-example.png)  
+ Once you have assigned a value to a variable, you can then change what is stored in the variable later in the same script
+ Once the variable has been created, you do not need to use the var keyword to assign it a new value. You just use the variable name, the equals sign (al so known as t he assignment operator), and the new value for that attribute

## **Variable Vinsmoke what is your name**
+ There are six rules you must follow when giving a variable a name
  1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number
  2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name
  3. You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript [cheatsheet](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/_keywords.html)
  4. All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases 
  5. Use a name that describes the kind of information that the variable stores. For example, firstName might be used to store a person's first name, lastName for their last name, and age for their age
  6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, firstName rather than firstname

# **Vinsmoke Variable has a Summary**
+ A script is made up of a series of statements. Each statement is like a step in a recipe.
+ Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.
+ Variables are used to temporarily store pieces of information used in the script.
+ Arrays are special types of variables that store more than one piece of related information.
+ JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).
+ Expressions evaluate into a single value. Expressions rely on operators to calculate a value.
+ A script is made up of a series of statements. Each statement is like a step in a recipe.
+ Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.
+ Variables are used to temporarily store pieces of information used in the script.
+ Arrays are special types of variables that store more than one piece of related information.
+ JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).
+ Expressions evaluate into a single value. Expressions rely on operators to calculate a value

## **Surf The Website**
- [**Homepage**](../102homepage.md)
- [**Markdown**](../Markdown.md)  
- [**Fun With Terminal**](../Terminal.md)
- [**Git Who**](../Git.md)
- [**HTML**](../HTML.md)
- [**CSS**](../css.md)
- [**JavaScript pt 2**](../yonkojavascript.md)
- [**Computers??**](../howcomputerwork.md)
- [**Fun with Loops**](../yonkojavascript3.md)
<!-- DrP E-Sign Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start -->
