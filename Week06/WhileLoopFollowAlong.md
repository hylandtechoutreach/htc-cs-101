# Factorial using a While Loop - FollowAlong
Start by creating a new `.cs` file/project. Then, follow the instructions below to create a factorial while loop application.
>Factorial is the product of an integer and all the integers below it; e.g. factorial four ( 4! ) is equal to 4 * 3 * 2 * 1 = 24

## Part 1 - User Input
First, ask the user for an integer to find the factorial. 

### Input
1. Use `Console.WriteLine` to ask the user to enter an integer. 
1. Use `Console.ReadLine` to receive the input from the user.
1. Use `Convert.ToInt32` to conver the user's input from a `string` to an `int`.
1. Make sure to store the result in a variable. 

### Code
```cs
Console.WriteLine("Enter a whole number: ");
int num = Convert.ToInt32(Console.ReadLine());
```

## Part 2 - While Loop
Second, we will create the while loop. To start, we will initialize the counter and the result variable.

### Counter & Sum
We want to use a counter that starts at the integer the user provided and the result starts at 1. 

1. Since we will be counting backwards, we want to start the counter at the number the user provides.

1. Also, we are going to be multiplying the result by the counter, so we don't want to start at 0 or the result will always be 0!

### Code

```cs
int i = num, result = 1;
```

### While Loop Condition
We are going to be counting down and want to stop when we are out of integers to multiply, so we want to go until the counter is equal to 0 but not if the counter is 0.

We will accomplish this by using the boolean operator `>`.

### Code

```cs
while (i > 0)
```

### While Loop Body
Now, we need to do the math funtion! Start with brackets and then add the arithmetic statement that we learned last week to multiply the variable by a number and assign the result to the variable. 

We also need to decrement the counter to keep the loop going. We do this with `i--;`.

### Code

```cs
while (i > 0)
{
    result *= i;

    i--;
}
```

## Part 3 - Print the results to screen
Finally, we need to let the user know what the answer is! We will do this with `Console.WriteLine()` outside of the while loop.

### Code 

```cs
Console.WriteLine("Factorial of " + num + "is " + result);
```

## Final Code

```cs
using System;
					
public class Program
{
	public static void Main()
	{

         Console.WriteLine("Enter a whole number");
         int num = Convert.ToInt32(Console.ReadLine());

         int i = num, result = 1;

         while (i > 0)
         {
             result *= i;

             i--;
         }

         Console.WriteLine("Factorial of " + num + "is " + result);
    }
}
```


