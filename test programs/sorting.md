```js
var APCSClassroom = ["Aidan", "Hana", "Mathew", "Nicholas", "Kiki", "Jonathan", "Derick", "Ben", "Drake"];
var grades = ["C", "A", "A", "B", "A", "B", "C", "B", "C"]; //Random grades
var nameSortedList = [];
var gradeSortedList = [];

function nameSort (){
  for(var i = 0; i < APCSClassroom.length; i++){
    if (APCSClassroom[i] < APCSClassroom[i + 1]){
      append(nameSortedList,APCSClassroom[i]);
    } else {
      insert(nameSortedList, APCSClassroom.length, APCSClassroom[i]);
    }
  }
}

function gradeSort (){
  for(var i = 0; i < grades.length; i++){
    if (grades[i] < grades[i + 1]){
      append(gradeSortedList, grades[i]);
    } else
      insert(gradeSortedList, grades.length, grade[i]);
  }
}

```
