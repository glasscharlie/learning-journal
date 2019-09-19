# Loops
### Loops
- Check a condition, if it returns true, a code block will run. Then the condition will be checked again, and if it still returns true, the code block will run again.It repeats until the condition returns false.

### Three common types of loops
> For - runs a loop a specific number of times

> While - If you don't know how many times the code should run, use a while loop. The condition can be something other than a counter.

> Do While - Same as while loops but it will always run it once, even if the conition starts out false

### Loop counters
- A for loop uses a counter as a condition

- Initialization - create a variable and seet it to 0, often called i
> var i - 0;

- Condition - the loop should continue to run until the counter reachs a certain number
> i < 10;

- Update - Every time the loop has run the satement in the curly brackets, it adds one to the counter
> i++

### Key loop concepts

- Keyworks
> break - causes the termination of the loop and tells interpreter to go to the next statement

> continue - tells the interppreter to continue with the iteration

- Loops and arrays
> Looops are very helpful when dealing with arrays if you want to run the same code for each item in the array

- Performance issues
> When a browser comes across JavaScript, it will stop doing anything else until it has processed the script

> If your loop contains a lot of items, it makes the page load slower

>If the condition never returns false, you get what is referred to as an infinite loop