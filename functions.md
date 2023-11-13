# FUNCTIONS .(>-< ).
> SORRY IF THERE IS ALOT OF INFORMATION (TRYING TO GET YOU GUYS TO UNDERSTAND :P)

Function are going to be a core component to your code, make it easier to read, debug, and apply. You ***SHOULD** always have a function OUTSIDE of an onEvent function. Functions are used in every app (since it is a requirement for the APCS exam), but there are multiple ways to apply it. 

Since there are multiple ways to apply it, first we have to go over what is needed within a function. First, we need to call the function that we are going to use. Then we have to add a certain perameter/condition that needs to be met throughout the program, whether it be repeating or just for one instance. Lets start off with this:
```js
var cafeteria = ["person1", "person2", "person3", "person4", "person5"]; //im being big lazy

peopleInACafeteria(); //Runs the function given

function peopleInACafeteria () { //Calls the function under "peopleINACafeteria
  console.log(cafeteria.length); //runs whatever the function states to do.
}
```
...but there are multiple ways to use a function! To break your mood, this is the most simplistic way of using a function. In which we are going to move onto parameters (this is where it gets very confusing). 

Parameters, in a sense, are just variables that can ***ONLY BE USING WITHIN THE FUNCTION***. These parameters help indicate what values you are trying to check without repeating the same code over and over. Let me give a small demonstration as to how parameters work:
```js
//FORMATING YIKERS
function functionName (parameter) {//calls a function with a parameter
  parameter = value; //uses this parameter ro add values to it depending on what its asking
  return parameter; //HAVE TO USE RETURN TO HMAKE THE PARAMETER WORK!!!!!
}
```
```js
//FULL EXAMPLE (something that used :3)
function averageDiceChecker(average) { //Calls the function and the parameter "average"
  var total = 0;
  for (var i = 0; i < diceList.length; i++) {
    total = total + diceList[i];
  }
  average = total / diceList.length; //parameter is used to get the average of the dice's rolled
  if (average >= 4.3) {
    setText("averageRollText", "HIGH ROLL = " + average); 
  } else {
    setNumber("averageRollText", average);
  }
  return average; //returns the value of "average", and adds it to where the function is called
}
```

