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
...but there are multiple ways 
