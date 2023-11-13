# LISTS .(0-0 ).
> SORRY IF THERE IS ALOT OF INFORMATION (TRYING TO GET YOU GUYS TO UNDERSTAND :P)

Here, we have another difficult thing to understand. Lists are basicaly variables that hold multiple values. It can hold both numberical values and string values within the same list. We can use values to accomplish certain things within a program. We can:
- Append/Remove/Insert values from a list
- Use loops to check through a list
- Add values together within a list

...There are multiple implications, as we can see from the examples given. Since we are not to well informed on how each example works in the first place, let me run through the 3 that I have listed.

## APPEND/REMOVE/INSERT
Before starting, we need to go over what appending is, what removing is, and what inserting is. Appending an item to a list indicated that you are adding a value to a lsit, all the way at the very end. Removing a list is indicating what value you want to remove and take it away. Inserting is the same as appending, but instead you are indicating where the value is going to go. Here is example of all 3 of these:
```js
//FORMATING OF THESE 3

appendItem(list, item);

removeItem(list, indexNumber);

insertItem(list, indexNumber, item);
```
```js
//FULL EXAMPLE

var junkYard = ["car", 1090, "Scrap Metal", "Pipe", 12, "Dirt"];
var newJunkYard = ["nothing..."];

appendItem(newJunkYard, junkYard[0]);
appendItem(newJunkYard, junkYard[4]);
removeItem(newJunkYard, 0);
removeItem(junkYard, 1);
removeItem(junkYard, 3);
insertItem(newJunkYard, 0, junkYard[1]);
insertItem(newJunkYard, 0, junkYard[3]);
```
## LOOPS
Loops can also be used within list values. It can check for multiple values, goes through the list depending on the length of the list (will go over this...), and even add all the values within a list to another one in a singe line!. To further explain this, here is an example of how it works.
```js
//Dont really need formating for loops, go to loops page
//FULL EXAMPLE

var kitchen = ["apples", "knives", "bannana", "meat", "cutting board", "stove", "microwave"];
var newKitchen = [];

for(var i = 0; i < kitchen.length; i++){
//kitchen.length checks for the amount of items within the list, which would be 7
appendItem(newKitchen, kitchen[i]);//takes the current index of the kitchen and adds to the new kitchen
}
```
## ADDING VALUES
If we can use loops as well as appending values, we can also add certain vlaues together! Since list can also contain numerical values, that means that we can use all mathematical opperators on certain values together within a list format! Similar to actually using opperators with variables, we can apply this same knowledge and get the same outcome. For example:
```js
//Dont really need formating for loops, go to loops page
//FULL EXAMPLE

var mathTest = [20, 70, 65, 83, 4];
var newMathTest = [];

for(var i = 0; i < mathTest.length - 1; i++){
  var adittion = mathTest[i] + mathTest[i + 1]; //Uses adition for index value and index value + 1
  var subtraction = mathTest[i] - mathTest[i + 1]; //Uses subtraction for index value and index value+1
  var multiplying = mathTest[i] * mathTest[i + 1]; //Uses multiplication for index value and index value + 1
  var division = mathTest[i] / mathTest[i + 1]; //Uses division for index value and index value + 1
  appendItem(newMathTest, adittion);
  appendItem(newMathTest, subtraction);
  appendItem(newMathTest, multiplication);
  appendItem(newMathTest, division);
}
```
### TESTING :nerd-emoji:

1) How can you add values to a list?

2) How can you use loops to itterate throughout a while list?

3) What are some opperators that you can use within lists?
