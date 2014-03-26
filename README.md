---
tags: arrays, data types, loops, jQuery, WIP
language: JavaScript, JS
---

# Arrays and Loops in JavaScript

##Objectives:

*  Gain a familiarity with JavaScript arrays and loops.
*  Use this information to change the div with the id of "print" to display the results of the instructions.

##Instructions:

###Arrays:

*  Arrays are list-like objects, simmilar to a bookshelf that has slots to store different books (elements) in a single shelf. Books can be fetched by identifying their (index) shelf position.
*  Declaring an empty array using the Array constructor.
```javascript
var myArr = new Array();
```
*  Declare an empty array using literal notation (hint: this is very similar to Ruby sytax).
*  Arrays are filled with elements:
```javascript
myArr3 = [element, anotherElement];
```
*  Elements can be strings, numbers, or boolean. If you leave a blank spot in an array it creates a blank shelf space (null) placeholder. Keeping these characteristics in mind, make a new array, "myArr", with four elements that will behave in the following ways:
```javascript
myArr[0]
  --> 'Hello'
myArr[1]
  --> undefined
myArr[2]
  --> 54.3
myArr[3]
  --> true
```
*  We can insert new values into any space in the array using the positions index. Change the undefined item in "myArr" to equal the string "Stuff" instead.

###Associative Arrays:
*  Associative arrays allow us to define the index as a string. For instance:
```javascript
alphabetArr = ['A', 'B', 'C', 'D'];
myArr['first'] = myArr[0];
myArr['first'];
  --> 'Hello'
```
*  Create an association so that calling myArr['Greeting'] will return "Hello"

###Overwriting:
*  We can overwrite all the elements of an array simply by giving the array new values. Or passing one array into another.
*  Make an array called "fruits" where the four elements are these strings: Apples, Oranges, Pears, and Bananas.
*  Overwrite "myArr" to equal "fruits".

###Retrieving the Total Number of Elements and Last Index:
*  Call length on the myArr. Is the result the number you were expecting?
*  Keeping in mind the fact that indexes start with zero instead of one, get the last element's index position in "myArr".
*  Make a variable "pos" and set it equal to the number you found in the step just above.
*  What should myArr[pos] return? Does it?

###

##Resources:
* [Codecademy](http://www.codecademy.com/tracks/javascript)
* [Code School](https://www.codeschool.com/paths/javascript)
