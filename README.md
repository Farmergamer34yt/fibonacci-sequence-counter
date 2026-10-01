# Fibonacci Sequence Generator

A small Python program I made while learning the fundamentals of Python. It generates and prints a specified number of values from the Fibonacci sequence.

This is one of my earlier programming exercises and was mainly created to practice **variables, lists, loops, indexing, and user input**.

## What It Does

The program asks the user how many numbers of the Fibonacci sequence they want:

```text
what is m: 10
```

It then generates and prints the requested number of Fibonacci numbers:

```text
0 1 1 2 3 5 8 13 21 34
```

## How It Works

The program starts with the first two Fibonacci numbers:

```python
fib = [0, 1]
```

It then uses a `while` loop to generate the remaining numbers.

The next Fibonacci number is calculated by adding the previous two numbers:

```python
fib[i-1] + fib[i-2]
```

The result is inserted into the list, and `i` is increased so the next number can be generated.

Once the requested number of values has been generated, a `for` loop goes through the list and prints each number.

## Concepts Practiced

This project helped me practice:

* Variables
* User input
* Integer conversion with `int()`
* Lists
* List indexing
* `while` loops
* `for` loops
* `range()`
* List `.insert()`
* Arithmetic operations
* Incrementing variables with `+=`
* Comments and code documentation

## Example

If the user enters:

```text
5
```

The program outputs:

```text
0 1 1 2 3
```

If the user enters:

```text
10
```

The program outputs:

```text
0 1 1 2 3 5 8 13 21 34
```

## Notes

There is also an alternative version of the program commented out in the source code. It uses a `for` loop instead of a `while` loop to generate the sequence.

I kept this version in the project because I was experimenting with different ways of accomplishing the same task and learning the differences between `while` and `for` loops.

