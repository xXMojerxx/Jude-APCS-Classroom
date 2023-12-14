```js

var total = 0;
var numbers = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9];

numbers.forEach(function(button){
  onEvent(button, "click", function(){
    total = total + button;
  });
};

console.log(total);

```
