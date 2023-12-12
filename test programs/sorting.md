```js
/////////////////////////////////////////
/*       this might be incorrect       */
/////////////////////////////////////////

var APCSClassroom = ["Aidan", "Hana", "Mathew", "Nicholas", "Kiki", "Jonathan", "Derick", "Ben", "Drake"]; //Name of students in an APCS classroom
var grades = ["C", "A", "A", "B", "A", "B", "C", "B", "C"]; //Random grades (NOT TURE)
var nameSortedList = []; //Empty list for sorting names
var gradeSortedList = []; //Empty list for sorting grades

function nameSort (){
  for(var i = 0; i < APCSClassroom.length; i++){
    if (APCSClassroom[i] < APCSClassroom[i + 1]){ //checks the current index with the index above and checks if its less than that index.
      append(nameSortedList,APCSClassroom[i]); //Adds according value to the new lsit
    } else {
      insert(nameSortedList, APCSClassroom.length, APCSClassroom[i]); //if function is false, sends name to the very back
    }
  }
}

function gradeSort (){
  for(var i = 0; i < grades.length; i++){ //checks the current index with the index above and checks if its less than that index.
    if (grades[i] < grades[i + 1]){ //Adds according value to the new lsit
      append(gradeSortedList, grades[i]);
    } else
      insert(gradeSortedList, grades.length, grade[i]); //if function is false, sends grade to the very back
  }
}


nameSort(); //runs the function

gradeSort(); //runs the function
```
