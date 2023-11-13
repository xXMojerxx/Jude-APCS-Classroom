# INPUT AND OUTPUT .(._. ).
> SORRY IF THERE IS ALOT OF INFORMATION (TRYING TO GET YOU GUYS TO UNDERSTAND :P)

Since in APCS we are creating apps, we are required to have ***INPUT*** and ***OUTPUT*** functions! It gets very confusing at first, but lets go over the basics. For these current examples, we are going to create these mini programs in code.org, so please test them out and mess around with them!!! (helps you learn better!). To first indicate what an input and output could consist of:
## INPUT :\
Input are usualy indicated to where a user interacts with an object ***OR*** adds a value into the program via UI (User interface). Some examples of this could include a user interacting with a button or a user inputing their age within the program. Here are a few examples for this:
```js
//FORMAT OF DIFFERNT INPUTS

onEvent("name of item", "type of user interaction", function(){
  //what runs when the event happens
});

//OR

variable = getText("UI Element"); // Grabs value from the UI indicated
```
```js
//FUNNY EXAMPLE '-'
var age = 0; //Creates a blank variable, to where a user can add values to it

//User interacting with something
onEvent("ageButton", "click", function(){
  age = 17; //When the button is pressed, assign the value "17" to the variable "age";
});

//User inputing something
age = getText("ageBox"); //Grabs the age from the user when they input into "ageBox"
```
## OUTPUT :|
An output, on the other hand, sends information to the user instad of receiving an input. When creating an output, we usualy need a UI(User interface) to send this information to the user. Just like inputs, there are multiple ways to send information to the user. Adding onto the program above, here are some exaples of output:
```js
//FORMAT OF DIFFERNT OUTPUTS

console.log(variable); //Sends the value of the variable to the console log

//OR

setText("UI Element", variable) //Sets the value of the value to the UI element
```
```js
//FUNNY EXAMPLE '-'
var age = 0;

//User interacting with something
onEvent("ageButton", "click", function(){
  age = 17; 
});

//User inputing something
age = getText("ageBox");

//Output to user VIA console log
console.log(age); //Sends the age to the console log in which the user can view it

//Output to user VIA UI
setText("ageBar", age); //Finds the element "ageBar" and assigns the current age to it
```

### TESTING TIME :nerd-emoji:

1) What is an input and what is a output?

2) For input, what can be used to input something ***VIA*** user?

3) For output, what is used when outputing to ***a console log?***?
