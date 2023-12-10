# CARD SORTING APP
```js
//Variables used to hold the values of each card//
var cardList = [];
var handList = [];

//Starts of the program when clicking the "Run" button//

generateCards();
lowestNumberChecker(cardList);

//>>>>>>>>>>>>>>>>>>>>>>>>>>>>-<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<//
//--- CODE TO CHECK FOR SMALLEST NUMBER BETWEEN ALL CARDS ---//
//>>>>>>>>>>>>>>>>>>>>>>>>>>>>-<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<//

function lowestNumberChecker(list) {

  // Cards are represented as a number 1 - 13, where Jack, Queen, and King are 11, 12, and 13
  var min = 13; 
  for (var i in list) { // checks EVERY item within a list
    if (list[i] < min) { // For every card, checks if the card is less than the minimum
      min = list[i]; // If the card is less than the minimum, makes this value the minimum
    }
  }

  // Once all the cards are gone though, it sets the text to the current minimum card and displays it

  setNumber("lowestCard", min);
  console.log("I found it! " + "The lowest number is : " + min);
}

//>>>>>>>>>>>>>>>>>>>>>>>>>>>>-<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<//
//--- CODE TO CHECK FOR SMALLEST NUMBER BETWEEN ALL CARDS ---//
//>>>>>>>>>>>>>>>>>>>>>>>>>>>>-<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<//

// Creates a random set of 8 cards

function generateCards() {
  for (var i = 0; i < 8; i++) { // Creates 8 cards, randomizing from ace to king
    var randomCard = randomNumber(1, 13);
    appendItem(cardList, randomCard); // Appends to card list
  }
}
```
