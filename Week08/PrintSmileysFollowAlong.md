# Print Smileys: Follow-Along
Create a program that will print some smiley faces based on a user's input.

## Part 1 - Defining the smiley face method
The smiley face method should print a certain number of smiley faces based on a parameter.

1. Define a new method named `PrintSmiley` in the `Program.cs` file
    - The method should take in one `int` parameter (`numSmileys`)
    - The method should return `void` (nothing)
1. In the body of the `PrintHat` method, create a `for` loop
    - The `for` loop should execute `numSmileys` times
1. In the body of the `for` loop, print a smiley face (`:)`)

#### Code
```cs
public static void PrintSmileys(int numSmileys)
{
    for (int i = 0; i < numSmileys; i++)
    {
        Console.WriteLine(":)");
    }
}
```

## Part 2 - User input
The main program should ask the user how many smileys to print. If they enter a number less than zero, the program should display an error message.

1. In the `Main` method, display a message asking the user how many smileys they would like
1. Convert their input into an `int`, and store it in a variable
1. Use an `if` statement to check if the number they entered is positive
    - If it is positive, call the `PrintSmiley` method with the number as an argument
    - If it is not positive, display a message saying "Please enter a positive number"

#### Code
```cs
Console.WriteLine("How many smileys would you like?");
int num = Convert.ToInt32(Console.ReadLine());

if (num > 0)
{
    PrintSmileys(num);
}
else
{
    Console.WriteLine("Please enter a positive number");
}
```