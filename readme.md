# Simple Calculator Program in C

## Introduction

This program is a basic calculator written in C that allows users to perform arithmetic operations like addition, subtraction, multiplication, and division. The user inputs two numbers and an operator, and the program outputs the result of the operation.

## Files

- **main.c**: Contains the source code for the calculator program.

## Requirements

- A C compiler (e.g., GCC).
- A terminal or IDE that supports C programming.

## How to Compile

To compile the program, use the following command in your terminal or command prompt:

```bash
gcc -o calculator main.c
```

This command will compile `main.c` and produce an executable file named `calculator`.

## How to Run

After compiling the program, run it by executing the following command:

```bash
./calculator
```

The program will prompt you to enter the following:

1. The first number.
2. An arithmetic operator (`+`, `-`, `*`, `/`).
3. The second number.

## Example Usage

```
Enter first number: 5
Enter an operator (+, -, *, /): *
Enter second number: 3
5.00 * 3.00 = 15.00
```

## Error Handling

- **Division by Zero**: The program checks for division by zero and outputs an error message if the user attempts to divide by zero.
- **Invalid Operator**: If the user inputs an operator other than `+`, `-`, `*`, or `/`, the program will display an "Invalid operator!" message.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

[Sounak Kundu]