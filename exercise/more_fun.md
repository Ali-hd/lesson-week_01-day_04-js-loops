1. Mia, Albert, and Tony are going to a party. Set "attendees" to an array of their names.

	```js
	attendees = [null];
```


1. Create the same array in a different way -- 
      by creating a new Array object.

	```js
	attendees = null;
```

1. Access the third element in the array. 

	```js
	attendees
```

1. Write a statement which sorts the array.

	```js
	attendees
```

1. Write a statement which removes the last 
     element of the array. 

	```js
	attendees
```


1. Write a statement which shifts a new element
     into the array as element 0 -- "Elaine"
	
	```js
	attendees
```


1. `console.log` the following poem. Do it using 
	a single console.log statement! Make sure there
	are four separate lines in the console output. 

	Computers are fun,
	Because they are neat.
	Javascript and Ruby,
	They cannot be beat! */

	```js
	console.log(null);
```



## WHILE LOOPS


1. Fix the below while loop so that the user
     is continually asked whether he or she is done. 
     Continue looping while the user enters "no".
     Remember you can place console.log statements
     inside loops to "see" the values change. 

	```js
var isDone = "no";
while (isDone === null) {
	isDone = prompt("Are you done?");
}
```


1. Modify the solution to the above while loop
     below. Now, continue looping if "no" OR "No"
     is entered.

	```js
var isDone = "no";
while (isDone === null) {
	isDone = prompt("Are you done?");
}
```



1. Explain to each other in English what this statement
     does. It should be a simple statement.
     Look up functions such as Math.round() and 
     Math.random() if they are new. Try pasting the
     individual parts of this statement into
     your console to better understand it!

	```js
var theTarget = Math.round(100 * Math.random()) + 1;
```


1. Number guessing game. While the guess is not
     the target value, continue asking the user
     for a guess and informing whether the guess
     is too low or too high. 

	```js
var guess = 0;
var theTarget = Math.round(100 * Math.random()) + 1;
while (null) {
	guess = prompt("Make a guess!");

	if (null) {
		alert("Too high!");
	} else if (null) {
		alert("Too low!");
	}
}
```


1. The following while loop implements a 
      "count up" clock. Make it console.log the
      numbers 1, 2, 3, 4, and 5.

	```js
var i = null;
while (i < null) {
	console.log(null);
	null;
}
```



## FOR LOOPS


1. Rewrite the "count up" clock as a for loop!

	```js
for (null; null; null) {
	console.log(null);
}
```

1. Rewrite the for loop to have no initial conditions.

	```js
null;
for (; null; null) {
	console.log(null);
}
```

1. Rewrite the for loop to have no incrementing statement.

	```js
for (null; null; ) {
	console.log(null);
	null;
}
```

1. Rewrite the for loop to have no incrementing or intial
     statements.
     
	```js
null;
for (; null; ) {
	console.log(null);
	null;
}
```

	/* Note that this is identical to the while loop! */


1. Let's make a count DOWN clock. We will display 
     5, 4, 3, 2, 1, 0.

	```js
var i = null;
while (i >= null) {
	console.log(null);
	null;
}
```

1. Now, rewrite the countdown clock as a for loop!

	```js
for (null; null; null) {
	console.log(null);
}
```


1. Using a for loop, print each value of the array
     to the console.

	```js
var foods = ["Burger", "Fries", "Drink", "Tomato"];
for (i=0; i<null; null) {
	console.log(null);
}
```

1. Using a for loop, print each value of the array
     to the console, backwards!
     
	```js
var foods = ["Burger", "Fries", "Drink", "Tomato"];
for (i=foods.length-1; null; null) {
	console.log(null);
}
```


## FUNCTIONS


1. Given the following function, call the function with
     appropriate example values. In a comment, write
     what the expected output will be.
     
	```js
	function concatStrings(str, appendString) {
		return str + appendString;
	}
	
	concatStrings(null);  // output is: 
```

1. Write a function that takes one number as a parameter,
     and returns that number plus one. Choose good 
     variable names! Call the function with an appropriate
     parameter.

	```js
	function increment(badParameterName) {
		return null;
	}
	
	increment(null);  // output is: 
```

1. Complete the below function. It accepts a 
	 number and returns a string with "a" repeated 
	 that many times. For example, calling the 
	 function with 3 will return "aaa". 
     Use a for loop to construct the return
     string. Call the function
     with example values and write the output as
     a comment. 

	```js
	function repeatA(numTimesRepeated) {
		var returnString = "";
	
		for (null; null; null) {
			returnString += "a";
		}
		
		return returnString;
	}
	
	repeatA(null);   // output is: 
```

1. Let's generalize the last function. Now, a 
     second parameter will be passed which is the
     character (or string) to repeat! Call the function
     with example values and write the output as
     a comment. 

	```js
	function repeatString(numTimesRepeated, stringToRepeat) {
		// modify the last function's code
	}
	
	repeatString(null, null);  // output is: 
```

1. Write a function which returns the original array,
     but reversed!

	```js
	function reverseStrings(arrayOfStrings) 
	{
		var reversedArray = [];
	
		for (i=arrayOfStrings.length-1; null; null) {
			reversedArray.push(null);
		}
	
		return reversedArray;
	}
	
	var foods = ["Burger", "Fries", "Drink", "Tomato"];
	reverseStrings(foods);

	/* Note that variables can be assigned functions. */

	var someVariable = repeatA;
	var anotherVariable = repeatA;
```

1. Try running the above two lines in your browser.
     Now, try calling the functions by using the
     new variables. (i.e. run the below code!)
     
	```js
someVariable(3);
anotherVariable(5);

	/* This is an important fact about JavaScript --
     functions can be assigned to variables and 
     passed around as arguments to functions! */
```

