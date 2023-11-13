# LOOPS .(x-x ).
> SORRY IF THERE IS ALOT OF INFORMATION (TRYING TO GET YOU GUYS TO UNDERSTAND :P)

Here we have loops, one of the more confusing parts to programming. Just as the name indicates, a loop is a function in which a program is itterated ***IN A LOOP*** multiple times, unless indicated to stop. 

Loops help itterate through a list, going though each and every individual value. Before using loops, you first have to understand how a lsit works (but we are going to go over that later on) There are two main loop functions:
### - WHILE-LOOP
### - FOR-LOOP
... But in terms of what you SHOULD be coding with, ***FOR LOOPS*** are going to be the generic type of loop you should be using. But lets go over both of them.

## WHILE LOOP
While loops are used to go throught ***EVERY VALUE*** within a list. No matter what values are in a list, it will go through every value untill it meets the condition that is set, if any. 

Since I have never used a while loop IN MY LIFE, i dont really know how to use them properly or effectivly, but if it fits your style, then go ahead. Here is (might be correct) an example of a while loop:
```js
//FORMAT OF A WHILE LOOP

while (condition){
 //what happens to the value depending on the condition stated
}
```
```js
//FULL EXAMPLE :3
var classroom = ["Aidan", "Jules", "Samantha", "Dan", "Johnathan", "Jose", "Sergio"];
var emptyClassroom = []; //This is an empty list
var people = 7

while (people = 7){ //Checks if the variable "people" still contains the number 7
  appendItem(emptyClassroom, classroom); //"sends" the people to the empty classroom
}
```
## FOR LOOP
For Loops, which im more comfortable with, is a loop in which its given a certain perameter to follow and does not exceed it in any way. For loops are more useful for ***specific values*** or ***specifc perameters*** that need to be followed. 

As indicated, for loops are used to check ***FOR*** a certain perameter before following through with the loop. I am going to make this a bit complicated, but bear with me it will make sense later on. Here is an example for a for-loop (using the exact same perameters and values listed above):
```js
//FORMAT OF A FOR LOOP:

for (var "variable name" = value assigned; CONDITION ; opperator (EX: i = i + 1 <- can be rewritten as i++){
  //what happenes to the values within the loop
}
```
```js
//FULL EXAMPLE :3
var classroom = ["Aidan", "Jules", "Samantha", "Dan", "Johnathan", "Jose", "Sergio"];
var emptyClassroom = []; //This is an empty list

for (var i = 0; i < classroom.length; i++;){ //Goes through the loop based on people in classroom
  appendItem(emptyClassroom, classroom); //"sends" the people to the empty classroom
  console.log(classroom[i] + "went to the empty classroom!"; //states who goes to the empty classroom
}
```
### TESTING :nerd-emoji:

1) What is a loop?

2) What does a while loop check for?

3) How does a for loop check what perameters it needs to check for?
