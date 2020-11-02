# CLASS 06 READING NOTES

- [Home](https://seidomo.github.io/201-reading-notes/home) 


## WHAT IS AN OBJECT? 

- Objects group together a set of variables and functions to create a model of a     something you would recognize from the real world. In an object, variables and  functions take on new names. 

* IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES 
If a variable is part of an object, it is called a property. Properties tell us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms. 

* IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS 
If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms. 

Programmers use a lot of name/value pairs: 
- HTML uses attribute names and values. 
- CSS uses property names and values. 
In JavaScript: 
- Variables have a name and you can assign them a value of a string, number, or Boolean. 
- Arrays have a name and a group of values. (Each item in an array is a name/value pair because it has an index number and a value.) 
- Named functions have a name and value that is a set of statements to run if the function is called. 
- Objects consist of a set of name/value pairs (but the names are referred to as keys). 


## DOCUMENT OBJECT MODEL 'DOM'

- The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window. 
The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. It is implemented by all major browser makers, and covers two primary areas:

- MAKING A MODEL OF THE HTML PAGE 
When the browser loads a web page, it creates a model of the page in memory. 
The DOM specifies the way in which the browser should structure this model using a DOM tree. 
The DOM is called an object model because the model (the DOM tree) is made of objects. 
Each object represents a different part of the page loaded in the browser window. 

- ACCESSING AND CHANGING THE HTML PAGE
The DOM also defines methods and properties to access and update each object in this model, which in turn updates what the user sees in the browser. 
You will hear people call the DOM an Application Programming Interface (API). User interfaces let humans interact with programs; APls let programs (and scripts) talk to each other. The DOM states what your script can "ask the browser about the current page, and how to tell the browser to update what is being shown to the user.

- The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element.

- LOOPING THROUGH A NODELIST 
If you want to apply the same code to numerous elements, looping through a Nodelist is a powerful technique. 
It involves finding out how many items are in the Nodelist, and then setting a counter to loop through them, one-by-one. 
Each time the loop runs, the script checks that the counter is less than the total number of items in the Nodelist

- ADDING ELEMENTS USING DOM MANIPULATION 
DOM manipulation offers another technique to add new content to a page (rather than i nnerHTML). It involves three steps: 
CREATE THE ELEMENT  createEl ement () 
You start by creating a new element node using the createElement() method. This element node is stored in a variable. 
When the element node is created, it is not yet part of the DOM tree. 

- EXAMINING THE DOM IN CHROME 
Modern browsers come with tools that help you inspect the page loaded in the browser and understand the structure of the DOM tree. 

- EXAMINING THE DOM IN FIREFOX 
Firefox has similar built-in tools, but you can also download a DOM inspector tool that shows the text nodes. 


- [Previous](https://seidomo.github.io/201-reading-notes/class05) 