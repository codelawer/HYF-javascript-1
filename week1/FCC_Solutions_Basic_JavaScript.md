#####  <span id="top"></span>I already made most part of the [FCC Basic JSS](https://www.freecodecamp.org/codelawer){:target="_blank"} tasks *before this assignment.* I just create a document which illustrates what's left.<br>

### freecodecamp task1
```js 
/* assasas */
//asasas

```

### task 2 
```js
var myName;
```

[TOP](#top)
___
### Assignment with a Returned Value

```js 
// Example
var changed = 0;

function change(num) {
  return (num + 5) / 3;
}

changed = change(10);

// Setup
var processed = 0;

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line
processed = processArg(7);

```
[TOP](#top)
___
### Understanding Boolean Values

```js 
function welcomeToBooleans() {

// Only change code below this line.
return true; // Change this line(Initial its false)

// Only change code above this line.
}
```
[TOP](#top)
___
### Use Conditional Logic with If Statements

```js 
// Example
function ourTrueOrFalse(isItTrue) {
  if (isItTrue) { 
    return "Yes, it's true";
  }
  return "No, it's false";
}

// Setup
function trueOrFalse(wasThatTrue) {

  // Only change code below this line.
  if(wasThatTrue){
      return  "Yes, that was true"
  }
  return   "No, that was false"
  // Only change code above this line.

}

// Change this value to test
trueOrFalse(false);

```
[TOP](#top)
___
### Comparison with the Equality Operator

```js 
// Setup
function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testEqual(10);
```
[TOP](#top)
___
### Comparison with the Strict Equality Operato

```js 
// Setup
function testStrict(val) {
  if (val === 7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testStrict("7");
```
[TOP](#top)
___
### Practice comparing different values
```js 
// Setup
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
compareEquality(10, "10");
```
[TOP](#top)
___

### Comparison with the Inequality Operator
```js 
// Setup
function testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(99);
```
[TOP](#top)
___
### Comparison with the Strict Inequality Operator

```js 
// Setup
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val !== 17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```
[TOP](#top)
___
### Comparison with the Greater Than Operator

```js 
function testGreaterThan(val) {
  if (val >100) {  // Change this line
    return "Over 100";
  }
  
  if (val>10) {  // Change this line
    return "Over 10";
  }
  

  return "10 or Under";
}

// Change this value to test
testGreaterThan(10);
```
[TOP](#top)
___
### Comparison with the Greater Than Or Equal To Operator

```js 
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }
  
  if (val >= 10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

// Change this value to test
testGreaterOrEqual(10);
```
[TOP](#top)
___
### Comparison with the Less Than Operator

```js
function testLessThan(val) {
  if (val <25) {  // Change this line
    return "Under 25";
  }
  
  if (val<55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

// Change this value to test
testLessThan(10);
```
[TOP](#top)
___
### Comparison with the Less Than Or Equal To Operator

```js 
function testLessOrEqual(val) {
  if (val <=12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }
  
  if (val<=24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

// Change this value to test
testLessOrEqual(10);

```
[TOP](#top)
___
### Comparisons with the Logical And Operator

```js 
function testLogicalAnd(val) {
  // Only change code below this line

  if (val<=50 && val >= 25) {
    
      return "Yes";
  
  }

  // Only change code above this line
  return "No";
}

// Change this value to test
testLogicalAnd(10);
```
[TOP](#top)
___
### Comparisons with the Logical Or Operator
```js
function testLogicalOr(val) {
  // Only change code below this line

  if (val<10 || val >20) {
    return "Outside";
  }


  // Only change code above this line
  return "Inside";
}

// Change this value to test
testLogicalOr(15);
```
[TOP](#top)
___
### Introducing Else Statements
```js 
function testElse(val) {
  var result = "";
  // Only change code below this line
  
  if (val > 5) {
    result = "Bigger than 5";
  }
  
  else{
    result = "5 or Smaller";
  }
  
  // Only change code above this line
  return result;
}

// Change this value to test
testElse(4);

```
[TOP](#top)
___
### Introducing Else If Statements

```js 
function testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }
  
 else if (val < 5) {
    return "Smaller than 5";
  }
  else {
  return "Between 5 and 10";
}
}
// Change this value to test
testElseIf(7);

```
[TOP](#top)
___

### Logical Order in If Else Statements
```js 
function orderMyLogic(val) {
  if (val < 5) {
    return "Less than 5";
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}

// Change this value to test
orderMyLogic(7);
```
[TOP](#top)
___
### Chaining If Else Statements
```js 
function testSize(num) {
  // Only change code below this line
  if (num<5){
    return "Tiny"
  }
  else if (num<10){
    return "Small"
  }
  else if (num<15){
    return "Medium"
  }
  else if (num<20){
    return "Large"
  }
  else (num >= 20)
    return "Huge"
  
  // Only change code above this line
}

// Change this value to test
testSize(7);
```
[TOP](#top)
___
### 72. Golf Code 
```js 
var names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  // Only change code below this line
  
  if(strokes==1){
    return "Hole-in-one!";
  }
  else if (strokes<=par-2){
    return "Eagle";
  }
  else if(strokes==par-1){
    return names[2];
  }
  else if(strokes==par){
    return names[3];
  }
  else if (strokes == par + 1){
    return names[4];
  }
 else if (strokes == par + 2){
    return names[5];
  }
  else if (strokes >= par +3){
    return names [6]
  }
  else {
    return "nothing to do"
  }
  

  // Only change code above this line
}

// Change these values to test
golfScore(5, 4);
```

> Comments: In order to understand what the par and stroke mean I watched this video [The Rules of Golf - EXPLAINED!](https://www.youtube.com/watch?v=IcaFTHeVQ7w&t=175s)
  

[TOP](#top)
___

### [80: Build JavaScript Objects](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/build-javascript-objects)
```js 
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};

// Only change code below this line.

var myDog = {
  name: "pawpatrol",
  legs: 4,
  tails: 1,
  friends: ["zuma", "sky"],
};
```
[TOP](#top)
___



### [81. Accessing Object Properties with Dot Notation](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-object-properties-with-dot-notation)

```js 
// Setup
var testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};

// Only change code below this line

var hatValue = testObj.hat;      // Change this line
var shirtValue = testObj.shirt;    // Change this line
```
[TOP](#top)
___ 


### [82. Accessing Object Properties with Bracket Notation](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-object-properties-with-bracket-notation)

```js 
// Setup
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};

// Only change code below this line

var entreeValue = testObj["an entree"];   // Change this line
var drinkValue = testObj["the drink"];    // Change this line
```

___ 

[TOP](#top)

### [83. Accessing Object Properties with Variables](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-object-properties-with-variables)

```js 
// Setup
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};

// Only change code below this line;

var playerNumber = 16;       // Change this Line
var player = testObj[playerNumber];   // Change this Line
```

___ 

[TOP](#top)

### [84:Updating Object Properties ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/updating-object-properties)

```js 
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};

ourDog.name = "Happy Camper";

// Setup
var myDog = {
  "name": "Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.
// First way
myDog.name= "Happy Coder"
//Second way
 myDog["name"] = "Happy Coder";

```

___ 

[TOP](#top)

### [85: Add New Properties to a JavaScript Object ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/add-new-properties-to-a-javascript-object)

```js 
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"]
};

ourDog.bark = "bow-wow";

// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};

// Only change code below this line.
myDog.bark = "woof";
myDog["bark"]= "woof"
```

___ 

[TOP](#top)

### [86:Delete Properties from a JavaScript Object ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/delete-properties-from-a-javascript-object)

```js 
// Example
var ourDog = {
  "name": "Camper",
  "legs": 4,
  "tails": 1,
  "friends": ["everything!"],
  "bark": "bow-wow"
};

delete ourDog.bark;

// Setup
var myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};

// Only change code below this line.

delete myDog.tails;

delete myDog["tails"];

```

___ 

[TOP](#top)

### [87:Using Objects for Lookups ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/using-objects-for-lookups)

```js 
// Setup
function phoneticLookup(val) {
  

  var lookup = {
    "alpha": "Adams",
    "bravo": "Boston",
    "charlie": "Chicago",
    "delta": "Denver",
    "echo": "Easy",
    "foxtrot": "Frank"
  };
  var result = lookup[val];
  return result;
}

// Change this value to test
phoneticLookup("delta");
```

___ 

[TOP](#top)

### [88:Testing Objects for Properties ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/testing-objects-for-properties)

```js 
// Setup
var myObj = {
  gift: "pony",
  pet: "kitten",
  bed: "sleigh"
};

function checkObj(checkProp) {
  // Your Code Here
  if (myObj.hasOwnProperty(checkProp) == true){
    return myObj[checkProp];
  }else {
    return "Not Found";
  }
  

} 

// Test your code by modifying these values
checkObj("gift");
```

___ 

[TOP](#top)

### [89:Manipulating Complex Objects ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/manipulating-complex-objects)

```js 
var myMusic = [
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [ 
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  }, // comma is added, it is important
  // Add record here

  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [ 
      "CD",
      "8T",
      "LP"
    ],

  }
];

```

___ 

[TOP](#top)

### [90:Accessing Nested Objects ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-nested-objects)

```js 
// Setup
var myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

var gloveBoxContents = myStorage.car.inside["glove box"]; // Change this line

```

___ 

[TOP](#top)

### [91:Accessing Nested Arrays ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/accessing-nested-arrays)

```js 
// Setup
var myPlants = [
  { 
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }  
];

// Only change code below this line

var secondTree = myPlants[1].list[1]; // Change this line

```

___ 

[TOP](#top)

### [92:Record Collection **_HARD_** ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/record-collection)

```js 

```

___ 

[TOP](#top)

### [93:Iterate with JavaScript While Loops ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/iterate-with-javascript-while-loops)

```js 
// Setup
var myArray = [];

// Only change code below this line.
var i = 0;
while(i<5){
    myArray.push(i);
    i++;
}

```

___ 

[TOP](#top)

### [94:Iterate with JavaScript For Loops ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/iterate-with-javascript-for-loops)

```js 
// Example
var ourArray = [];

for (var i = 0; i < 5; i++) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (i=1; i<6; i++){
    myArray.push(i);
}

```

___ 

[TOP](#top)

### [95:Iterate Odd Numbers With a For Loop ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/iterate-odd-numbers-with-a-for-loop)

```js 
// Example
var ourArray = [];

for (var i = 0; i < 10; i += 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (i = 1; i<10; i += 2){
  myArray.push(i)
}

```

___ 

[TOP](#top)

### [96:Count Backwards With a For Loop ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/count-backwards-with-a-for-loop)

```js 
// Example
var ourArray = [];

for (var i = 10; i > 0; i -= 2) {
  ourArray.push(i);
}

// Setup
var myArray = [];

// Only change code below this line.
for (i= 9; i>0; i -= 2){
  myArray.push(i);
}

```

___ 

[TOP](#top)

### [97:Iterate Through an Array with a For Loop](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/iterate-through-an-array-with-a-for-loop)

```js 
// Example
var ourArr = [ 9, 10, 11, 12];
var ourTotal = 0;

for (var i = 0; i < ourArr.length; i++) {
  ourTotal += ourArr[i];
}

// Setup
var myArr = [ 2, 3, 4, 5, 6];
var total= 0;
// Only change code below this line
for (i=0; i<myArr.length; i++){
  total += myArr[i];
}

```

___ 

[TOP](#top)

### [98:Nesting For Loops ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/nesting-for-loops)

```js 
function multiplyAll(arr) {
  var product = 1;
  // Only change code below this line
  for (var i= 0; i<arr.length; i++){
    for (var j=0; j<arr[i].length; j++){
      product = product * arr[i][j];

    }
  }
  // Only change code above this line
  return product;
}

// Modify values below to test your code
multiplyAll([[1,2],[3,4],[5,6,7]]);

```

___ 

[TOP](#top)

### [99:Iterate with JavaScript Do...While Loops ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/iterate-with-javascript-do---while-loops)

```js 
// Setup
var myArray = [];
var i = 10;

// Only change code below this line.

do {
  myArray.push(i);
  i++;
}while (i < 11) 

```

___ 

[TOP](#top)

### [100: Profile Lookup ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/profile-lookup/)

```js 

```

___ 

[TOP](#top)

### [101:Generate Random Fractions with JavaScript ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/generate-random-fractions-with-javascript)

```js 
function randomFraction() {

  // Only change code below this line.

  return Math.random();

  // Only change code above this line.
}
```

___ 

[TOP](#top)

### [102:Generate Random Whole Numbers with JavaScript ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/generate-random-whole-numbers-with-javascript)

```js 
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

function randomWholeNum() {

  // Only change code below this line.

  return Math.floor(Math.random()*10);
}
```

___ 

[TOP](#top)

### [103: Generate Random Whole Numbers within a Range ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/generate-random-whole-numbers-within-a-range)

```js 
// Example
function ourRandomRange(ourMin, ourMax) {

  return Math.floor(Math.random() * (ourMax - ourMin + 1)) + ourMin;
}

ourRandomRange(1, 9);

// Only change code below this line.

function randomRange(myMin, myMax) {

  return Math.floor(Math.random() * (myMax -myMin + 1)) + myMin

; // Change this line

}

// Change these values to test your function
var myRandom = randomRange(5, 15);
```

___ 

[TOP](#top)

### [104:Use the parseInt Function ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/use-the-parseint-function)

```js 
function convertToInteger(str) {
  return parseInt(str);
}

convertToInteger("56");
```

___ 

[TOP](#top)

### [105:Use the parseInt Function with a Radix ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/use-the-parseint-function-with-a-radix)

```js 
function convertToInteger(str) {
  return parseInt(str, 2);
}

convertToInteger("10011");
```

___ 

[TOP](#top)

### [106:Use the Conditional (Ternary) Operator ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/use-the-conditional-ternary-operator)

```js 
function checkEqual(a, b) {
  return a == b ? true : false;
}

checkEqual(1, 2);
```

___ 

[TOP](#top)

### [107:Use Multiple Conditional (Ternary) Operators](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/use-multiple-conditional-ternary-operators)

```js 
function checkSign(num) {
    return (num === 0) ? "zero" : (num>0) ? "positive" : "negative";
}

checkSign(10);
```

___ 

[TOP](#top)

  * [Golf Code](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/golf-code/) , 
  * [counting cards](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/counting-cards/),  
  * [Record Collection](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/record-collection), 
  * [98:Nesting For Loops ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/nesting-for-loops), 
  * [Profile Lookup](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/profile-lookup/)
  * [103: Generate Random Whole Numbers within a Range ](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/generate-random-whole-numbers-within-a-range)
  * 
