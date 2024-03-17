# Input
This topic adds the **input** command to the prior learning about output and variable assignment.

## Learning Objectives/Goals

Students will learn to interpret, trace, identify and create python code that uses:

|Concept|Explanation|Python Code|Examples|
|:---|:---|:---:|:---|
|Input|Collecting data for processing.  In these examples we collect input that the user types on the keyboard but computers collect input in lots of ways - as sound, mouse movements, with sensors etc. ** Input must ALWAYS be assigned to a variable** or it will not be stored.  All input is treated as **strings**. Any input that needs to be treated as a number must be **cast** into the new format.|variableName = input()|print("What's your name?")  name = input()    print("Guess the secret number"  guess = int(input())| 

## Slide Deck

[The slide deck for this topic can be found here](https://docs.google.com/presentation/d/1iQtjLPF7ZCsytrZSkp3I_v9uE4SvYNA8x5TQLKQETJU/edit?usp=sharing)

## TEACHER NOTES

### Prior Learning

- Algorithms - sequences of instructions for a task.

- Output - the information presented to the user by the computer.  In our programs output will be in the form of text on screen.

- Strings - data in text format

- Syntax - the format that code is written in.  If code is not written in the correct format it creates a **syntax error **and the program will not run.

- Variable - a placeholder for information that can change as the program runs.

- Variable assignment - Using the '=' symbol to store data in a variable.

- Concatenation - joining the contents of variables to other variables and/or strings in output.

### New Learning

- Input - the data collected by the computer. In our programs input will be in the form of the user typing in.  Input **must** be assigned to a variable or it will be discarded by the program.

## CODE EXAMPLES

Assign string input to a variable.

```
variable = input()
```

Assign integer input to a variable.

```
variable = int(input())
```

## PRIMM Task - Modify

In the **modify** tasks, students adapt the example code to start to create code of their own.

Make sure that the students add comments to explain what the code does.

## Misconceptions/Errors to Watch Out For

- Students put the data into the brackets after the input command eg:
```
print("What's your name?")
name = input("Andy")
```
- Missing brackets after the 'input'
- Not pressing enter after typing in the input.
- Not assigning the input to a variable