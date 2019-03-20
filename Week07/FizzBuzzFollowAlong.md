# FizzBuzz: Follow-Along
FizzBuzz is a classic technical interview question. The problem is stated as follows:

Write a short program that prints each number from 1 to 100 on a new line. 
- For each multiple of 3, print "Fizz" instead of the number. 
- For each multiple of 5, print "Buzz" instead of the number. 
- For numbers which are multiples of both 3 and 5, print "FizzBuzz" instead of the number.

## Part 1 - `for` loop set up
1. Build out the `for` loop structure:
    - `for` keyword
    - Parentheses (`()`)
    - Within the parentheses: two semi-colons (`;`)
    - After the parentheses: curly brackets (`{}`)
1. Fill in the for loop init, conditional, and increment:
    - `int i = 1`
    - `i <= 100`
    - `i++`

```cs
for (int i = 1; i <= 100; i++) {

}
```

## Part 2 - Body of the `for` loop
1. Print the current number `i`
    - Verify that each number, 1 to 100, is printed
1. If `i` is a multiple of 3, print "Fizz"
    - Use modulo (`%`) to determine if `i` is divisible by `3`
    - Use an `if` and an `else` so that it does not print the number if divisible by 3
1. If `i` is a multiple of 5, print "Buzz"
    - Use an `else if` to accomplish this
1. If `i` is a multiple of 3 AND 5, print "FizzBuzz"
    - This has to be the first check

```cs
for (int i = 1; i <= 100; i++) {
    if (i % 3 == 0 && i % 5 == 0) {
        Console.WriteLine("FizzBuzz");
    } else if (i % 3 == 0) {
        Console.WriteLine("Fizz");
    } else if (i % 5 == 0) {
        Console.WriteLine("Buzz");
    } else {
        Console.WriteLine(i);
    }
}
```

## Part 3 - User input
1. Before the `for` loop, use `Console.ReadLine` to receive a number from the user
1. Convert the string into a number
1. Use the number as the top limit in the `for` loop

```cs
Console.WriteLine("Enter a Number");
int topNum = Convert.ToInt32(Console.ReadLine());

for (int i = 1; i <= topNum; i++) {
    if (i % 3 == 0 && i % 5 == 0) {
        Console.WriteLine("FizzBuzz");
    } else if (i % 3 == 0) {
        Console.WriteLine("Fizz");
    } else if (i % 5 == 0) {
        Console.WriteLine("Buzz");
    } else {
        Console.WriteLine(i);
    }
}
```