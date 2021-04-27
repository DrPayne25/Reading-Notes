# **Class 00 Developer Payne's Origin**

## **Section Selector**:
- [Structure](#structure)
- [Extra Markup](#extra-markup)
- [HTML 5 Layout](#html-5-layout)
- [Process & Design](#process--design)
- [The ABC of Programming](#the-abc-of-programming)

---   
## **Structure**

### **Key Takeaways**
1. An HTML Page is just one big text document looks at the inspect tool if you don't believe me
2. Tags are used in HTML to give the characters inside angled brackets the special meaning for instance a <p\> will be used to note this is the paragraph section </p\> is used to end that 
3. Tags are often referred to as elements
4. Tags often come in pairs generally an opening tag to tag the start and a closing tag to tag the end
5. An opening tag can carry an attribute which can give more content to that element
6. Attributes require a name and a value 
7. Tags are very important in HTML knowing which ones are available and what what they do and where they go

---    
## **Extra Markup**

**DOCTYPES**: Each page should begin with a DOCTYPE declaration to tell a browser which version of htm the page is using  
**<!DOCTYPE html\>**: is the HTML 5 way to declare the version   
<!-- Bet you didn't see this coming Surprise Comment --> Inspect This line for a cool surprise  
**ID Attribute**: every html element can carry the ID Attribute. Its used to uniquely identify that element from other elements. It value should start with a letter. 
No two ID attributes should be the same  
**Class Attribute**: Used to identify several elements as being different but doesn't have to be unique like the ID but can be different
If can indicate that an element belongs to several classes by separating the names with a space 
**Block Elements**: some elements will always start on a new line examples include <h1\> <p\> <ul\> <li>
**<div\>**: is the element that allows you to group a set of elements together in one block-level box
Using the id or class attribute on a div will allow you to create CSS rules to style how much space it takes up
Adding a comment before or after a div is a good way to label what it is 
**<span\>** is the inline equivalent of the div tag to be used in either situation  
   1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text  
   2. Contain a number of inline elements  

### **IFrames** 
This is basically picture in picture used commonly to put a google map on a page. It needs a few attributes
    1. **SRC** tells us the URL of the page to show in frame
    2. **Height** tells us the height of the iframe in pixels
    3. **Width** tells us the width of the iframe in pixels  
Scrolling & Frameborder are not supported in HTML5 
**seamless** is the new HTML5 attribute to apply when scrollbars are not desired

## **Info about the Page**
The <meta\> lives inside the <head\> and contains info about the web page 
The most common attributes are the name and content attributes which tend to be used together 
The value of the name attribute is the property you are setting and the value of content is the value that you want to give the property  
![meta](./Images/meta-examples.png)  

### **Key Takeaways**
- DOCTYPES tell browsers which version of HTML you are using.
- You can add comments to your code between the <!-- and --\> markers.
- The id and class attributes allow you to identify particular elements.
- The <div\> and <span\> elements allow you to group block-level and inline elements together.
- <iframes\> cut windows into your web pages through which other pages can be displayed.
- The <meta\> tag allows you to supply all kinds of information about your web page.
- Escape characters are used to include special characters in your pages such as <, >, and ©.

---
## **HTML 5 Layout**
<header\> & <footer\> can be used in 
- the main header or footer that appears at the top or bottom of every page on the site
- A header or footer for an individual <article\> or <section\>

<nav\> can be used to contain the major navigational blocks on the site such as the primary site navigation  
This can also be used in the footer to contain things like privacy policy & t&c for a website  

<article\> this element is used as a container for any section of a page that could stand alone.
If a page contains several articles then each individual article would live inside its own article element  
The article element can be nested inside each other think of a comments section on a website that could be an article within an article  

<aside\> this element has two purposes based on if it is in an <article\> or not  
When placed inside it should contain information that is related to the article but not essential to its overall meaning.   
When placed outside it acts as a container for content that is related to the entire page.  

<section\> groups related content together typically each section has its own heading  
The section element should not be used as a wrapper for the entire page this is best left for a <div\>  

<hgroup\> this element serves to group together a set of one or more <h1\> through <h5\> elements so that they are treated as one single heading  
The jury is still out on this one for the moment on weather it is a useful or not to group up titles like this  

<figure\> & <figcaption\> The figure element can bue used to contain any content that is referenced from the main flow of an article  
if you were to remove the content of the figure element the article should still make sense  
Due to this it should only be used when the content simply references the element 
**Usage** 
- Images
- Videos
- Graphs
- Diagrams
- code samples
- text that supports the main body of an article  
The figure element should also contain the figcaption element to provide a text description of the figure element 

<div\> the div element will remain an important way to group together related elements the new elements listed above should ony be used for there express purpose 

<a\> use this element around and entire block to make it all into a link 

Older browsers that do not know the new HTML5 elements will automatically treat them as inline elements. Therefore, to help older browsers, you should include the line of CSS below which states which new elements should be rendered as block-level elements. <!-- this was taken from pg 442 of the book-->
![broswer](Images/browser.png)
![ie9](Images/ie9-helper.png)  

### **Key Takeaways**  
- The new HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.
- The new elements provide clearer code (compared with using multiple <div> elements).
- Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
- To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.

---
## **Process & Design**

### **Who??**
*Knowing your target audience is important when designing and creating a website while worldwide appeal would be great your target audience is who most likely will interact with it*
Creating fictional visitors to the website will allow you to refer back to there needs when thinking about your audience 

### **Target Audience: Individuals**
- What is the age range of your target audience?  
- Will your site appeal to more women or men? What is the mix?  
- Which country do your visitors live in? 7 < 2 > 
- Do they live in urban or rural areas?  
- What is the average income of visitors?  
- What level of education do they have?  
- What is their marital or family status?  
- What is their occupation?  
- How many hours do they work per week?  
- How often do they use the web?  
- What kind of device do they use to access the web?  

### **Target Audience: Companies**
- What is the size of the company or relevant department? 
- What is the position of people in the company who visit your site? 
- Will visitors be using the site for themselves or for someone else? 
- How large is the budget they control? 

## **Why?**
*Once you figure out who is coming to the website now we get into the why are they visiting.*

Two Basic categories of questions you can ask to help determine why they are coming
### **Key motivations** 
- Is this for general entertainment or Do they have a specific need 
- Is there a goal personal or professional
- Is the time investment a essential need or a luxury

### **Specific Goals**
- Are they looking for vernal information such as background info on a topic or are they looking for something specific such as a certain fact 
- Is this a product that they are already familiar with or do they need an intro
- Are they coming for time sensitive information such as news or updates
- Are they looking to discover specific product or service to help them decide to buy or not
- Are you going to need to be contact info do they need to visit you in person 

## **What?** 
*What are your visitors trying to achieve?*

- Creating a list of all the reasons a person would visit your site can help you find out what they are trying to achieve
- Thinking about what a visitor will need to achieve what they are looking to do is the next key step 
- Remember you are working with human psychology here if someone doesn’t find what they need quickly or it is wrong info they will most likely look elsewhere
- Will visitors be familiar with your subject area / brand or do you need to introduce yourself? 
- Will they be familiar with the product / service / information you are covering or do they need background information on it? 
- What are the most important features of what you are offering? 
- What is special about what you offer that differentiates you from other sites that offer something similar? 
- Once people have achieved the goal that sent them to your site, are there common questions people ask about this subject area? 

### **How?**
*How often will people come to your site*

- Understanding how often people are to revisit a site will help you understand how often you need to update it if they are visiting it once every six months it may not be need to be updated as frequently as a website that someone is revisiting twice a day 7 days a week 
- Setting a schedule for these updates can be helpful to keep track instead of ad hoc 
- A site doesn’t need to be updated all at once or nothing some parts might not need and update as frequently 

### **Goods/Services**
- How often do the same people return to purchase from you? 
- How often is your stock updated or your service changed? 

### **Information**
- How often is the subject updated? 
- What percentage of your visitors would return for regular updates on the subject, compared with those who will just need the information once? 

## **Floorplans really???**

- Site Maps are basically another word to describe a layout of the site structure
- Card Sorting is a technique to help you figure out where information should go
- Asking your target audience about helping group related info they are using it 
- Site Maps start with a home page  
￼![SiteMaps](https://user-images.githubusercontent.com/81712870/114134400-8ce4a380-98bc-11eb-9791-da939cf9e8fb.png)
- Remember to focus on the goal a visitor is hoping to achieve if they can’t do that easily and intuitively they will most likely look elsewhere
- Remember you want to organize it in a way the reflect your target audience if it doesn't make sense to them but you are they going to use it? 

## **Wireframes**
Its a simple sketch of the key info on that needs to go on each page 

- Include info such as the logo, primary navigation, headings and main bodies of text, user logins 
- Don’t include info such as color scheme, font choices, backgrounds or images for the website 
- Remember this is a good way to have them focus on the site functions not the site look that can adjust much easier than site functions
![WireFrames](https://user-images.githubusercontent.com/81712870/114134414-9241ee00-98bc-11eb-89f6-b44df16887cb.png)

## **Message = Design**
*The primary aim of any kind of visual design is to communicate*

- By making parts of the page look distinct from surrounding content, designers draw attention to (or away from) those items. 
- Designers create something known as a visual hierarchy to help users focus on the key messages that will draw people's attention, and then guide them to subsequent messages. 
- Grouping together related content into blocks or chunks makes the page look simpler (and easier to understand). 

Visual Hierarchy
Most folks don’t read an entire website they skim through for the information that is important to them using visual hierarchy can help get your message across and help them find what they are looking for.


## **Navigation**

- Concise: Try to limit the number of options in a menu to no more than eight link 
- Clear: User should be able to guess what they are clicking on if it says dog photos but takes to cat photos is that clear
- Selective: Primary navigation should only reflect the sections or content of a site
- Context: Let a user know where they are in the website using color and visual markers 
- Interactive: Links should be big enough to click on and it should change when the user hovers over each item or clicks on it
- Consistent: Keep things the same your primary navigation should be the same everywhere not different on one page

### **Key Takeaways**
- Understand your who the target demo is, why are they coming, what are they looking for and when are they coming back 
- Site maps allow you to pan the layout of the site
- Wireframes help you organize the info that will go on each page
- Design is another form of communication. Visual Hierarchy helps visitors understand what you are trying to get across
- Size, color, and style help differentiate between pieces of info
- Grouping and similarity to help simplify what you are presenting with your audience  

---
## **The ABC of Programming**
A script is a series of instructions that a computer can follow to achieve a goal.  
To write a script you need to first state your goal and then list the tasks that need to be completed in order to achieve it.  
Break your big goal in to smaller easier to achieve steps
1. Define the goal - what are you trying to achieve 
2. Design the script - break the goal you just defined into smaller tasks
3. Code each step - write each step down in a programming language the computer understands   
Computer are very logical and obedient. They need to be told every detail of what they are expected to do.  

Computer solve problems programmatically they follow a series of instructions one after another   
Each physical thing in a world can be represented as an object in computer programming  
Characteristics of an object are often called properties by programmers   
Each property has a name and a value they each tell you something about an individual instance of an object  
An event is the computer's way of telling you hey something happened  
Scripts often use different events to trigger different types of functionality   
**What is a Method?**  
Methods typically represent how people or things interact with an object in the real world   
**What does a method do?**  
The code for a method can contain lots of instructions that together represent one task 
When using a method you don't always need to know hot it achieves its task you just need to know how to ask the question and how to interpret any answers it gives you  
Computers use data to create models of things in the real world.  
The events, methods, and properties of an object all relate to each other: Events can trigger methods, and methods can retrieve or update an object's properties  
Web Browsers are programs built using objects  

**PROPERTIES**  
Properties describe characteristics of the current
web page (such as the title of the page).  

**METHODS**  
Methods perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or adding new content).    

**EVENTS**  
You can respond to events, such as a user clicking or
tapping on an element.  
All major browsers use a JavaScript interpreter to translate your  

**How A Browser sees a web page**  
1. The browser receives an html page
2. It creates a model of the page and stores it in memory.
3. It shows the page on screen using a rendering engine.  
3 languages are generally used to create web pages HTML, CSS, & Javascript  
- HTML handles Content  
- CSS handles Presentation  
- Javscript Handles Behavior  
Layer these 3 on top of each other starting with HTML then CSS followed by Javascript this means that your site will run on all browser versions in some form  
Javascript should be in its own folder in your website  
Calling a method of an object is generally how you use objects and methods 


### **Key Takeaways**
**What is a script and how do I create one?**  
- A script is a series of instructions that the computer can follow in order to achieve a goal.
- Each time the script runs, it might only use a subset of all the instructions.
- Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task programmatically.
- To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).
**How do computer fit in with the world around them**
- Commuters create models of the world using data
- the models use objects to represent physical things objects can have: properties that tell us about the object; methods that perform tasks using the properties of that object; events which are triggered when a user interacts with the computer.
- Programmers can write code to say "When this event occurs, run that code."
- Web browsers use HTML markup to create a model of the web page. Each element creates its own node(which is a kind of object.\)
- To make web pages interactive, you write code that uses the browser's model of the web page.   
**How do I write a script for a web page**
- It is best to keep JavaScript code in its own JavaScript file. JavaScript files are text files (like HTML pages and CSS style sheets), but they have the .js extension.
- The HTML <script\> element is used in HTML pages to tell the browser to load the JavaScript file (rather like the <link\> element can be used to load a CSS file).  
- If you view the source code of the page in the browser, the JavaScript will not have changed the HTML, because the script works with the model of the web page that the browser has created.
---

## [**Code 201 Reading Notes**](201homepage.md)
  1. [Class 00](class-01.md)
  2. [Class 01](/201/class-02.md)
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