## Homework Week 3
[`...`](https://github.com/HackYourFuture/JavaScript1/blob/master/Week3/MAKEME.md)
## Step 4: String and Array challenges

_Deadline Wednesday_

> For all the following exercises create a new .js file. Try to find a proper name for each file or make a small comment about what it does inside for future reference

_IMPORTANT NOTE_
In each assignment write at least two `console.log` statements to verify if your code works correctly. In other words proof that you code works as expected. If you need inspiration look at the steps defined in the assignments from last week.

1\. **Strings!**

> Consider the following string:
> 
> ```js
> let myString = "hello,this,is,a,difficult,to,read,sentence";
>```

>1\.1 Add the string to your file and log it.<br />
1\.2 Log the length of `myString`.<br />
1\.3 The commas make that the sentence is quite hard to read. Find a way to remove the commas from the string and replace them with spaces.<br />
1\.4 Log `myString` to see if you succeeded.<br />

 * **codelawer's solution** : [pytut](http://tinyurl.com/y45wb3o2)
 ```js
let myString = "   hello1this1is,a.  difficult.   to,read,   sentence   ";
console.log(myString.length);
let a = myString.replace(/[,,.,1]/g, " ").trim(); // trim() replace the whitespace left and right side of the quotations. not inside.
console.log(a.length);
 ```
 
 [TOP](#Homework_Week_3)
___
2\. **Arrays!**

>Consider the following array:

>```js
>let favoriteAnimals = ["blowfish", "capricorn", "giraffe"];
>```

>2\.1 Add a statement that adds Mauro's favorite animal _'turtle'_ to the existing array.<br />
2\.2 Log your new array!<br />
2\.3 Now add Jim's favorite animal to the array, it's _'meerkat'_, but make sure it will be placed after _'blowfish'_ and before _'capricorn'_.<br />
2\.4 Write a console.log statement that explains in words _you think_ the new value of the array is.<br />
2\.5 Log your new array!<br />
2\.6 Log the length of the array, add a message: _'The array has a length of: '_ (here you should show the length of the array).<br />
2\.7 Jason does not like _'giraffe'_, delete this animal from the array.<br />
2\.8 Again log your new array.<br />
2\.9 Now if unlike Jim, you don't like _'meerkat'_ and you want to delete it from the array, but you don't know the position or the `index` of the item in the array, how can you find it?<br />
2\.10 Log the index of _'meerkat'_. Add a message so it says: _'The item you are looking for is at index: '_ (here you should show the index of the item).<br />

* **codelawer's solution** : [pytut](http://tinyurl.com/y45wb3o2)
 ```js

let favoriteAnimals = ["blowfish", "capricorn", "giraffe"];
favoriteAnimals[3] ="turtle" //also possible{"Mauro's favorite animal" :"turtle"};
console.log(favoriteAnimals); // [ 'blowfish', 'capricorn', 'giraffe', 'turtle' ]
favoriteAnimals.splice(1,0, "meerkat"); // splice (index, (0:insert, 1: replace), "element");
console.log(favoriteAnimals); // [ 'blowfish', 'meerkat', 'capricorn', 'giraffe', 'turtle' ]
console.log('The array has a length of: ' + favoriteAnimals.length); // The array has a length of: 5
favoriteAnimals.splice(3,1); // 
console.log(favoriteAnimals.indexOf("meerkat")); // 1 (index)
console.log('The item you are looking for is at index: ' + favoriteAnimals.indexOf("meerkat"));
 ```
 
 Notes `push() / pop()— add/remove elements from the end of the array
        unshift() / shift()— add/remove elements from the beginning of the array
        concat()— returns a new array comprised of this array joined with other array(s) and/or value(s)`
        
[TOP](#Homework_Week_3)
___
## More JavaScript

>1. Create a function that takes 3 arguments and returns the sum of the these arguments.
    
    ```js 
    function myFunction(param_1, param_2, param_3){
      let result =  param_1 + param_2 + param_3; 
      return result;
    };
    let arg_1 = 5, arg_2 = 10, arg_3 = 15;
    console.log(myFunction(arg_1, arg_2, arg_3)); //30
    ```
___
>2. Create a function named `colorCar` that receives a color, and prints out, _'a red car'_ for example.

```js 
function colorCar (color) {
    let result = "a " + color + " car";
    return result;
  };
console.log(colorCar("red")); // a red car
  
```
___
>3. Create an object and a function that takes the object as a parameter and prints out all of its properties and values.
    * first method; [for more information](https://zellwk.com/blog/looping-through-js-objects/)
```js 
function myFunction (object){
  return object;
  };
  
let myObject = {
  name: "Honda",
  color: "white",
  "production date": "2015",
  age: 4,
  }
let foo = Object.entries(myObject); // to change object to array
console.log(myFunction(foo));
```
   * second method;
 
 ```js 
 function myFunction (object){
  return object;
  };
  
let myObject = {
  name: "Honda",
  color: "white",
  "production date": "2015",
  age: 4,
  }

console.log(myFunction(myObject));
 ```
    
___
>4. Create a function named `vehicleType` that receives a color, and a code, 1 for car, 2 for motorbike. And prints _'a blue motorbike'_ for example when called as `vehicleType("blue", 2)`

```js 
function vehicleType (color, code){  
    switch(code){
      case 1:
      return color + " " + "car";
      break;
      case 2:
      return color + " " + "motorbike"
      };
}
 /* 
   if (code === 1){
        code = "car";
    }else if (code ===2){
      code = "motorbike";
    } 
*/
  
console.log(vehicleType("blue", 2));
```



> 5. Can you write the following without the `if` statement, but with just as a single line with `console.log(...);`?

   ```js
   if (3 === 3) {
     console.log("yes");
   } else {
     console.log("no");
   }
   ```
* **codelawer's solution** : [pytut](http://tinyurl.com/y6pnt99c)
 ```js
 var ternaryOperator = 3 === 3 ? "yes" : "no";
 console.log(ternaryOperator);
 ```
[TOP](#Homework_Week_3)
___
> 6. Create a function called `vehicle`, like before, but takes another parameter called `age`, so that `vehicle("blue", 1, 5)` prints _'a blue used car'_

```js 
function vehicleType (color, code, age){  
    

   if (code === 1){
        code = "car";
    }else if (code ===2){
      code = "motorbike";
    } else {
      console.log("please enter 1 or 2")
      return}
    
    age>0 ? age = "used" : age = "new";
      
    let result = `a ${color} and ${age} ${code}`
    return result
}
console.log(vehicleType("blue", 1, 1));
```

7. Make a list of vehicles, you can add `"motorbike"`, `"caravan"`, `"bike"`, or more.

8. How do you get the third element from that list?

9. Change the function `vehicle` to use the list of question 7. So that `vehicle("green", 3, 1)` prints "a green new bike".

10. Use the list of vehicles to write an advertisement. So that it prints something like: `"Amazing Joe's Garage, we service cars, motorbikes, caravans and bikes."`. (Hint: use a `for` loop.)

    > Hint, the output should be correct English with all the punctuation in place (that's the challenge). So plurals for the vehicle types, commas followed by a single space, the word and to replace the final comma and closed off by a period.

11. What if you add one more vehicle to the list, can you have that added to the advertisement without changing the code for question 10?

12. Create an empty object.

13. Create an object that contains the teachers that you have had so far for the different modules.

14. Add a property to the object you just created that contains the languages that they have taught you.

15. Write some code to test two arrays for equality using `==` and `===`. Test the following:

    ```js
    let x = [1, 2, 3];
    let y = [1, 2, 3];
    let z = y;
    ```

    What do you think will happen with `x == y`, `x === y` and `z == y` and `z == x`? Prove it!

    > Don't cheat! Seriously - try it first.


    Check out this [Fiddle](http://jsfiddle.net/jimschubert/85M4z/). You need to open your browser’s Developer Tools to see the console output. Press the Run button in the upper right corner to run the code.

    More insights from this [Stack Overflow question](http://stackoverflow.com/questions/22395357/how-to-compare-two-arrays-are-equal-using-javascript).

> 16. Take a look at the following code:

    ```js
    let o1 = { foo: "bar" };
    let o2 = { foo: "bar" };
    let o3 = o2;
    ```

    Show that changing `o2` changes `o3` (or not) and changing `o1` changes `o3`(or not).

    Does the order that you assign (`o3 = o2` or `o2 = o3`) matter?
    
   * **codelawer's solution** : [pytut](http://tinyurl.com/y45wb3o2)
 ```js
 ```
[TOP](#Homework_Week_3)
___

> 17. What does the following code return? (And why?)

    ```js
    let bar = 42;
    typeof typeof bar;
    ```

> ‘Coerce' means to try to change - so coercing `var x = '6'` to number means trying to change the type to number temporarily.

* **codelawer's solution** : [pytut](http://tinyurl.com/y45wb3o2)
 ```js
 ```
[TOP](#Homework_Week_3)
___
