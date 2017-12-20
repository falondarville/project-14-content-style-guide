# Learning Material

---

Learning Material should adhere to the guidelines of the Writing Style portion. In addition, they will follow the criteria:

1. Show and tell. Show the code and explain it as thoroughly as you can without talking down to learners. 

2. Use examples that have real-world meaning. This will help learners understand the impact and application of code. 

3. Do not use examples can cause logical issues and are nonsensical. For example, the following would not require a function to this extent, but rather a simple return if/else statement.

   1. Form an array with two colors in it. Create a function and title it favoriteColor. Use Math.random to choose at random a favorite color. The function should return either of the two colors in your array depending on the result of Math.random. 

An example of learning material that will benefit the learner is as follows:

## Creating a while loop

---

Oftentimes, you will want to write programs that perform repetitive tasks so as not to have to re-read code throughout. Loops execute code over and over again until your criteria is met to end the loop. 

In the following example, I have define that i is equal to zero. I do this because I need to tell the computer where i starts. Not that often in JavaScript, we start at counter 0 instead of 1. For example, when you create functions that cycle through arrays, each value in the array is assigned a numerical position starting with 0 and continuing to the last value in the array. 

```

```

Then I have said that while i is less than nine, I will print "I'm counting." So that I don't get stuff in an infinite loop \(that will crash my browser\), I have added to i at the end of each loop. So each time I go through the while loop, I am counting up. If i++ was not in included, i would always be less than nine and so the loop would not stop. 

```
var i = 0;

while (i < 9) {
    console.log("I'm counting");
    i++;
}
```



