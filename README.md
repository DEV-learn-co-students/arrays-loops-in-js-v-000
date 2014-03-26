---
tags: arrays, data types, loops, jQuery, WIP
language: JavaScript, JS
---

# Arrays and Loops in JavaScript

##Objectives:

*  Gain a familiarity with JavaScript arrays and loops.
*  Use this information to change the div with the id of "print" to display the results of the instructions.

##Instructions:

###1. Arrays:

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

###2. Associative Arrays:
*  Associative arrays allow us to define the index as a string. For instance:
```javascript
alphabetArr = ['A', 'B', 'C', 'D'];
myArr['first'] = myArr[0];
myArr['first'];
  --> 'Hello'
```
*  Create an association so that calling myArr['Greeting'] will return "Hello"

###3. Overwriting:
*  We can overwrite all the elements of an array simply by giving the array new values. Or passing one array into another.
*  Make an array called "fruits" where the four elements are these strings: Apples, Oranges, Pears, and Bananas.
*  Overwrite "myArr" to equal "fruits".

###4. Retrieving the Total Number of Elements and Last Index:
*  Call length on the myArr. Is the result the number you were expecting?
*  Keeping in mind the fact that indexes start with zero instead of one, get the last element's index position in "myArr".
*  Make a variable "pos" and set it equal to the number you found in the step just above.
*  What should myArr[pos] return? Does it?

###5. Array Insertion and Deletion:
*  We can insert on to the end of an Array simply by using the push method.
*  Insert the string "Strawberries" into "myArr".
*  You can pull the last element off the end using the pop method.
*  Call pop on "myArr". What will myArr[myArr.length - 1] return? Does it?
*  We can use splice method to insert content at a given position or to remove content from a given position. Here is the syntax:
```javascript
arrayToModify.splice(index, how many elements to remove, optional content to add);
```
*  Add the string "Tiger" at index 2 without removing any elements. What do you think myArr.length; will return?
*  Let's say we needed to remove the second to last item, but we do not know how long the array is...We can use negative numbers to go to end of array and index from end to beginning.
*  Replace "Pears" with "Lion" using the negative index number, using the info above.
*  Now remove Lion from the 3rd index position using splice.

###6. Loops:

####A. Introduction to Loops:
*  A loop is a set of commands that executes repeatedly until a specified condition is met. JavaScript supports the for, do while, and while loop statements.

####B. For Loops:
*  A "for" loop repeats until a specified condition evaluates to false. Here is the syntax:
```javascript
for ([initialExpression]; [condition]; [incrementExpression]) {statement}
```
*  Make an array "vegetables" with three string elements: Broccoli,Peas, and Carrots.
*  Use a "for" loop that will add each element in "vegetables" as list items to the element with the id "print".

####C. Do While Loops:
*  A while statement executes its statements as long as a specified condition evaluates to true. Here is the syntax:
```javascript
do {statement} while (condition);
```
*  Make an array "cars" with threee string elements: "Corvette","Mustang", and "Porsche".
*  Set a var "i" to 0 (you will use this to increment the index of each element)
*  Make a while loop that will add each element in "cars" as list items to the element with the id "print"

####D. While Loops:
*  Here is the syntax:
```javascript
while (condition){statement}
```
*  Make an array "fish" with three elements: "Snapper", "Tuna", and "Salmon".
*  Set a var "i" to 0 (you will use this to increment the index of each element)
*  Make a while loop that will add each element in "fish" as list items to the element with the id "print".

###7. jQuery:

####A. .each method:
*  You may notice that there is no easy way to call the each method we're accustomed to in Ruby in JavaScript. However, jQuery does provide one. Here is the syntax:
```javascript
$.each( function(index, Element) ) { statement }
```
*  Add this array to your code:
```javascript
var numbers = [5, 10, 15, 20, 25, 30 , 35, 40, 45, 50];
```
*  Use the jQuery .each method to iterate over all elements in the array one by one and add them as list items to the element with the id "print".

####B. .grep method:
*  You can use this method for filtering an array. Here is the syntax:
```javascript
jQuery.grep( array, function(elementOfArray, indexInArray) [, invert] )
``` 
*  Make a variable called "bigNumbers" that will contain only the numbers in the array "numbers" that are larger than 25.
*  Incorporate what you learned from the .each section to add each element in "bigNumbers" as list items to the element with the id "print".

##Resources:
* [MDN Array Methods](https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Global_Objects/Array)
* [MDN Loop Statements](https://developer.mozilla.org/en-US/docs/JavaScript/Guide/Statements)
* [Codecademy](http://www.codecademy.com/tracks/javascript)
* [Code School](https://www.codeschool.com/paths/javascript)
