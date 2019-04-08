# Square Count: Challenge
Create a program that will count the number of perfect square numbers between 0 and 100. A perfect square is a number that is the product of a rational number multiplied by itself. For example, `9` is a perfect square (`3*3`), and so is `25` (`5*5`).

Start by creating a new C# project, then follow the steps below.

## `IsSquare` method
Copy the following method into your program. It will take in an `int`, and return a `bool` that says whether or not the integer is a perfect square.

```cs
public static bool IsSquare(int num)
{
    double sqrt = Math.Sqrt(num);
    return sqrt == Math.Floor(sqrt);
}
```

## Finding the squares
1. In the `Main` method, declare a new `List<int>` variable named `squares`
1. Initialize the value of `squares` to a new empty list
1. Create a `for` loop that will iterate through the numbers 0-100
    - `for` keyword
    - initializer (use `i` as the variable)
    - condition
    - increment
1. In the body of the `for` loop, use an `if` statement to check whether the current number (`i`) is a square
    - Pass `i` as an argument to the `IsSquare` method
1. If `i` is a square, `Add` it to the `squares` list

## Printing the count
1. In the body of the `Main` method, beneath the `for` loop, find the `Count` of the `squares` list
1. Store the count in a variable
1. Display a message to the user informing them of the count

Try running the program. It should have a count of `11`. If the count says `10`, there may be an off-by-one error!

## Squaring a number
One interesting side effect for this list of perfect squares is that each item in the list is the square of its own index. For example, the item at index `0` in the list is `0`, the item at index `4` in the list is `16`, and so on. It is possible to use this list to calculate squares without having to do the math!

1. In the body of the `Main` method, beneath the count message, display a message asking the user which number they would like to square
1. Store the number they enter as an `int` variable (`num`)
1. Declare a new variable that will hold the number squared
1. Set the variable to the item in the `squares` list at position `num`
1. Display a message to the user telling them the square value
    - Ex. If they enter `6`, "6 squared is 36"

## Extra Challenges
### Custom limit
Instead of counting all the squares from 0-100, allow the user to enter the upper limit. Use the number they enter in the `for` loop instead of `100`.

### Better error handling
When squaring a number, do not allow the user to square a number outside the range of the list. For example, if they wish to square the number `20`, but there fewer than `21` items in the list, display a message saying "Number not within range."