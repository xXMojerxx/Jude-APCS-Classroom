# COMPLICATED CODE .('=' ).
> SORRY IF THERE IS ALOT OF INFORMATION (TRYING TO GET YOU GUYS TO UNDERSTAND :P)

Here, I am going to show you certain things you can accomplish with code.org! Although this is mainly related to code.org, you can still use the same knowledge to apply it ot other programs that you are creating outside of code.org. I cant really explain this, so look at it like this...
```js
//SEMI-FULL EXAMPLE (ALSO FORMAT) 
var listOfElements = ["image", "text", "number"];

lifOfElements.forEach(function(element){ //grabs the values within the list, using "element" as the parameter
  onEvent(element, "click", function(){
    if (element == "image"){ //If user clicks on the image, sets the image
      setImage("image", "image.png");
    } else if (element == "text") { //If the user clicks on the text, sets the text
      setText("text", "hello there!");
    } else if (elemetn == "number"){ //If the user  clicks on the number, sets the number
      setNumber("number", 3);
    }
  });
});
```
Looks confusing at first? Well, we can see that we added a new dot function -> .forEach!!!. .forEach checks every value within the list and creates a function based of off it. This is where we get into the semi-complicated zone. 

Since we can use .forEach now, we can also aply this to elements we have created! Going based pff the program above, we can see that I have made 3 elements, an image, a text, and a number. Using these elements, we can check ***FOR EACH*** elements and apply it to the on event function. Think of it as a way to replace the parameter with whatever element you are trinyg to use. 

So, if i were to have 3 elements presented, I am running the function the amount of elements I have. If i were to click on the image element, we can replace the element parameter with image instead. Same thing goes for the text and the number

Going off of this, we can also use time within our app (meaning running a line of code after a set amount of time. For example:

```js
var counter = 0;

onEvent("screen", "click", function() {
  timedLoop(500, function(){ //plays in intervals of 1 second (i believe)
    counter++;
    if (counter == 5){ //plays after 5 seconds
      console.log("hello there");
    } else if (counter == 10){ //plays after 10 seconds
      console.log("how is your day?");
    } else if (counter == 20) { //plays after 20 seconds 
      console.log("good to hear...")
    } else if (counter == 30) { //plays after 30 seconds
      console.log("anyways... i hope your day tmrw is just as good!!!!);
    }
  });
});
```
As we can see, we create an onEvent function first. This function sets when the timedLoop with begin. timedLoop indicated how long the function is going to count for and how long each interval is going to be. Assuming that 500 is one second, we can set the timedLoop to 1 second intervals, to where it counts every second.

Going off of this, we can add a counter, to where it counts every second. Using this counter, we can set if statements for each 5 second interval and apply past knowledge of using an output to the user. For example, the first iff statement plays after 5 second, saying to the user VIA ***CONSOLE LOG***.

Everythig is going to look fairly easy right now, but as you start to use it as well as apply it to your code, its going to get ***MORE COMPLICATED*** in terms of application, errors, and debugging. So I wish you good luck if you are going to plan to use this, and start to learn more from it!

### TESTING TIME

1) What does ***.forEach*** do?

2) What interval does ***timedLoop*** count for?

3) Why is using these function confusing?
