# Learning Material

---

Learning Material should adhere to the guidelines of the Writing Style portion. In addition, they will follow the criteria:

1. Show and tell. Show the code and explain it as thoroughly as you can without talking down to learners.

2. Use examples that have real-world meaning. This will help learners understand the impact and application of code.

3. Do not use examples can cause logical issues and are nonsensical. For example, the following would not require a function to this extent, but rather a simple return if/else statement.

   1. Form an array with two colors in it. Create a function and title it favoriteColor. Use Math.random to choose at random a favorite color. The function should return either of the two colors in your array depending on the result of Math.random. 

An example of learning material that will benefit the learner is as follows:

## Creating a While Loop

---

Oftentimes, you will want to write programs that perform repetitive tasks so as not to have to re-read code throughout. Loops execute code over and over again until your criteria is met to end the loop. Refer to this example as I explain each portion of it throughout this section.

```js
var i = 0;

while (i < 9) {
    console.log("I'm counting");
    i++;
}
```

In the while loop listed above, I have define that i is equal to zero. I do this because I need to tell the computer where i starts. Not that often in JavaScript, we start at counter 0 instead of 1. For example, when you create functions that cycle through arrays, each value in the array is assigned a numerical position starting with 0 and continuing to the last value in the array.

```js
var potentialClient = ["Jonathan", "Smitherson", "805-555-6647"];
```

The variable potentialClient is an array. "Jonathan" is at position 0; "Smitherson" is at position 1; and "805-555-6647" is at position 2. Note that i is an arbitrary designation that I have given as my counter. You will be able to tell that I have constructed it because it appears after the designation "var." I could have chosen a range of other names such as "counter," but opted for i because you will often see this designation in other tutorials across the web.

After I have assigned i the value of 0, I have said that while i is less than nine, I will print "I'm counting." So that I don't get stuff in an infinite loop \(that will crash my browser\), I have added to i at the end of each loop. So each time I go through the while loop, I am counting up. If i++ was not in included, i would always be less than nine and so the loop would not stop.

The following loop will run 9 times and print "I'm counting" 9 times. If you run this while loop in your Google Chrome console, the number 8 will also be printed after "I'm counting." Let's break down the function in discreet steps to demonstrate each portion of this process.  See the commented out portion below and refer to the loop to understand each step going on.

```js
var i = 0;

while (i < 9) {
    console.log("I'm counting");
    i++;
}

//var i starts at 0. While i is less than nine, we will print "I'm counting". 

//first loop: i = 0, while loop runs and prints "I'm counting"
//second loop: i = 1, while loop runs and prints "I'm counting"
//third loop: i = 2, while loop runs and prints "I'm counting"
//fourth loop: i = 3, while loop runs and prints "I'm counting"
//fifth loop: i = 4, while loop runs and prints "I'm counting"
//sixth loop: i = 5, while loop runs and prints "I'm counting"
//seventh loop: i = 6, while loop runs and prints "I'm counting"
//eighth loop: i = 7, while loop runs and prints "I'm counting"
//ninth loop: i = 8, while loop runs and prints "I'm counting"

//In the above, you see that the loop has run nine times. 
//Google Chrome prints 8 because i = 8 at the end of your loop.
```



