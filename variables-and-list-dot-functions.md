# VARIABLES & LIST DOT FUNCTIONS .(c_c ).
> SORRY IF THERE IS ALOT OF INFORMATION (TRYING TO GET YOU GUYS TO UNDERSTAND :P)

Dot functions are what you can join with variables and list to do certain things. It helps understand how a variable or list is viewed and how people can use it to their advantage. For example, the length of a string or the length of a list. Lets go over basic dot functions that are very useful!!!! (<- btw this is used in code.org)
```js
//STRING DOT FUNCTIONS FORMAT

stingName.length //grabs the length of the string based on the character amount
stringName.toUpperCase(); //makes the string characters all uppercase (ex: upPerCase -> UPPERCASE)
stringName.toLowerCase(); //makes the string characters all lowercase (ex: loWeRcasE -> lowercase)

//LIST DOT FUNCTIONS FORMAT

listName.length //grabs the length of the list, based on the amount of values in the lsit
listName.join("separator"); //joins all values in a list, having a separator which seperates the words
```
As we can see, there are multiple instances to where we can use this. For example .length, which grabs the length of a string or list. We can use these notation along side other functions like loops and functions to better have our programs run without constantly changing multiple things within code. Coding is suppose to help simplify things to mainly repeat over and over. A full examle to where these cna be use would be:
```js
//FULL EXAMPLE 

var period1APCS = [];
var period5APCS = [];
var peopleAPCS = ["Vien Tran", "Aidan Cruz", "Aidan Florido", "Jude Pulanco", "Nicholas Johnson"];

sortingClasses(); //states the functions and runs it

function sortingClasses() { //sorts the different people into their respecitve class
  for(var i = 0; i < peopleAPCS.length; i++){
    if ((peopleAPCS[i] == "Vien Tran") || (peopleAPCS[i] == "Aidan Cruz")){ //checks for these names
      appendItem(peroid1APCS, peopleAPCS[i]); //sends people who are in period 1 to period1APCS list
    } else {
      appendItem(period5APCS, peopleAPCS[i]); //sends everyone else to period5APCS list
  }
  period1APCS.join("and"); //adds the names together and puts "and" inbetween every name
  period5APCS.join("and"); //adds the names together and puts "and" inbetween every name
}
```
Although some dot functions are not as useful, it still good to understand that some dot functions have specific uses. But overall, .length is going to be one of the most important things to understand and use within your apps to check for certain valus within a list without manualy counting every value in a lsit.

### TESTING TIME

1) What is a dot function?

2) What variables do dot functions apply to?

3) Which dot function is going to be the most useful within your program (maybe)?
