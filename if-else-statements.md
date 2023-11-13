# IF/ELSE STATEMETNS :]
> SORRY IF THERE IS ALOT OF INFORMATION (TRYING TO GET YOU GUYS TO UNDERSTAND :P)

This is the core of creating an ap in the first place. Other than variables, these are important for the user to create decisions, interaction, and include more information within your app.

If/else statements indicate what happends when a user interacts with someting or when your app checks for something, using a true or false checker. When the vlaue is ***TRUE*** within the statement, it will run the statement. But when the function is ***FALSE***, it will continue on to the next line of code or the next statement presented.

To give a better example, I am going to give two differt programs, one for an if-statement and another one for an if/else-statement:
## IF-STATEMENT
```js
//FORMAT OF AN IF STATEMENT

if (condition){
 //condition = true, run these lines of code
}
```
```js
//ACTUAL EXAMPLE
var carBrand = "Toyota"; //Always have a variable!!!!

if (carBrand == "Toyota"){ //Checks the variable to see if the value is equal to "Toyota"
  console.log("YIPPIEE!!!");
}

console.log("uh oh..."); // Runs this line of code if the statement is FALSE
```
## IF/ELSE STATEMENT
```js
//FORMAT OF AN IF/ELSE STATEMENT
if (condition1) {
  //run these lines of code IF condition1 = true;
} else if (condtion2) {
  //run these lines of code IF condition1 = false & condition2 = ture;
}
```
```js
//ACTUAL EXAMPLE
var carBrand = "Toyota";

if (carBrand == "Mercades"){ //Chekcs if the variable's value is "Mercades"
  console.log("This if first car");
} else if (carBrand == "Tesla"){ //Chekcs if the variable's value is "Tesla" IF statement above FALSE
  console.log("Elon Musk...");
} else if (carBrand == "Lexus"){ //Chekcs if the variable's value is "Lexus" IF statement above FALSE
  console.log("erm...");
} else if (carBrand == "Toyota"); //Chekcs if the variable's value is "Toyota" IF statement above FALSE
  console.log("WE GOT THERE!!!!");
}

console.log("ggs"); //runs this line of code when all of the statements are FALSE
```
The basis of these statements is to chekc if a function or certain parameter is either true or false, and run accordingly. If statements as well as if/else statements are going to be used throughout your final app, small apps created within APCS, programs shown within the AP exam, and when writing our programs for written test. SO GET COMFORTABLE WITH THEM :) [they are not that hard i belive...]
### TESTING TIME :nerd-emoji:

1) What are if/else statements?

2) How do if statements work and what do they check for?

3) Using the if/else statement example, what would be the outcome of the program?
