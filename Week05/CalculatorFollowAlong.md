# Calculator - FollowAlong
Start by creating a new `.cs` file/project. Then, follow the instructions below to create a simple calculator application.

## Part 1 - User Input
To begin, the program should ask the user to enter two numbers, and then enter the operation to perform. Assume the user will enter valid integer numbers.

### First Number
1. Use `Console.WriteLine` to ask the user to enter the first number
1. Use `Console.ReadLine` to receive the input from the user
1. Use `Convert.ToInt32` to convert the user's input into an `int`
1. Make sure to store the result in a variable

#### Code
```cs
Console.WriteLine("Enter a:");
int a = Convert.ToInt32(Console.ReadLine());
```

### Second Number
Repeat the steps for the first number, but store a second `int` variable for the second number.

#### Code
```cs
Console.WriteLine("Enter b:");
int b = Convert.ToInt32(Console.ReadLine());
```

### Operation
1. Use `Console.WriteLine` to ask the user for an operation
1. Use `Console.ReadLine` to receive the input from the user
1. Make sure to restore the result in a `string` variable

```cs
Console.WriteLine("What operation to perform?");
string operation = Console.ReadLine();
```

## Part 2 - Addition
Create a method to add two numbers together, and use it when the user would like to perform the plus operation.

### Defining the Method
Start with the method signature:
- Visibility: `public`
- Modifier: `static`
- Return type: `int`
- Name: `AddNumbers`
- Parameters: `int integer1`, `int integer2`

In the body of the method:
- Add the two `int`s together
- Return the result

#### Code
```cs
public static int AddNumbers(int integer1, int integer2)
{		
    return integer1 + integer2;
}
```

### Calling the Method
1. In the `Main` method, after retrieving the input from the user, use an `if` to check if the user would like to add numbers
1. If the user would like to add numbers, call the `AddNumbers` method and store the result in a new variable  
    - The parameters for the `AddNumbers` call should be the input from the user (`a` and `b`)
1. Print the sum to the console

#### Code
```cs
if (operation == "+")
{
    int sum = AddNumbers(a, b);
    Console.WriteLine(sum);
}
```

## Part 3 - Subtraction
Repeat the steps for the addition method, but use subtraction instead of addition.

## Final Code
```cs
using System;
					
public class Program
{
	public static void Main()
	{
		Console.WriteLine("Enter a:");
		int a = Convert.ToInt32(Console.ReadLine());
		
		Console.WriteLine("Enter b:");
		int a = Convert.ToInt32(Console.ReadLine());
		
		Console.WriteLine("What operation to perform?");
		string operation = Console.ReadLine();
		
		if (operation == "+")
		{
			int sum = AddNumbers(a, b);
            Console.WriteLine(sum);
		}
		else if (operation == "-")
		{
			int difference = SubtractNumbers(a, b);
            Console.WriteLine(difference);
		}
	}
    
	public static int AddNumbers(int integer1, int integer2)
	{		
		return integer1 + integer2;
	}
	
	public static int SubtractNumbers(int integer1, int integer2)
	{		
		return integer1 - integer2;
	}
}
```