# Logic Gates
![](https://imgs.xkcd.com/comics/circuit_diagram.png)

## Introduction
In computing hardware, every circuit is built from boolean **logic gates**. These gates take in electrical signals (on or off) as input, and output electrical signals based on that input. For example, the **NOT** gate will output "off" if given "on," and "on" if given "off." The **AND** gate will take in two signals. It will output "on" if BOTH input signals are "on," and output "off" otherwise. There are many additional gates, and the gates come together to build much larger circuits that do everything in a CPU.

### All Logic Gates
View the table in this Wikipedia article to learn about all the different logic gates: https://en.wikipedia.org/wiki/Logic_gate#Symbols
- NOT
- AND
- OR
- NAND
- NOR
- XOR
- XNOR

### Truth tables
A **truth table** is a diagram in rows and columns showing how the truth or falsity of a proposition varies with that of its components. For example, a truth table for **AND** looks like this:

| A | B | A && B |
|-|-|-|
| T | T | T |
| T  | F | F |
| F | T | F |
| F | F | F |

Sometimes **1** and **0** are used in place of **T** and **F**.

## Basic Exercises
### Truth tables
Read this webpage (https://www.101computing.net/logic-gates-truth-tables/) and complete some of the exercises at the bottom. You should fill out the truth table for the given circuit, then click "Check Answer" to see if you completed it correctly. Then, click "Next" to move onto the next exercise.

### Boolean Expressions
Complete the exercises on this page: https://www.101computing.net/binary-logic/logic-gates-expressions.html

### Building Diagrams
Complete the exercises on this page: https://www.101computing.net/binary-logic/logic-gates-diagrams.html

### Building from NAND
NAND and NOR gates are "universal" gates, and thus any boolean function can be constructed using either NAND or NOR gates only. Try to build out each logic gate using only the NAND gate. Use paper and pencil to attempt this.

## Building Gates
Create a C# console application that is able to run inputs through different logic gates. First, the program should ask the user which gate they would like to use. Then, the program should ask them for their input values to the gate (either one single input, or multiple inputs). Finally, the program should provide the user with the output to the gate.

## Other resources of interest
- De Morgan's laws: https://en.wikipedia.org/wiki/De_Morgan%27s_laws
- Short-circuit evaluation: https://en.wikipedia.org/wiki/Short-circuit_evaluation 