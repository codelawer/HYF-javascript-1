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

...<br>

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

### Understanding Boolean Values

```js 
function welcomeToBooleans() {

// Only change code below this line.
return true; // Change this line(Initial its false)

// Only change code above this line.
}
```

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

### Golf Code
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

> Comments: ```In order to understand what the par and stroke mean I watched this video : [The Rules of Golf - EXPLAINED!](https://www.youtube.com/watch?v=IcaFTHeVQ7w&t=175s)```
  
<a href="#top">TOP</a>

### 
```js 

```
